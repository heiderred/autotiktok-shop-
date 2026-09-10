# AutoTikTok Shop - Sistema de Produção

Sistema completo de gestão de produção de vídeos para afiliados do **TikTok Shop**, em um único arquivo HTML. Cadastre produtos, gere roteiros automaticamente, acompanhe o fluxo de produção e organize suas postagens — tudo sem sair da página.

![Versão](https://img.shields.io/badge/vers%C3%A3o-1.1-ff0050)
![Linguagem](https://img.shields.io/badge/lang-pt--BR-00f2ea)

## Funcionalidades

- **Painel** — visão geral: produtos ativos, roteiros gerados, vídeos em produção e meta diária
- **Produtos** — cadastro completo (preço, comissão, vendidos, avaliação, benefícios, problema que resolve)
- **Roteiros** — geração automática com 3 modelos prontos:
  - Problema → Solução → Prova
  - Antes vs Depois
  - Curiosidade Chocante
  - Cada roteiro inclui ganchos, legendas, hashtags e sugestão de música
- **Produção (Pipeline)** — acompanhamento das etapas: roteiro, assets, voz, edição, thumbnail, postado
- **Calendário** — planejamento mensal de postagens
- **Verificação** — checklist de 10 passos da produção + metas diárias com barra de progresso
- **Ferramentas** — acesso embutido ao painel 3xapp.shop, ElevenLabs e TikTok Studio + configurações rápidas (API key ElevenLabs, voz, link da loja, horário de postagem)
- **Exportar** — backup e restauração em JSON / exportação de roteiros em TXT

## Como usar

### Opção 1: Online (GitHub Pages)
Acesse a URL do seu GitHub Pages após ativar (veja instruções abaixo).

### Opção 2: Local
Baixe o `index.html` e abra direto no navegador. Não precisa de servidor nem instalação.

> **Dados salvos no navegador:** os dados ficam no `localStorage` do seu navegador. Use a aba **Exportar** para fazer backup antes de trocar de navegador ou limpar os dados. As configurações de API key também ficam só no seu navegador — nada é enviado para servidores.

## Publicando no GitHub Pages (grátis)

1. Crie um repositório no GitHub (ex: `autotiktok-shop`)
2. Faça upload dos arquivos ou envie via git:

```bash
git init
git add .
git commit -m "Primeira versão do AutoTikTok Shop"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/autotiktok-shop.git
git push -u origin main
```

3. No repositório, vá em **Settings → Pages**
4. Em "Source", selecione a branch `main` e a pasta `/ (root)`
5. Salve — em alguns minutos seu sistema estará em `https://SEU-USUARIO.github.io/autotiktok-shop/`

## Tecnologias

- HTML5, CSS3 e JavaScript puros (sem dependências, sem build)
- Armazenamento local (`localStorage`)
- Design responsivo com tema escuro

## Aviso

Este é um sistema de organização pessoal. Ele não possui integração oficial com a API do TikTok, ElevenLabs ou 3xapp.shop — os acessos são feitos por iframe/incorporação ou manualmente. Marca registrada e nomes de produtos citados pertencem aos seus respectivos donos.
