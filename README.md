# Travelgram

Página estática de um perfil de viagens, feita com HTML e CSS.

## Como abrir

Abra `index.html` no navegador. Não é necessário instalar dependências.
Também é possível usar a extensão Live Server do editor.

## Estrutura

Organização baseada no projeto formulario-de-convite:

```text
travelgram/
├── index.html
├── README.md
├── assets/
│   ├── icons/       # Logo e ícones SVG
│   └── images/      # Foto de perfil e fotos de viagens
└── styles/
    ├── index.css   # Importação dos estilos
    ├── global.css
    ├── nav.css
    ├── header.css
    ├── main.css
    └── footer.css
```

Os caminhos no HTML apontam para `assets/` e `styles/`. Os estilos de cada seção são importados por `styles/index.css`.

O nome, a biografia e a localização são conteúdo demonstrativo e podem ser alterados no HTML. O contador corresponde às 12 fotos da galeria. Os links de navegação levam ao perfil e às fotos na própria página.

A fonte Poppins é carregada do Google Fonts quando há conexão; sem internet, a página usa Arial. As imagens e o restante da página funcionam localmente.
