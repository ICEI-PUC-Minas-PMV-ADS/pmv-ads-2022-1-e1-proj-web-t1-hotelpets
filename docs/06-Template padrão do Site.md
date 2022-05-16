# Template padrão do site

O padrão de layout a ser utilizado pelo site tem correspondência ao projeto de Interface elaborado anteriormente. Devendo observar as especificidades abaixo:

### Padrão entre: Página Inicial, Resultado de Hospedagens e Hospedagem Específica. 

> Menu de Navegação:

HTML:
```
<body>
  <header class="cabecalho">
    <img src="./img/logo.png" />
    <nav class="cabecalho-menu">
      <a class="cabecalho-menu-item" href="#">Início</a>
      <a class="cabecalho-menu-item" href="#">Como Funciona</a>
    </nav>
    <nav class="cabecalhodois">
      <a class="cabecalho-login-item" href="#">Cadastre-se</a>
      <a class="cabecalho-login-item" href="#"><img src="./img/login.png" /></a>
    </nav>
 </header>
</body>
```

CSS:

```

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100&family=Roboto:wght@100;400&display=swap%27);

 
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
}

body {
  font-size: 100%;
  background: #fff

}

.cabecalho {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  padding: 24px;

}

.cabecalho-imagem {
  height: 72px;
}

.cabecalho-menu {
  display: flex;
  gap: 15px;

}

.cabecalhodois {
  display: flex;
  align-items: center;
  gap: 20px;

}

.cabecalho-menu-item {
  font-family:'Roboto', sans-serif;
  color: #3F3E41;
  font-weight: 400;
  font-size: 13px;

}

.cabecalho-login-item {
  font-family: 'Roboto', sans-serif;
  color: #3F3E41;
  font-weight: 400;
  font-size: 13px;
} 
```

> Footer:





### Padrão entre: Login, Cadastro e Pagamento

em desenvolvimento
