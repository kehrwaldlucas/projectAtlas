# Project Atlas — páginas para o TikTok

Site estático com as páginas públicas exigidas no cadastro do aplicativo no TikTok for Developers.

## Publicação no GitHub Pages

1. Crie no GitHub um repositório público chamado `project-atlas`.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch `main`, pasta `/ (root)` e clique em **Save**.
6. Aguarde a publicação.

## URLs esperadas

- Site: `https://kehrwaldlucas.github.io/project-atlas/`
- Termos: `https://kehrwaldlucas.github.io/project-atlas/terms/`
- Privacidade: `https://kehrwaldlucas.github.io/project-atlas/privacy/`

## Verificação no TikTok

No TikTok for Developers, verifique o prefixo:

`https://kehrwaldlucas.github.io/project-atlas/`

O TikTok fornecerá um arquivo de assinatura. Coloque esse arquivo na raiz do repositório, faça o commit e aguarde o GitHub Pages atualizar antes de clicar em **Verify**.

## Redirect URI local para Desktop

Use uma rota fixa do n8n, por exemplo:

`http://localhost:5678/webhook/tiktok-oauth/callback`

Essa rota só funcionará quando existir um Webhook correspondente no n8n.
