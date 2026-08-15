# Meu Portfólio

Site de portfólio pessoal — HTML, CSS e JavaScript puro, sem dependências externas. Um único arquivo (`index.html`) + pasta `imagens/`, fácil de editar e publicar.

## Como visualizar

Basta abrir `index.html` no navegador (duplo clique).

## Como personalizar

Tudo está em `index.html`:

- **Textos**: seção "Sobre", descrições dos projetos e skills estão em texto simples no HTML.
- **Projetos**: cada projeto é um bloco `<article class="project-card">` — copie um bloco existente para adicionar um novo projeto.
- **Cores**: no topo do arquivo, dentro de `<style>`, as variáveis em `:root` (`--bg`, `--accent`, etc.) controlam a paleta.
- **Contato**: seção `#contato`, links de e-mail, GitHub, LinkedIn e WhatsApp.
- **Foto**: `imagens/Jordan.jpeg`, referenciada no hero (`<div class="hero-photo-frame">`). Para trocar, substitua o arquivo mantendo o mesmo nome, ou edite o `src` da tag `<img>`.

## Como publicar (grátis)

**Opção 1 — GitHub Pages**

```bash
cd "meu portfolio"
git init
git add .
git commit -m "Portfólio inicial"
gh repo create meu-portfolio --public --source=. --push
gh repo edit --enable-pages   # ou ative em Settings > Pages no GitHub
```

**Opção 2 — Vercel / Netlify**

Arraste a pasta `meu portfolio` para [vercel.com/new](https://vercel.com/new) ou [app.netlify.com/drop](https://app.netlify.com/drop) — publica em segundos, sem configuração.

## Observação sobre os repositórios dos projetos

Os links para `ariane-paiva-studio` e `iron-manager` no site apontam para repositórios **privados** no GitHub. Quem visitar o portfólio sem acesso verá uma página 404. Para mostrar o código a recrutadores, considere:

- Criar um repositório público separado só com um resumo/demo do projeto, ou
- Conceder acesso de leitura pontual ao repositório privado, ou
- Gravar um GIF/vídeo curto do sistema funcionando e embutir no portfólio.
