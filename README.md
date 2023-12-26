# Parking Control API

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

This project is an API built using **Java, Java Spring.**

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/MarcelFeo/parking-control-api.git
```

2. Install dependencies with Maven

## Usage

1. Start the application with Maven
2. The API will be accessible at http://localhost:8081


## API Endpoints
The API provides the following endpoints:

```markdown
GET /parking-spot - Retrieve a list of all spots.

GET /parking-spot/{id} - Retrieve a specific spot

POST /parking-spot - Register a new spot.

DELETE /parking-spot/{id} - Delete a spot

PUT /parking-spot/{id} - Update a spot

```



