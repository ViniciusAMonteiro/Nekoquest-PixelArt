# NekoQuest — Pixel RPG Planner 🐈

Planner mobile de tarefas em pixel art com gatinhos, calendário, Pomodoro, histórico, perfil personalizável e recompensas da vida real editáveis.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `nekoquest`.
2. Envie **todos os arquivos desta pasta** para a raiz do repositório: `index.html`, `manifest.json`, `service-worker.js`, `cat.svg`, `cat-192.png` e `cat-512.png`.
3. Abra **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e clique em **Save**.
4. Aguarde o link HTTPS, normalmente `https://SEU-USUARIO.github.io/nekoquest/`.
5. Abra o link no celular. Android/Chrome: menu ⋮ → **Instalar app** ou **Adicionar à tela inicial**. iPhone/Safari: Compartilhar → **Adicionar à Tela de Início**.

## Notas
- A instalação PWA requer HTTPS (GitHub Pages fornece HTTPS). Abrir o HTML diretamente como arquivo não permite instalar como aplicativo.
- Dados e recompensas ficam no armazenamento local do navegador; não há sincronização em nuvem. Exporte backups regularmente.
- Moedas: tarefas rendem moedas com base no XP; sessões Pomodoro rendem 1 moeda. O custo das recompensas pessoais é editável.
