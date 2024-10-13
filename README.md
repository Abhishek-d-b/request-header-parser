# Request Header Parser App

This is a simple **Request Header Parser App** built with Node.js and Express. The service provides information about the user's IP address, language, and software (user-agent) based on the request headers.

## Project Purpose

This project is part of the [FreeCodeCamp Back End Development and APIs](https://www.freecodecamp.org/learn/back-end-development-and-apis/) curriculum. It demonstrates how to extract header information from HTTP requests.

## Features

- Returns the client's IP address.
- Parses the `Accept-Language` header to retrieve the user's language preferences.
- Retrieves the `User-Agent` from the request to determine the user's software information (browser and operating system).
- Responds with a JSON object containing the above information.

## API Endpoints

- **`/api/whoami`**
  - Example Response:
    ```json
    {
      "ipaddress": "192.168.1.1",
      "language": "en-US,en;q=0.9",
      "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"
    }
    ```

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (v12.x or higher)
- [npm](https://www.npmjs.com/) (comes bundled with Node.js)

### Installation

1. Clone the repository from GitHub:

   ```bash
   git clone https://github.com/Abhishek-d-b/request-header-parser
   ```
