# Controle de filas

O queue-control foi desenvolvido com o intuito de auxiliar no controle de filas de estabelecimentos para não causar aglomeração.
O sistema utiliza websocket para tornar o sistema real-time.

## Como executar ?

Para usar é bem simples, basta pegar o compilado para o seu sistema operacional e executar em um "server".
Depois de executado, basta abrir o browser e acessar a servidor.

O sistema foi desenvilvido em golang, com interface em html e javascript. Para executar, basta ter o golang instalado.

    $ go mod download
    $ go run *.go

No endereço http://localhost:8080 vai ter a interface com o numero da mesa que esta chamando o próximo cliente da fila.
No endereço http://localhost:8080/call vai ter a interface para o atendente chamar o cliente.
