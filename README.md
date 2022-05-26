# Go4 Blockchain
[![Developed Using](https://img.shields.io/badge/made%20with-C%23-success.svg?)]( https://go.dev/)

Intro: Go4 has announced their plans to develop their own block chain. The team, who is best known for their work on a proof of work consensus algorithm, feels that this is the next step in their development. 3 nodes are currently running the Go4 block chain and more are planned to be added in the future. The company has stated that they plan to open source all of their code and invites other developers to participate in the project. They believe that this will help create a strong community around the project and further development of the block chain. Proof of Work consensus is currently being used but Go4 is also exploring other options including delegated proof of stake and voting based

## Key Information:
- **Proof of Work(PoW)** Go4 is based on  Proof of Work (PoW) consensus model.
- **Nodes** Currently Go4 is utilizing 3 nodes.
- **Programming Language** Go is used for development.

## Key Functions Commands & Usage.

### Create /Write New Transaction
"send" command is used to create new transactions. </br>

```bash
Usage of send:
  -amount int
        Amount to send
  -from string
        Source wallet address
  -to string
        Destination wallet address
```

Example: </br>
`go run main.go send -from "Ali" -to "Nicholas" -amount 1`

"getbalance" is used to get wallet balance of an address </br>
```bash
  -address string
        The address to get balance
```

Example: </br>
`go run main.go getbalance -address "Nicholas"`

### Create Wallet Wallet
### Retrieve a transaction
### View transaction status
### View transaction details
### View overall blockchain status
### View Current block
"printchain" commands is used to view current block </br>
`go run main.go printchain`
### List Current Nodes
