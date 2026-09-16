# HOMERFPSSS

Site pessoal / link hub do canal **HOMERFPSSS** — streamer de games, com lives na TikTok e na Kick.

🔗 **Hub (link-in-bio):** https://claude.ai/artifact/ENrmifVERvAGY1TpRboYVn
🔗 **Configurações/Setup:** https://claude.ai/artifact/WLuy7P36AccgAXcU9SaKmm

## O que tem aqui

- **`index.html`** — página principal (hub): nome/marca, botão de compartilhar, links pro TikTok/Kick/Discord/Configurações, agenda semanal (editável, veja abaixo), seção de clipes em destaque e navegação por setas entre páginas.
- **`setup.html`** — página de configurações: specs do PC, periféricos e configs de jogo (sensibilidade, keybinds etc).

Cada arquivo é uma página HTML única e independente (CSS e JS embutidos, sem build step, sem dependências externas além das fontes do Google Fonts).

## Identidade visual

- Tema dark-only (sem modo claro), fundo roxo quase preto com acentos roxo/magenta neon
- Tipografia: **Rajdhani** (títulos), **Manrope** (texto), **Permanent Marker** (assinatura "homerps")

## Agenda semanal editável

O hub tem um botão **"Editar"** ao lado de "Agenda da semana", visível só pro dono da página. Ele abre um formulário pra marcar dias de live, horário e o que vai rolar (jogo/atividade). Ao salvar, a própria página se republica com os dados novos — usa capacidades de runtime do Claude Artifacts (`artifact` + `user`).

## Como as páginas são hospedadas

As páginas rodam como [Claude Artifacts](https://claude.ai) (link privado até ser compartilhado). Esse repositório é o backup/versionamento do código-fonte: toda vez que uma página é atualizada, o HTML aqui é sincronizado com o Artifact publicado.

## Fluxo de atualização

1. Peça a mudança numa conversa com o Claude (no app Claude/Cowork)
2. O Claude edita o HTML e republica o Artifact correspondente
3. O arquivo atualizado chega nessa pasta local
4. Revise as mudanças no GitHub Desktop, escreva um resumo e dê **Commit** + **Push**

## Roadmap / próximos passos

- Preencher a agenda semanal de verdade (dias/horários fixos)
- Adicionar clipes em destaque na seção do hub
- Preencher specs reais do setup (PC, periféricos, configs de jogo)
- Migrar pra um domínio próprio (ex: `homerfpsss.com`/`.gg`/`.tv`), hospedado via GitHub Pages
