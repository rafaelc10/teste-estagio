# Teste para vaga de Estagiário Dev Web

## Questões Teóricas

1. Qual a função do "head" no HTML?<br>
R: No HTML, o head será onde ficará informações que não são visiveis diretamente ao usuario do site. São informações como: titulo do site, vinculação com outros arquivos, metadados e etc.

2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?<br>
R: Não, Porque se não, não seria necessário utilizar os recursos para deixar o site responsivo. Por exemplo a tag "<meta name="viewport" content="width=device-width, initial-scale=1.0">" serve para que o site se enquadre proporcionalmente nas telas celulares, e o media query no css que serve para manipular os elementos para que se adaptem aos diferentes tipos de tela.

3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?<br>
R: Não, o HTML e CSS é mandado do servidor e renderizado no browser. Também é possivel utilizar SSR (Server Side Rendering) onde os Javascripts e CSS são renderizados no servidor, reduzindo o tempo de carregamento do site.

4. Qual a função das tags H (h1, h2, h3, etc) no HTML?<br>
R: A função das tags H é criar títulos e sub-titulos.

5. O que é SEO e como funciona?<br>
R: SEO é uma otimização para os Mecanismos de Busca, para melhorar o posicionamento do site nos buscadores como Google, Bing etc. Utilizar HTML semântico, Meta tags, nomes de arquivos são fatores que influênciam os motores de busca a achar o seu site mais facilmente.

6. O uso de media query é obrigatório em todas as páginas?<br>
R: O media query não é obrigatório, porém se for fazer um site adaptavel para todos os tamanhos de tela é um requisito.

7. Qual a diferença entre CSS Inline e CSS em um arquivo?<br>
R: O CSS Inline permite que o CSS seja escrito no próprio codigo HTML, mais especificamente na linha do elemento utilizando a tag "Style".
O CSS em um arquivo é o CSS em um arquivo separado do HTML sendo necessário vinculá-lo ao código com a tag <link>

8. Como criar animações no CSS? Dê um exemplo.<br>
R: Para criar uma animação é necessário primeiramente criar um keyframe no CSS, o nome da animação e o que a animação fará.
Por exemplo: @keyframes animacao{0% {background-color: blue;} 50%{background-color: green;} 100%{background-color:red;} }
Com isso a animação estará criada, neste exemplo a animação mudará a cor de fundo do elemento.
Para utilizá-la é só adicionar a propriedade "animation-name: animacao;" e o tempo que a animação irá durar com "animation-duration:5s" no elemento desejado.
Existem outras propriedades também, para definir como delay para a animação começar, se a animação será infinita e etc.

9. Qual a diferença entre class e ID no CSS?<br>
R: A diferença entre a class e o ID é que o ID só pode ser usado uma vez no elemento, por exemplo se eu atribuir um ID "teste" para algum elemento apenas este elemento poderá ter esse ID. Já a class pode ser usada em vários elementos diferentes.
No CSS para selecionar um ID usa-se #nome-do-id e a classe usa-se .nome-da-classe.


10. Quais os diferentes tipos de seletores CSS?<br>
R: Os principais tipos de seletores são: Seletor de Elemento Vazio, Seletor Negativo, Seletor NTH e Seletor Before/After.
O Seletor de Elemento Vazio seleciona o elemento que não tem conteúdo.
O Seletor Negativo deixa de selecionar o elemento que eu especificar.
O Seletor NTH seleciona determinado elemento dentro de uma lista, especificando sua posição.
Os Seletores Before/After serve para criar um novo elemento antes (before) ou after (depois) do elemento que eu selecionar.

## Projeto prático
### Projeto disponível no repositório
O candidato deve criar a página da imagem a seguir:
![Layout](https://i.ibb.co/Bydq2FZ/screencapture-spotify-br-2022-05-10-15-13-17.png)

