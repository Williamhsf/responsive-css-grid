# Estudando sobre conceitos responsivos em css grid com Angela Design
https://www.youtube.com/watch?v=68O6eOGAGqA

- Antes de começar devemos desenhar nosso layout no papel e após a definição, formar a estrutura no Figma ou Sketch, buscando entender antes de qualquer coisa o layout, usei o <a href="https://www.figma.com/file/1eIgopd7ma6rJ4zuogfLFQ/css-grid?type=design&t=OglidgVsNPZ3HCmg-6">Figma</a>;

- O estudo sera feito em mobile e desktop;

### HTML
Necessário definir como sera o container, já que ele sera usado para conter os elementos, foi decidido que seu body ficara desse jeito, que são os elementos principais da página:

  div container <br>
    nav - Navbar  <br>
    main - Main  <br>
    div id-sidebar - Sidebar <br> 
    div id-content1 - Content1  <br>
    div id-content2 - Content2  <br>
    div id-content3 - Content3  <br>
    footer - Footer 
     
### CSS
No CSS vamos chamar o container que pode ter varias propriedades a serem definidas, seguindo o que esta no layout:

  display: grid; ( TIPO ) <br>
  height: 100vh; ( ALTURA ) <br>
  grid-template-columns: 1fr 1fr 1fr 1fr; ( MEDIDAS PARA CADA COLUNA ) <br>
  grid-template-rows: 0.2fr 1.5fr 1.2fr 0.8fr; ( MEDIDAS PARA CADA LINHA ) <br>
  grid-template-areas:  ( PRECISAMOS ROTULAR CADA AREA A SER PREENCHIDA) <br>
    "nav nav nav nav"<br>
    "sidebar main main main"<br>
    "sidebar content1 content2 content3"<br>
    "sidebar footer footer footer";<br>
  grid-gap: 0.2rem; (ESPACAMENTO ENTRE OS ELEMENTOS) 

### Responsive
Supondo que o tamanho mobile seja de 550px no máximo, vamos começar definindo para uma coluna 1fr

  grid-template-columns: 1fr;<br>
  grid-template-rows: 0.4fr 0.4fr 2.2fr 1.2fr 1.2fr 1.2fr 1fr; (brincar ate chegar proximo do projeto)<br>
  grid-template-areas: ( PRECISAMOS ROTULAR CADA AREA A SER PREENCHIDA)  <br>
  "nav"<br>
  "sidebar"<br>
  "main"<br>
  "content1"<br>
  "content2"<br>
  "content3"<br>
  "footer";

## Medias 
- Dribbble: <a href="dribbble.com/angeladelise">dribbble.com/angeladelise</a>
- Medium: <a href="medium.com/@angeladelise">medium.com/@angeladelise</a>

