# Stad API

Welcome to the **Stad API**! This API is developed by the Dutch Verification App OS Authority in collaboration with the local authority. With the Stad API, you can easily access valuable information about cities and towns in the Netherlands.

## What is Stad API?

The Stad API allows developers to retrieve data about various cities and towns, such as the number of traffic lights, buildings, and other relevant information.

## Features

With the Stad API, you can query the following data:

- **Number of traffic lights** in a specific city or town.
- **Number of buildings** and their characteristics.
- **General information** about the city or town.
- **Statistics** and other useful data related to the area.

## API Endpoints

Here’s an overview of the available endpoints:

| Endpoint                             | Description                              |
|--------------------------------------|------------------------------------------|
| `/api/steden`                       | List of all cities and towns             |
| `/api/stad/{name}`                 | Data of a specific city or town          |
| `/api/stad/{name}/stoplichten`      | Number of traffic lights in the city or town |
| `/api/stad/{name}/gebouwen`       | Information about buildings in the city or town |

## Example Usage

### 1. List of cities and towns

```http
GET /api/steden
