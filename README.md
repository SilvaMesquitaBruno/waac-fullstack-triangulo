# Teste de Lógica - WAAC 

*Aprender é a única coisa de que a mente nunca se cansa, nunca tem medo e nunca se arrepende.*

## Links com os códigos
[backend](https://github.com/SilvaMesquitaBruno/waac-backend-triangulos)
[frontend](https://github.com/SilvaMesquitaBruno/waac-frontend-triangulos)

## Desafio dos Triângulos

Dado um triângulo de números, encontre o total máximo de cima para baixo.

## O Triângulo

                6
            3       5
        9       7       1
    4       6       8       4    

    Nesse triângulo, o total máximo é 6 + 5 + 7 + 8 = 26.
 
## Estratégia

- Estratégia inicial: Usar conceitos de arvore binaria e busca binaria para resolver o desafio.

- Estratégia atual: Não foi preciso o uso de estrutura de dados mais complexas para resolução do desafio, uma simples varredura na matriz com duas condições. O tempo de execução do algoritmo foi agradável, **2.400ms**, tendo um aumentou consideravelmente quando foi preciso extrair os números selecionados.

### Arquitetura

- **MVC**, Model View e Controller.
Sendo o backend contendo o Model e o Controller, e o frontend contento somente a View.


### Linguagem

- **Javascript**
Linguagem que atende melhor quando o requisito é fullstack, contém uma gama de libs que atendem tanto o frontend quanto o backend mantendo uma boa performance e produtividade, sem necessidade de saber e aprender mais de uma linguagem, como uma linguagem para o backend e outra linguagem para o frontend.

### Ferramentas

- [NodeJs](https://nodejs.org/en/), plataforma javascript.
- [Insomnia](https://insomnia.rest/), programa para debug de APIs.
- [MongoDB Compass](https://www.mongodb.com/products/compass), Visualizão de registros para MongoDB
- [Docker](https://www.docker.com/), Criação de BDs em ambientes isolados.

#### Backend

- **Express**, para a criação da API.
- **Mongoose**, para o banco não relacional.
- **Yup**, para validações. 
- **Eslint**, **Prettier**, para estilização do codigo para melhor entendimento(Padrão Airbnb).
- **Jest**, framework para testes.

#### Frontend
    
- **ReactJs**, criação de interfaces com js.
- **Axios**, lib para conexão com a API.
- **Eslint**, **Prettier**, para estilização do codigo para melhor entendimento(Padrão Airbnb).

### Problemas Encontrados

Criação da matriz a partir de inputs do usuario.

#### Minhas Limitações Atuais

- Mostrar o triângulo de forma tracejada com o caminho percorrido.
- inputs Dinâmicos, adicionar mais linhas na matriz e remover.

