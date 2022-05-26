# Blockchain with Golang

<p>
Contains a simple blockchain implementation using the Go language.<br>
Persistence implementation is achieved using Badger KV<br>
It automatically creates the <i>Genesis</i> block if it does not exist
</p>

## Commands
### Print blockchain with its data and hash <br>
`go run main.go print`
<br>

### Add New Block with data<br>
`go run main.go add 'My block data'`

###