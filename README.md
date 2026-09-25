# Mapa de estudo — Banco de Dados II

Material de revisão da disciplina Banco de Dados II (Prof. Leonardo Sápiras),
montado a partir dos três decks da disciplina. Páginas HTML independentes,
sem nenhuma dependência externa — abrem direto no navegador, inclusive offline.

## O que tem aqui

| Página | Para quê |
|---|---|
| [`guia.html`](guia.html) | Os três assuntos completos: modelagem relacional (Codd, chaves, dependência funcional, integridade, operadores), orientação a objetos (classe, objeto, herança, encapsulamento, bancos de dados OO) e bancos de dados temporais (tipos de tempo, versionamento, SQL temporal no PostgreSQL). Autoteste com 15 flashcards no fim. |
| [`simulado.html`](simulado.html) | 44 questões objetivas com correção imediata e explicação, na mesma proporção de temas do formulário real (~1/3 para cada assunto). |

## Sobre o simulado

O professor passou um Google Forms com **75 questões (25 por assunto)**,
aparentemente geradas por IA a partir do mesmo material. O simulado deste
repositório começa com uma **base própria**, gerada a partir dos slides —
a ideia é ir ajustando e completando as questões conforme as reais forem
sendo vistas no Forms, para bater cada vez mais com a prova de verdade.

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
