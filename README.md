# Calculadora API

Esta é uma API simples para realizar operações matemáticas básicas (soma, subtração, multiplicação e divisão) utilizando Node.js e Express.

## Tecnologias Usadas

- **Node.js**: Ambiente de execução JavaScript do lado do servidor.
- **Express**: Framework web para Node.js que facilita a criação de APIs.
- **Body-parser**: Middleware para analisar o corpo das requisições em JSON.

## Configuração do Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/seurepositorio.git
   cd seurepositorio
2. **Instale as dependências**
   ```bash
   npm install
3. **Inicie o servidor**
   ```bash
   node app.js
O servidor estará rodando em `http://localhost:3001`.

## Rotas da API

### 1. Rota Principal
- **GET** `/`
  - Resposta: `"Está funcionando"`

### 2. Soma
- **POST** `/soma`
  - **Corpo da Requisição**:
    ```json
    {
      "a": número,
      "b": número
    }
    ```
  - **Resposta**: 
    ```
    O resultado da soma de {a} e {b} é {resultado}
    ```

### 3. Subtração
- **POST** `/subtrai`
  - **Corpo da Requisição**:
    ```json
    {
      "a": número,
      "b": número
    }
    ```
  - **Resposta**: 
    ```
    O resultado da subtração de {a} e {b} é {resultado}
    ```

### 4. Multiplicação
- **POST** `/multiplica`
  - **Corpo da Requisição**:
    ```json
    {
      "a": número,
      "b": número
    }
    ```
  - **Resposta**: 
    ```
    O resultado da multiplicação de {a} e {b} é {resultado}
    ```

### 5. Divisão
- **POST** `/divide`
  - **Corpo da Requisição**:
    ```json
    {
      "a": número,
      "b": número
    }
    ```
  - **Resposta**: 
    ```
    O resultado da divisão de {a} por {b} é {resultado}
    ```
    - Se `b` for 0:
      ```
      Erro: Divisão por zero!
      ```

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades!

