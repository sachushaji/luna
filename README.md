# luna
A Go Blockchain Implementation which helps beginners to easily grasp the fundamentals of blockchain.

### Prerequisites

- Should Have GoLang installed on your Pc
- Should Have Git Installed
- Should Have postman Installed


### How To Install

- Clone the repository to your local system
- Create a .env file and add a single line specifying the port at which you have to access your chain

```sh
ADDR=8080
```
### How to Run

- Execute the command from the root directory
```sh
go run main.go
```
- Go to your browser and run the below code to view the chain
```sh
localhost:8080
```
- Go to postman and execute a post request to port 8080 and in the raw-data section add the below code to append your data

```sh
{"DATA":'enter your string here'}
```
