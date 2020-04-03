# Django-Serverless
Django, Docker and Serverless on Lambda.

## Requirements
To work with this repo you should have preinstalled:
* Docker Desktop
* Serverless Framework
* Node Package Manager

## Setup
Change `service`, `app` and `org` values in:
```
nano serverless.yml
```

Fill in secrets
```
cp .env.sample .env && nano .env
```

Install deployment deps
```
npm i
```

## Usage

For local development
```
docker-compose up -d
```

For remote deployment
```
serverless deploy
```
