# Full Cycle - Desafio Nginx com Node.js e MySql

## 🐋 Módulo Docker
### Instruções

Nesse desafio você colocará em prática o que aprendemos em relação a utilização do `nginx` como **proxy reverso**. A idéia principal é que quando um usuário acesse o `nginx`, o mesmo fará uma chamada em nossa aplicação `node.js`. Essa aplicação por sua vez adicionará um registro em nosso banco de dados `mysql`, cadastrando um nome na tabela people.

O retorno da aplicação `node.js` para o `nginx` deverá ser:

```html
<h1>Full Cycle Rocks!</h1>
```

- Lista de nomes cadastrada no banco de dados.

Gere o `docker-compose` de uma forma que basta apenas rodarmos: `docker-compose up -d` que tudo deverá estar funcionando e disponível na `porta: 8080`.

Não esqueça de colocar o `volume` na aplicação para o ambiente de desenvolvimento. 

Suba tudo em um repositório e faça a entrega.

* A linguagem de programação para este desafio é `Node/JavaScript`.

### Para executar a aplicação

Execute o comando `docker-compose` para subir os containers.

```bash
docker-compose up -d
```

Em alguns instantes a aplicação estará no ar.
 
### Para acessar a aplicação

No navegador (*browser*) digite o endereço:
[http://localhost:8080/](http://localhost:8080/)

**OBS:** Caso no navegador apresente a mensagem **Erro 502**, aguardar alguns segundos e atualizar a página.

Todas as vezes que você a página for atualizada, um novo nome será adicionado ao banco de dados.

***

## Tecnologias e ferramentas

- **[Docker](https://www.docker.com/)**
- **[Docker Hub](https://hub.docker.com/)**
- **[MySQL](https://www.mysql.com/)**
- **[Nginx](https://www.nginx.com/)** 
- **[Node.js](https://nodejs.org/en/)**
- **[Visual Studio Code](https://code.visualstudio.com/)**






