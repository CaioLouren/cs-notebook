# 📓 CS Notebook — Ciência da Computação, do zero ao domínio

> Plano de estudo e **caderno vivo** de um grupo de amigos aprendendo Ciência da Computação por inteiro — da linguagem **C** até **System Design** — e construindo um projeto de verdade no caminho.
>
> *A study group's living roadmap & notebook for Computer Science — learning in public, from C to System Design.*

![Linguagem](https://img.shields.io/badge/linguagem-C-555?style=flat-square)
![Base](https://img.shields.io/badge/base-roadmap.sh%20CS-orange?style=flat-square)
![Ritmo](https://img.shields.io/badge/ritmo-4h%2Fdia-success?style=flat-square)
![Status](https://img.shields.io/badge/status-em%20andamento-blue?style=flat-square)
![Idioma](https://img.shields.io/badge/cursos-PT--BR-yellow?style=flat-square)

---

## 📌 Sobre

Este repositório é o **quartel-general** dos nossos estudos. O coração dele é um board interativo (`index.html`) que segue o roadmap de Computer Science completo, dividido em fases, com checkpoints, uma trilha de projeto e referências em português.

Não é um curso passivo: é um plano que a gente **mantém vivo**, marcando o progresso e atualizando conforme avança. A regra de ouro é simples — **vídeo não forma mestre, código forma.**

## 🚀 Como usar

1. Baixe ou clone o repositório.
2. Abra o arquivo **`index.html`** no navegador.
3. Marque os checkboxes conforme concluem cada etapa — **o progresso fica salvo no seu navegador**.

> 💡 **Dica:** ativem o **GitHub Pages** (Settings → Pages → branch `main`) para ter um link público do board, tipo `https://<usuario>.github.io/<repo>/`. Aí dá pra abrir de qualquer lugar e compartilhar no LinkedIn.

## 🗺️ O que tem dentro

| Seção | O que é |
|---|---|
| **Parte 1 — Núcleo** | Linguagem C, ponteiros e memória, estruturas de dados e algoritmos (Fases 0–5). A fundação. |
| **Parte 2 — O resto de CS** | Arquitetura, Sistemas Operacionais, Redes, Bancos de Dados, Segurança, Design Patterns e System Design (Fases 6–13). |
| **🧱 Trilha de projeto** | O capstone: um **banco de dados key-value (mini-Redis) feito do zero em C**, construído camada por camada em paralelo às fases. |
| **🧭 Cobertura do roadmap** | Uma matriz que mapeia **cada nó do roadmap → onde a gente estuda → onde o projeto exercita**. |
| **📣 Build in Public** | Ideias de post no LinkedIn por fase + estratégia pra estudar em público. |
| **📒 Caderno de Strings em C** | Referência completa de strings em C (comandos, funções e pegadinhas). Mais cadernos virão. |

## 🧱 O projeto capstone

Construímos um **banco de dados em C, do zero**, em 9 camadas — de uma hash table com `GET`/`SET`/`DEL` até replicação, sharding e tipos de dados avançados (skip list, trie, bloom filter...). Cada camada crava na prática uma área do roadmap.

> 🔗 O código do capstone vive em um repositório separado: **[adicionar link aqui]**

## 👥 O grupo

Quatro pessoas estudando juntas, com um mentor conduzindo. Donos por área no projeto:

- **Core / estruturas**
- **Rede / protocolo**
- **Persistência / storage**
- **Concorrência / infra**

> Os papéis rodam a cada camada pra todo mundo tocar em tudo.

## 🤝 Como manter atualizado

Tratamos este repo como projeto de software — é treino de fluxo de verdade:

1. Crie uma branch (`git checkout -b atualiza-fase-X`).
2. Faça a alteração (novo caderno, ajuste de fase, link de recurso...).
3. Abra um **Pull Request** e peça **code review** de outra pessoa do grupo.
4. Merge depois do review.

> Esse histórico de PRs com review é parte do que torna o repositório uma prova de maturidade — não só o conteúdo.

## 📚 Recursos-base

- **[roadmap.sh — Computer Science](https://roadmap.sh/computer-science)** — o mapa que estamos seguindo
- **[VisuAlgo](https://visualgo.net/)** — estruturas de dados animadas
- Canais em PT: Pietro Martins, xavecoding, Programação Descomplicada, Professor Mario, UNIVESP

## 🗂️ Estrutura do repositório

```
.
├── index.html        # o board interativo (abra no navegador)
├── README.md         # este arquivo
└── cadernos/          # (futuro) cadernos de referência avulsos
```


<sub>Feito por um grupo de amigos estudando em público. Se este plano te ajudou, deixe uma ⭐.</sub>
