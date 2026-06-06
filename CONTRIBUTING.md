# 🤝 Como contribuir

Bem-vindo! Este repositório é mantido por um grupo de amigos estudando juntos. Atualizá-lo faz parte do estudo: além do conteúdo, a gente treina o **fluxo real de trabalho com Git** que se usa em empresa. Não tem stress — errar aqui é de graça e é assim que se aprende.

> Se você nunca abriu um Pull Request, este é o lugar perfeito pra aprender. Pergunte sem medo.

## 🧭 Antes de começar

- **Pegue uma tarefa numa [Issue](../../issues).** Se o que você quer fazer não tem issue, abra uma primeiro. Isso evita duas pessoas mexerem na mesma coisa.
- **Evite editar o mesmo arquivo que outra pessoa** está mexendo ao mesmo tempo — combinem no grupo.
- **Atualize seu repositório local** antes de começar: `git pull origin main`.

## 🔁 O fluxo, passo a passo

```bash
# 1. crie uma branch a partir da main
git checkout main
git pull origin main
git checkout -b tipo/descricao-curta

# 2. faça suas alterações e confira o que mudou
git status
git add .

# 3. faça o commit com uma mensagem clara
git commit -m "tipo: o que você fez"

# 4. suba a branch
git push origin tipo/descricao-curta
```

Depois, no GitHub: abra um **Pull Request** da sua branch para a `main`, descreva o que fez e **peça review** de outra pessoa do grupo. Só dá merge **depois do review**.

## 🌿 Como nomear branch e commit

Mantenha simples e padronizado. Use um destes prefixos (`tipo`):

| Prefixo | Quando usar | Exemplo de branch |
|---|---|---|
| `caderno` | novo caderno ou edição de conteúdo | `caderno/ponteiros` |
| `fase` | ajuste numa fase do plano | `fase/atualiza-checkpoint-f3` |
| `fix` | corrigir erro/typo/link quebrado | `fix/link-univesp` |
| `docs` | README, este arquivo, etc. | `docs/atualiza-recursos` |

Mensagem de commit no mesmo espírito: `caderno: adiciona caderno de ponteiros` ou `fix: corrige link da UNIVESP`.

## 📒 Como adicionar um caderno novo

O board (`index.html`) já tem o estilo dos cadernos. Para um novo tópico:

1. Combinem quem é o **dono** do caderno (quem escreve).
2. Siga o mesmo padrão visual dos cadernos existentes (título, cartões de comando, bloco de código, pegadinhas, checkpoint).
3. Adicione o link do caderno no menu lateral e na fase correspondente.
4. Abra o PR — alguém revisa **conteúdo** (está certo? está claro?) antes do merge.

## 👀 Code review entre amigos

Revisar o trabalho dos outros é tão importante quanto escrever. Ao revisar, olhe:

- **Está correto?** Especialmente código C — testem antes de aprovar.
- **Está claro pra um iniciante?** Se você não entenderia de primeira, comente.
- **Segue o padrão?** Nomes, estilo, formatação.
- Seja gentil e específico. Comentário bom é "isso aqui pode confundir, que tal X?", não "tá errado".

## ✅ Checklist antes de abrir o PR

- [ ] Testei (se mexi em código C, compilou e rodou).
- [ ] Não commitei executáveis nem `.o` (o `.gitignore` cuida disso).
- [ ] Links e imagens funcionam.
- [ ] A mensagem de commit e o nome da branch seguem o padrão.
- [ ] Pedi review pra alguém do grupo.

## ❓ Dúvidas

Travou em algo do estudo ou do Git? **Abra uma [Issue](../../issues)** descrevendo o problema. Documentar dúvidas ajuda quem vier depois — inclusive o "você do futuro".

---

<sub>Lembrete do grupo: vídeo não forma mestre, código forma. Bons commits. 🚀</sub>
