# node-red-brasilapi
Node-RED que consome dados brasilAPI

## Requisitos
- Node.js
- Node-RED

## Como rodar
1. Instale o Node-RED: `npm install -g node-red`
2. Inicie o Node-RED: `node-red`
3. Importe os fluxos:
   - Clique no menu -> Import -> Clipboard -> Cole o conteúdo do JSON
4. Acesse:
   - Catálogo de Corretores: `http://localhost:1880/corretoras`
   - Pesquisador de CEP: `http://localhost:1880/cep`

## Observações
- A pesquisa de CEP é possível utilizar de duas formas:
1. Através da URL. Exemplo: `http://localhost:1880/cep?codigocep=89010025`
2. Através de uma barra de pesquisa, que irá aparecer ao digitar `http://localhost:1880/cep`