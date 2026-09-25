# Floral Garden 🌷

Site simples em HTML sobre uma loja/jardim fictício de flores, desenvolvido como atividade avaliativa. O projeto explora tags semânticas do HTML5, como `section`, `article`, `figure`, `fieldset`, `table`, `audio` e `iframe`.

## 📁 Estrutura do projeto

```
Prova/
├── README.md
├── html/
│   ├── home.html
│   ├── flores.html
│   └── formulario.html
├── img/
├── audio/
└── video/
```

## 🖥️ Páginas

### `home.html`
Página inicial do site. Contém um cabeçalho com imagem do jardim, menu de navegação (presente em todas as páginas), uma breve apresentação do site e uma lista recolhível (`<details>`) mostrando as 3 flores em destaque: Rosa, Orquídea e Lírio.

### `flores.html`
Página com o catálogo de flores:
- Lista das flores com imagem e legenda (`<figure>`/`<figcaption>`), incluindo o nome científico de cada uma.
- Tabela (`<table>`) com um guia de cuidados (necessidade de luz, rega e tipo de solo) para cada planta.
- Um vídeo de orientação incorporado via `<iframe>` do YouTube.
- Uma citação (`<blockquote>`) resumindo o conteúdo do vídeo.

### `formulario.html`
Página "Sobre nós" e contato:
- Texto de apresentação da empresa, acompanhado de um áudio (`<audio>`) e uma imagem do jardim de rosas.
- Formulário de contato com campos de nome, e-mail e mensagem, todos com `label` associado corretamente via `for`/`id` e marcados como `required`.
- Os campos do formulário estão agrupados dentro de um `<fieldset>` com `<legend>`, e o envio é feito por um `<button type="submit">`.
- Data da prova marcada com `<time>` e uma citação final sobre HTML.

## 🔗 Navegação
As três páginas compartilham o mesmo cabeçalho e menu (Home, Flores, Formulário), permitindo circular entre elas.

## 📦 Outras pastas
- **img/** — todas as imagens usadas nas páginas (jardim, rosa, orquídea, lírio, etc.).
- **audio/** — arquivo de áudio (`Flores.ogg`) usado em `formulario.html`.
- **video/** — pasta vazia, já que o vídeo exibido é um iframe do YouTube, e não um arquivo local.
