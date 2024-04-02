# Go Server

A simple go server.

### Instructions to run locally

1. Configure GO in your system.
2. Download the dependencies using this command:
    ```bash
    go mod download
    ```
3. Set environment variable to the system for building the application:
    * `CGO_ENABLED=0`
    * `GOOS=linux`
4. Build the application:
    ```bash
    go build -o <your_desired_location>/go_server
    ```
5. Set environment variable for running:
    * `PORT=<your_desired_port>`
5. Run the built binary:
    ```bash
    <your_desired_location>/go_server
    ```

### Check if the server is running
1. Go to `http://localhost:<given_port>` and check if you see "`Hello, from Ostad! <3`".
2. Go to `http://localhost:<given_port>/health` and check if you see "`{"Status": "OK"}`".
