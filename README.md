# FastAPI Docker Simulation on Google Colab

Este repositório contém um script para configurar um ambiente no Google Colab, simular contêineres Docker utilizando `udocker`, e criar uma API simples com FastAPI. A API é exposta publicamente usando o `ngrok`, permitindo o acesso remoto.

## Funcionalidade

- **Simulação de Docker com `udocker`**: Instala e configura o `udocker` para rodar contêineres sem privilégios de root.
- **Criação de API FastAPI**: Instala as dependências necessárias e cria uma API simples com um endpoint que retorna "hello world".
- **Exposição pública com `ngrok`**: Usa o `ngrok` para gerar uma URL pública e expor a API localmente.

## Como Usar

1. Clone o repositório ou faça o upload do script no seu ambiente do Google Colab.
2. Execute o código para configurar o ambiente e rodar a API.
3. O script irá gerar uma URL pública através do `ngrok`, permitindo que você acesse a API remotamente.

## Dependências

- `udocker`
- `FastAPI`
- `Uvicorn`
- `ngrok`
- `nest_asyncio`

## Exemplo de Uso

Após executar o código, você verá a URL pública do `ngrok`, onde poderá acessar a API:


Acesse a API em: `http://<URL gerada pelo ngrok>/`

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
