@import url('https://fonts.googleapis.com/css?family=Chakra+Petch:wght@400;700&display=swap');

:root {
  --cor-de-fundo: #161618;
  --verde: #6FFF57;
  --branco: #FFFFFF;
  --botao-ativo: #3A375E;
  --botao-inativo: rgba(58, 55, 94, 0.5);
  --texto-fundo: rgba(58, 55, 94, 0.3);
}

body {
  background-color: var(--cor-de-fundo);
  color: var(--branco);
  font-family: 'Chakra Petch', sans-serif;
}


.conteudo-principal {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    max-width: 1200px;
    width: 100%;
    margin: 0 auto;
}

.titulo-principal {
    text-align: left;
    width: 100%;
    font-size: 32px;
}

.titulo-principal span {
    color: var(--verde);
}


.botao {
    font-family: "Crakra Petch", sans-serif;
    background-color: var(--botao-inativo);
    color: var(--branco);
    display: flex;
    justify-content: center;
    padding: 1em;
    font-size: 18px;
    align-items: center;
    width: 100%;
    border-bottom: 4px solid var(--botao-ativo);
    border-left: 2px solid var(--botao-ativo);
    border-right: 2px solid var(--botao-ativo);
    border-top: none;
}

.botao:first-child {
    border-radius: 40px 40px 0 0;
}

.botoes {
    display: block;
}

.ativo{
    background-color: var(--botao-ativo);
    border-bottom: 4px solid var(--verde);
}
    
@media screen and (min-width: 768px) {@import url('https://fonts.googleapis.com/css?family=Chakra+Petch:wght@400;700&display=swap');

    :root {
      --cor-de-fundo: #161618;
      --verde: #6FFF57;
      --branco: #FFFFFF;
      --botao-ativo: #3A375E;
      --botao-inativo: rgba(58, 55, 94, 0.5);
      --texto-fundo: rgba(58, 55, 94, 0.3);
    }
    …    display: block;
    .botoes {
        display: flex;
    }
    .botao:first-child {
        border-radius: 40px 0 0 0;
    }
    .botao:last-child {
        border-radius: 0 40px 0 0;
    }
}
