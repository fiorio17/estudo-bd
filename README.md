# Mapa de estudo — Banco de Dados II

Material de revisão da disciplina Banco de Dados II (Prof. Leonardo Sápiras),
montado a partir dos três decks da disciplina. Páginas HTML independentes,
sem nenhuma dependência externa — abrem direto no navegador, inclusive offline.

## O que tem aqui

| Página | Para quê |
|---|---|
| [`guia.html`](guia.html) | Os três assuntos completos: modelagem relacional (Codd, chaves, dependência funcional, integridade, operadores), orientação a objetos (classe, objeto, herança, encapsulamento, bancos de dados OO) e bancos de dados temporais (tipos de tempo, versionamento, SQL temporal no PostgreSQL). Autoteste com 15 flashcards no fim. |
| [`simulado.html`](simulado.html) | As 75 questões reais do Google Forms de revisão (25 por módulo), com correção imediata e explicação, gabarito conferido contra os slides. |

## Sobre o simulado

O professor passou um Google Forms de revisão com **75 questões (25 por
módulo)**: Modelagem relacional, Orientação a objetos e Bancos de dados
temporais. O simulado deste repositório usa o texto exato dessas questões,
com o gabarito conferido pergunta a pergunta contra os três decks da
disciplina — nenhuma inconsistência encontrada.

## Rodando local

Não tem build, servidor nem instalação:

```bash
git clone https://github.com/fiorio17/estudo-bd.git
```

Abra `index.html` no navegador. Funciona sem internet.

## Estrutura

```
index.html      página inicial
guia.html       guia completo dos três temas
simulado.html   simulado
theme.js        alterna tema claro/escuro (compartilhado)
```

Cada página carrega o próprio CSS e JS embutidos; `theme.js` é o único
arquivo compartilhado.

## Bibliografia

ROB, Peter; CORONEL, Carlos. *Sistemas de Banco de Dados*. Cengage Learning.
