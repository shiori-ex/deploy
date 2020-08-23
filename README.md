<img src="https://raw.githubusercontent.com/shiori-ex/graphics/master/rendered/banner-bg-4477x1000.png" width="100%" />

shiori is a web application to simply store, manage and search through links by meta variables like description or tags. [MeiliSearch](https://www.meilisearch.com/) is used therefore as high-performance full-text search database to provide blazingly fast search results even in huge datasets. The dataset will be accessable over a REST API via web or CLI application.

---

# Deployment

Best practice is to deploy shiori with Docker and docker-compose. In this repository, you can find an example and ready-to-run [`docker-compose.yml`](docker.compose.yml).

You can use this as base to set up on or integrate this into your current infrastructure.

Or just use it to play around with it on a local machine.