
## Description

Sample Nestjs GraphQL API Setup.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev
```
## Docker 

#### Build Image
```
docker build . -t starter-api
```

#### Run as Container
```
docker run -p <port>:<port> -d --name starter-api starter-api
```