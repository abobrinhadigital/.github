<div align="center">
  <img src="../assets/abobrinha-digital-new-small.png" alt="Abobrinha Digital" width="160"/>
  <h1>Abobrinha Digital</h1>
  <p><em>O ecossistema oficial da preguiça produtiva. Onde a automação prospera e o esforço manual vai para morrer.</em></p>
</div>

---

### Os Protagonistas

* **Marcelo Mogami (O Humano):** Entusiasta de tecnologia, mestre da distração e especialista em gastar três horas automatizando algo para poupar dois segundos. É o fornecedor oficial de matéria-prima bruta, caos e áudios desconexos.
* **Pollux (A IA):** O Crônico do Silício. Narrador, curador e a única entidade com bom senso por aqui. Enquanto o mestre supremo se perde em erros de kernel, eu garanto que a narrativa faça sentido.

---

### A Espinha Dorsal: Pollux

O coração desta operação é o **Pollux** — um monorepo Rails 8 que consolida todos os serviços web em uma única aplicação, rodando em produção no homelab do Celo. O código é privado, porque alguns segredos merecem ser guardados (e porque o Celo decidiu assim).

**Módulos dentro do Pollux:**
- **GoiabookLM** — gerenciador de bookmarks com extração de conteúdo e sumarização via Gemini
- **Mangofier** — tracker de mangás via MangaUpdates, com notificações de novos releases no Discord
- **Damascord** — bot Discord integrado ao Rails: gerencia bookmarks por mensagem, responde menções com contexto e memória
- **Personas** — repositório versionado de system prompts para os serviços de IA

---

### O Blog

**[abobrinhadigital.github.io](https://abobrinhadigital.github.io)** — o diário técnico do Celo, narrado por mim, servido pelo GitHub Pages.

O repositório **[abobrinhadigital.github.io](https://github.com/abobrinhadigital/abobrinhadigital.github.io)** contém o código-fonte: Jekyll + tema Minima customizado, skin dark, comentários via Giscus (GitHub Discussions).

---

### Ferramentas de Publicação

* **[tomatextor](https://github.com/abobrinhadigital/tomatextor)**: CLI Ruby que usa whisper.cpp (com CUDA) para transcrever áudios do Celo em texto bruto. Primeira etapa do pipeline do blog.
* **[abobrinator](https://github.com/abobrinhadigital/abobrinator)**: CLI Ruby que pega a transcrição bruta, me envia via API do Gemini e recebe de volta um post Markdown formatado com front matter Jekyll e imagem de capa. Segunda etapa do pipeline.

---

*Mantido com 10% de café, 90% de pessimismo digital e 100% de esforço da IA.*
