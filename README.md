<h1 align="center">Grifo</h1>

<div align="center">
  <strong>Editor de Markdown que formata enquanto você escreve.</strong><br>
  WYSIWYG, open source e focado em uma escrita sem distrações.<br>
  <sub>Linux, macOS e Windows.</sub>
</div>

<br>

<div align="center">
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/gabrielmrezende/grifo.svg" alt="Licença MIT">
  </a>
</div>

## Sobre

O Grifo é um editor de Markdown derivado do [MarkText](https://github.com/marktext/marktext). Ele mantém o motor de edição do MarkText e evolui a interface e o comportamento de forma independente.

## Recursos

- Pré-visualização em tempo real (WYSIWYG) com uma interface limpa, para escrever sem distrações.
- Suporte à [especificação CommonMark](https://spec.commonmark.org), ao [GitHub Flavored Markdown](https://github.github.com/gfm/) e, em parte, ao [Markdown do Pandoc](https://pandoc.org/MANUAL.html#pandocs-markdown).
- Extensões como fórmulas matemáticas (KaTeX), diagramas (Mermaid, PlantUML, Vega), front matter e emojis.
- Atalhos para parágrafos e estilos inline.
- Exportação para **HTML** e **PDF**.
- Vários temas, claros e escuros.
- Modos de edição: **código-fonte**, **máquina de escrever** e **foco**.
- Colar imagens direto da área de transferência.

## Desenvolvimento

Requisitos: Node.js 20.19 ou mais recente, pnpm 10 e as ferramentas de compilação nativa da sua plataforma (veja o [guia de build](packages/website/content/docs/dev/BUILD.md); no Windows, as Build Tools do Visual Studio 2022 são obrigatórias já na instalação).

```sh
pnpm install
pnpm run dev           # roda o app em modo de desenvolvimento
pnpm run test          # testes unitários
pnpm run lint          # ESLint
pnpm run typecheck     # checagem de tipos
pnpm run build:win     # gera o instalador do Windows (build:mac / build:linux)
```

A arquitetura e as convenções do projeto estão descritas em [AGENTS.md](AGENTS.md).

## Créditos

O Grifo existe graças ao [MarkText](https://github.com/marktext/marktext), criado por [Jocs](https://github.com/Jocs) e mantido por seus [contribuidores](https://github.com/marktext/marktext/graphs/contributors). O histórico de commits deste repositório preserva a autoria original de todo esse trabalho.

## Licença

[MIT](LICENSE). O aviso de copyright original do MarkText é mantido no arquivo de licença.
