# Mundo Linux

Projeto da prova de HTML da disciplina de Desenvolvimento Front-end (UNIPÊ), feito apenas com HTML: sem CSS e sem JavaScript.

## Sobre

Site de 5 páginas sobre o Linux: origem, distribuições, mídia e um formulário de contato. Para visualizar, abra o `index.html` no navegador.

## Estrutura

```
.
├── index.html
├── html/
│   ├── sobre.html
│   ├── distros.html
│   ├── midia.html
│   └── contato.html
├── img/
│   ├── desktop.png
│   └── tux.png
├── audio/
│   └── musica.mp3
├── video/
└── README.md
```

A pasta `video/` existe pela organização pedida na atividade; o projeto usa apenas áudio (`audio/musica.mp3`, um som de disco rígido).

## Conteúdo por página

- **index.html**: introdução, `time`, `figure` e `figcaption`, `aside`
- **sobre.html**: `blockquote` e `cite`, `abbr`, `mark`, `del`, `ins`, `progress`, `meter`, `figure`, `details` e `summary`
- **distros.html**: tabela de 3 colunas e 3 linhas, com `colspan` na última linha, `details` e `summary`, `aside`
- **midia.html**: `audio` local com controles, `figure` e `figcaption`
- **contato.html**: formulário com `date`, `file`, `range`, `datalist`, `required` e `placeholder`

Todas as páginas usam `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`, com o mesmo menu de navegação.