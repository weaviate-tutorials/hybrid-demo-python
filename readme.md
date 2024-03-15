# Hybrid Demo project

To run the project you need:
1. Set up Weaviate
    * Use Docker Compose
    * or create one with [WCS](https://console.weaviate.cloud/)
2. Install required libraries

## ==== Set up Weaviate ====

### Local – Docker
To run Weaviate locally, install Docker Compose.

Then run the following command at the root of the repo:
```
docker compose
```

Which will use the configuration in `docker-compose.yml` file.

### Cloud – WCS
If you want to run Weaviate in the cloud with WCS, head to [https://console.weaviate.cloud/](https://console.weaviate.cloud/), create an account and create a new instance (a free sandbox is good enough).

See the [WCS Quickstart](https://weaviate.io/developers/wcs/quickstart) for step-by-step guide.

## ==== Install required libraries ====

Create a new venv configuration.
```
python3 -m venv .venv
```

Then switch to the new configuration:
```
source .venv/bin/activate
```

And install the required packages.
```
pip install -r requirements.txt
```