# ![Empire logo](EMPIRE_LOGO.png) Platform API

OpenAPI specification for the REST API of Empire, the allocation and nomination platform of BritNed.

The common OpenAPI specification (single YAML file) is available in the root of this repository. The recommended exploration of the options is to use the web-based navigation through it at [https://britned.github.io/empire-platform-api](https://britned.github.io/empire-platform-api)

## Notes for developers

- Usage of our API is subject to our [Terms of Use](API%20terms%20of%20use%20for%20EMPIRE%20by%20participants%20-%20v1.pdf), of which you find a PDF on this repository and a link on our website.

## Using the Python client SDK
​
The Python client is automatically generated from the OpenAPI specification and [published to PyPi](https://pypi.org/project/empire-platform-api-public-client/). To use the client with the authenticated API endpoints you will need to generate an API token in Empire.
​
After installing the package you will be able to use the client by first instantiating a `Configuration` class and creating an `ApiClient`:
​
```python
configuration = Configuration(
        api_key={"ApiKey": "<your empire api key>"},
        host="https://api.training.empire.britned.com"
    )
client = ApiClient(configuration=configuration)
```
​
During the testing phase of Empire we provide a single environment for testing at `https://api.training.empire.britned.com`. The `ApiClient` instance then can be used to construct individual clients for the different API categories.
​
An example for retrieving ten auctions ordered by the start of their bidding periods:
​
```python
    auction_api = AuctionApi(api_client=client)
    auctions = auction_api.get_auctions(limit=10, offset=0,
                                                      sort_by=AuctionSortBy.BIDDING_PERIOD_START_DESC)
    print(auctions)
```

## Changelog

Changes in particular versions of the API Specification (in the `openapi.yaml` file) are automatically tracked in [CHANGELOG.md](CHANGELOG.md).

- 2023-08-14 Added changelog generation for API changes
- 2023-08-10 Access multiple versions of the API spec on GitHub Pages
- 2023-07-19 Published a new version of the API spec and added instructions to use the python client
- 2023-04-04 Web-based navigation of the API spec, through GitHub Pages added, updated the README accordingly.
- 2023-04-03 Added Readme and open up the repository to the public internet
- 2023-03-27 API Terms of Use v1 published, effective 31.3.2023
- 2022-03-21 Place holder for Terms of Use 
