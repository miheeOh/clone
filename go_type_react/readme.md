# to-do app
## initialize go app
go mod init github/com/tomdoestech/go-react-todo
## install fiber v2
go get -u github.com/gofiber/fiber/v2
## create client app with vite
yarn create vite client -- -- template react-ts
## install dependencies
yarn add @mantine/hooks @mantine/core swr @primer/octicons-react

server -> go run main.go
client -> yarn dev