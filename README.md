# Teste de Conhecimento PHP

Para esse teste, você deverá desenvolver uma aplicação web bem simples. Um cadastro de Produtos e Categorias.

Serão dois CRUDs, um para **Produtos** e outro para **Categorias**.

Segue os campos necessários para cada entidade:
- Entidades
    - Categoria
        - id
        - nome
    - Produto
        - id
        - nome
        - quantidade
- Cada produto pode pertencer a várias categorias.
- Para cada entidade, deverá ser criado uma tela de listagem, inclusão, alteração e exclusão.
- Na tela de listagem de **Produtos** deverá ter dois botões, por registro, que vão adicionar ou remover 1 da quantidade do produto.

## Regras de Arquitetura

- Utilizar PHP 7.0 ou superior
- Não utilizar nenhum framework
- Utilizar a classe **PDO** para fazer a comunicação com o Banco de Dados
- Permitido o uso de bibliotecas externas
- Seguir os princípios **SOLID**
- Criar um arquivo `README.MD` com as instruções detalhadas de como rodar a aplicação.
- O Frontend da aplicação pode ser feita com bootstrap ou qualquer outra tecnologia de Front na qual, você se sinta mais à vontade

## Entrega do Projeto

O projeto deve estar em um repositório público no github / bitbucket para ser clonado por nós e avaliado.

## Diferenciais

- Criar um sistema de Logs da aplicação
- Criar testes automatizados da aplicação
- Seja criativo!
