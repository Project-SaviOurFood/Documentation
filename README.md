
# 🥝 SaviOurFood
## Redução das Desigualdades
### Objetivos de Desenvolvimento Sustentável no Brasil

Um E-commerce, onde são comercializados produtos a baixo custo e também proximos da validade, visando reduzir a Desigualdade Alimentícia no Brasil.

## ⚙️ Funcionalidades

✅ Fazer Login / Cadastro;

✅ Editar, Deletar e Cadastrar um Produto;

✅ Editar, Deletar e Cadastrar Categoria;

✅ Adicionar ao Carrinho;

✅ Finalizar Compra.

## :hammer_and_wrench: Ferramentas 
### 🍮 BackEnd
- DOCKER;
- MySQL com Sequelize;
- NodeJS com Express;
- JWT;
- MD5;
- Testes (Sinon, Chai, Mocha);

### 🍮 FrontEnd
- React;
- Context API;
- Jest
- Axios

# Orientações

- *Clonar o repositório:*

```
$ git clone git@github.com:Brayan-23/Delivery-App.git
```

- *Acessar o projeto appdelivery:*

```
$ cd Delivery-App
```

- *Instalar as dependências tanto do Front-end, como Back-end*

> Acesse as pastas back-end e front-end e instale as dependencias: `npm install`


<details>
  <summary><strong>🐋 Rodando o MySQL com Docker vs Localmente</strong></summary><br />
  
  ## Com Docker


  - Dentro da pasta back-end, rode o `docker-compose` com o comando:
   ```
  $ docker-compose up -d
  ```
  - Esse serviço irá inicializar um container chamado `back_app_delivery` com a imagem do <strong>MySQL</strong>.

  - *Com o container em funcionamento, execute o comando para popular o Banco de Dados:*
  
  ```
  $ npm run db:reset
  ```
  
  - *Por fim, execute em sua respectivas pastas o comando abaixo, para colocar no ar tanto Back-end, quanto Front-end*
   
   ```
   $ npm start
   ```
---
  
  ## Sem Docker
 
  - *Execute o comando para popular o Banco de Dados:*
  
  ```
  $ npm run db:reset
  ```
  - *Execute em sua respectivas pastas o comando abaixo, para colocar no ar tanto Back-end, quanto Front-end*
  
   ```
   $ npm start
   ```
   
   ⚠ Atenção ⚠: Caso opte por utilizar localmente, necessarimente você precisa ter o <strong>MySQL</strong> instalado e funcionando.. 
   
  <br/>
</details>

- *Poderá encontrar a aplicação* [LINK](http://localhost:3000/)
- *Utilizar um login válido:*
```
        Customer              Administrador         Vendedora
email: zebirita@email.com ou adm@deliveryapp.com ou fulana@deliveryapp.com
senha: $#zebirita#$ ou --adm2@21!!-- ou fulana@123
```
## 👨‍💻 Desenvolvedores
- Brayan Santos
  [Linkedin](https://www.linkedin.com/in/braka/)
  [GitHub](https://github.com/Brayan-23)
- Anderson Santos
  [Linkedin](https://www.linkedin.com/in/anderson-santos-s-silva/)
  [GitHub](https://github.com/AndersonSantos07)
- Ygor Araújo
  [Linkedin](https://www.linkedin.com/in/ygor-araújo-052824242/)
  [GitHub](https://github.com/Ygorgen?tab=repositories)
- Edevando Alves
  [Linkedin](https://www.linkedin.com/in/edevando-alves/)
  [GitHub](https://github.com/EdEddAEddy)
- Tainara Victória
  [Linkedin](https://www.linkedin.com/in/tainara-santos-58a3201bb)
  [GitHub](https://github.com/tainaravctr)
- Thamires Ribeiro
  [Linkedin](https://www.linkedin.com/in/thamires-ribeiro-cruz/)
  [GitHub](https://github.com/ThamiresRC)
