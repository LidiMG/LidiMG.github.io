# lidimg.github.io

Portfólio de **Lidiane M. Gomes** — bibliotecária há 16 anos em transição para Engenharia, Governança e Qualidade de Dados.

🔗 **No ar:** https://lidimg.github.io

> Este site foi **construído com auxílio da Claude AI (Anthropic)**, a partir
> das orientações, decisões e revisão de Lidiane Gomes — que definiu o
> conteúdo, a narrativa e quais projetos destacar; a escrita do código e a
> maior parte das soluções visuais foram trabalho do Claude.

## O conceito

Cada projeto é apresentado como uma **ficha catalográfica**: número de chamada
(classificação decimal), descrição e, no rodapé, os "assuntos" — que aqui são
as tecnologias usadas. É o jeito de mostrar, sem precisar explicar, de onde vem
o olhar de governança de dados.

## Estrutura

```
LidiMG.github.io/
├── index.html      # Todo o conteúdo, em português e inglês
├── style.css       # Visual (fichário de biblioteca)
└── assets/         # Capturas de tela dos projetos
```

Sem framework e sem etapa de build: o GitHub Pages publica os arquivos como estão.

## Como editar

- **Textos:** cada trecho existe duas vezes, lado a lado — `lang="pt"` e `lang="en"`.
  Ao mudar um, mude o outro. O botão PT/EN no topo alterna entre eles.
- **Novo projeto:** copie um bloco `<article class="project">…</article>` inteiro
  e troque o conteúdo.
- **Capturas de tela:** salve em `assets/` com o nome já usado no HTML
  (`eventos-medievais.png`, `aco-e-folha.png`). Se o arquivo não existir,
  o espaço simplesmente não aparece.
- **Pendências** estão marcadas no HTML com `TODO`.

## Publicação

1. Crie um repositório público chamado exatamente `LidiMG.github.io`.
2. Suba estes arquivos na branch `main`.
3. Em *Settings → Pages*, confirme a origem `Deploy from a branch` → `main` / `(root)`.
4. Em um ou dois minutos, o site fica disponível em https://lidimg.github.io.
