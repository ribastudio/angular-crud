
# Angular CRUD

Criação de um CRUD consumindo uma API externa e manipulando os dados, como forma de testar a tecnologia Angular v19


## Instalação

após baixar o projeto 
```bash
cd [pasta]
```

Instale o projeto:
```bash
npm i
```

Para rodar o projeto em desenvolvimento:
```bash
npm run start
```

Para rodar os testes:
```bash
npm run test
```
## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Deploy

Para fazer o deploy desse projeto rode

```bash
  npm run deploy
```


## Demonstração

Insira um gif ou um link de alguma demonstração


## Autores

- [@ribastudio](https://www.github.com/ribastudio)

