# Personal-OpenAI-UI

This project provides a Docker Compose setup to run Open WebUI with persistent storage and OpenAI API key integration.

## Prerequisites

- Docker installed on your system
- An OpenAI API key (see instructions below)

## Setup

Clone or download this repository.

## Running the Container

Start the container with:

```bash
docker compose up -d
```

Access Open WebUI in your browser at:

```
http://localhost:5001
```

change the port if required.

## Stopping the Container

To stop and remove the container:

```bash
docker compose down
```

## Setting up an OpenAI API Key

Setting up an OpenAI API key for use with Open WebUI to access ChatGPT models involves two primary steps: obtaining the API key from OpenAI and then configuring it within Open WebUI.

### 1. Obtaining the OpenAI API Key

* **Create an OpenAI Account:** If an account does not exist, navigate to the OpenAI website and sign up.
* **Access API Key Management:** Once logged in, locate the section for API Keys within the OpenAI dashboard or account settings. This is typically found under a profile menu or a dedicated "API Keys" section.
* **Generate a New Secret Key:** Create a new secret API key. It is crucial to copy this key immediately upon generation, as it is a secret key and will not be displayed again for security reasons.

### 2. Configuring the API Key in Open WebUI

* **Access Open WebUI Admin Panel:** Open the Open WebUI interface in a web browser and navigate to the Admin Panel.
* **Navigate to Connections Settings:** Within the Admin Panel, locate the "Settings" section and then select the "Connections" tab.
* **Add OpenAI API Key:** Find the section dedicated to OpenAI API integration and paste the copied secret API key into the designated field.
* **Save Configuration:** Save the changes to apply the API key configuration. This action allows Open WebUI to connect to the OpenAI API and utilize the ChatGPT models.