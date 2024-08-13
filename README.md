# Simple Go Web Server

This is a simple web server written in Go. The server handles static files, a form submission, and a hello endpoint.

## Getting Started

### Prerequisites

* Go (Golang) installed on your machine.

### Installation

1. Clone the repository or copy the code into a new directory.

```bash
git clone https://github.com/khushisinha20/go-mongodb-api
cd go-web-server
```

2. Create a static directory in the root of your project and add your static files (e.g., HTML, CSS, JavaScript) there.

### Running the Server

1. Open a terminal in the project directory.

2. Run the following command to start the server:

```bash
go run main.go
```
3. The server will start at http://localhost:8080.

## Endpoints

* **/**: Serves static files from the `./static` directory.
* **/hello**: Returns a "Hello!" message.
  * Method: GET
  * Returns: "Hello!"
* **/form**: Handles form submissions via POST requests.
  * Method: POST
  * Parameters:
    * name: The name of the person submitting the form.
    * address: The address of the person submitting the form.
  * Returns: A response with the submitted name and address.


