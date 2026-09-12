# YouTube Copy

Projeto desenvolvido com o objetivo de praticar e consolidar conhecimentos de HTML e CSS, tendo como referência visual a página inicial do YouTube.

A proposta foi reproduzir a estrutura e alguns elementos visuais da interface, utilizando apenas HTML e CSS, sem a utilização de frameworks ou JavaScript.

> Este projeto possui finalidade exclusivamente educacional e foi desenvolvido para estudos de desenvolvimento front-end.

## Demonstração

Acesse o projeto publicado no GitHub Pages:

[Visualizar projeto](https://joabe-nogueira.github.io/youtube-homepage-clone)

## Objetivo

O principal objetivo deste projeto foi colocar em prática conceitos fundamentais de desenvolvimento web, principalmente:

* Estruturação de páginas com HTML;
* Uso de elementos semânticos;
* Organização de conteúdo com CSS;
* Flexbox;
* CSS Grid;
* Posicionamento de elementos;
* Responsividade;
* Media Queries;
* Utilização de imagens e ícones;
* Organização de arquivos e estilos;
* Criação de uma interface inspirada em uma aplicação real.

## Sobre o projeto

A página reproduz uma versão simplificada da home do YouTube, contendo elementos como:

* Barra superior de navegação;
* Logo do YouTube;
* Campo de pesquisa;
* Botão de pesquisa;
* Botão de pesquisa por voz;
* Botão "Criar";
* Notificações;
* Foto de perfil;
* Menu lateral;
* Atalhos para Início, Shorts, Inscrições e Você;
* Grid de vídeos;
* Miniaturas;
* Duração dos vídeos;
* Foto dos canais;
* Título dos vídeos;
* Nome dos canais;
* Quantidade de visualizações;
* Responsividade para diferentes tamanhos de tela.

## Tecnologias utilizadas

* HTML5
* CSS3
* Google Fonts — Roboto

O projeto não utiliza JavaScript, frameworks ou bibliotecas externas para a construção da interface.

## Estrutura do projeto

```text
Youtube-copy/
│
├── index.html
│
├── styles/
│   ├── header.css
│   ├── main.css
│   ├── nav.css
│   └── typography.css
│
└── imagens/
    ├── icons/
    │   ├── youtube-favicon.png
    │   ├── teclado-icon.png
    │   ├── pesquisa-icon.svg
    │   ├── microfone-icon.svg
    │   ├── mais-icon.svg
    │   ├── notificacao-icon.svg
    │   ├── icon_inicio.svg
    │   ├── icon_shorts.svg
    │   ├── icon_inscricoes.svg
    │   ├── icon_voce.svg
    │   ├── menu-icon.svg
    │   └── youtube_icon.svg
    │
    ├── thumbnails/
    │   ├── thumbnail01.webp
    │   ├── thumbnail02.webp
    │   ├── thumbnail03.webp
    │   ├── thumbnail04.webp
    │   ├── thumbnail05.webp
    │   └── thumbnail06.webp
    │
    └── perfil/
        ├── perfil-usuario.jpg
        ├── profile02.jpg
        ├── profile03.jpg
        ├── profile04.jpg
        ├── profile05.jpg
        └── profile06.jpg
```

## Responsividade

A interface foi adaptada para diferentes tamanhos de tela utilizando Media Queries.

O grid de vídeos se comporta de acordo com a largura disponível:

* Telas maiores: 3 vídeos por linha;
* Telas médias: 2 vídeos por linha;
* Telas menores: 1 vídeo por linha.

Em telas pequenas, alguns elementos da barra superior, como a pesquisa e o microfone, também são ocultados para melhorar a adaptação da interface.

## Conceitos praticados

Durante o desenvolvimento, foram praticados conceitos importantes de CSS, como:

* Flexbox;
* CSS Grid;
* Position;
* Media Queries.

## O que aprendi

Este projeto foi desenvolvido principalmente como uma forma de aprendizado e prática de HTML e CSS.

Ao reproduzir uma interface já existente, foi possível entender melhor como diferentes elementos de uma página real são organizados e como conceitos individuais de CSS podem ser combinados para construir uma interface completa.

Entre os principais aprendizados estão:

* Como estruturar uma página utilizando HTML;
* Como dividir estilos em diferentes arquivos CSS;
* Como utilizar Flexbox para alinhamento;
* Como utilizar Grid para criação de layouts;
* Como trabalhar com elementos `position: fixed` e `position: absolute`;
* Como criar layouts responsivos;
* Como utilizar Media Queries;
* Como organizar imagens, ícones e outros recursos;
* Como pensar na estrutura de uma interface antes de implementá-la.

## Observação

Este projeto é uma reprodução para fins de estudo, baseada na interface do YouTube. Não possui vínculo oficial com o YouTube ou com o Google.

O objetivo principal é demonstrar a evolução no aprendizado de HTML e CSS e a capacidade de transformar uma referência visual em uma interface funcional e responsiva.

---

Desenvolvido para fins de aprendizado em desenvolvimento Front-end.
