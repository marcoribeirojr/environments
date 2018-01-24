## Ambiente de desenvolvimento para Bot Framework

### Configurações iniciais

Este ambiente de desenvolvimento é baseado na imagem node, portanto é necessário na raiz do projeto a criação
de um arquivo ```package.json``` com um script de start configurado.

Exemplo:

`
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "start": "node server.js"
},
`

Onde ```server.js``` seria um possível arquivo de configuração do servidor NodeJS.

### Instalação Básica

```docker-compose up -d```

### Observações

- Portas
O arquivo leva em consideração um servidor rodando na porta 3000 e a API de bots configurada para a porta 3978.
