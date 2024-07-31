# Paginas estaticas

 Esse repositório contém meus projetos de estudos em HMTL e CSS sem o uso de JavaScript. Cada pasta inicia com "Pagina-" simbolizando um projeto diferente contendo imagens, vídeos além do uso das propriedades da linguagem de estilos como display e responsividade. O intuito é usar de quase todas as funções diferentes da linguagem nas ideias acima. 🚀🌟
 

 ## Versão com cards em destaque 

 No repositório publicado a aba de sabroes das pizzas possui o mesmo background-color que o body. A ideia aqui é desenvolver cards que destaquem essa parte do site.

 Atualmente o estilo segue dessa forma:


 
```/* Section */

h2{
    margin-top: 5px;
    margin-bottom: 20px;
   font-size: 54px;
   color: #ea8d31;
    text-align: center;
    text-shadow: 2px 1px 2px rgba(0, 0, 0, 0.349);
}

.cardapio ul{
    display: flex;
    width: 90%;
    justify-content: space-between;
    margin: 0 auto;
}

.cardapio li{
    flex: 1 1 300px;
    padding: 2rem;
    border: 1px solid grey;
    margin: 6px 5px;
    list-style: none;
    border-radius: 7px;
}
```