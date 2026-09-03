# Meu Portfólio

Site de portfólio pessoal — HTML, CSS e JavaScript puro, sem dependências externas além das fontes do Google Fonts. Um único arquivo (`index.html`), pasta `imagens/` e o currículo em `curriculo/`.

## Como visualizar

Basta abrir `index.html` no navegador (duplo clique).

## Como personalizar

- **Textos**: seções "Sobre", "Projeto" e "Skills" estão em texto simples dentro de `index.html`.
- **Projeto em destaque**: hoje mostra só o Ariane Paiva Studio (único projeto em produção). Pra adicionar outro, duplique o bloco `<div class="project-frame">` dentro da seção `#projeto`.
- **Cores**: no topo do arquivo, dentro de `<style>`, as variáveis em `:root` (`--paper`, `--ink`, `--accent`, etc.) controlam a paleta.
- **Contato**: seção `#contato`, dentro de `.contact-fields`.
- **Currículo**: `curriculo/index.html` é a fonte (abrir e exportar como PDF via Ctrl+P) que gera `curriculo/Jordan_Souza_Curriculo.pdf`, referenciado pelos botões "Currículo" do site.
- **Foto** (usada só no currículo): `imagens/Jordan.jpeg`.

## Como publicar

O repositório já está publicado via GitHub Pages em `jordansouzadev.github.io`. Qualquer push na branch `main` atualiza o site automaticamente.

## Atualizando o currículo em PDF

1. Edite `curriculo/index.html`.
2. Abra o arquivo no Chrome e exporte via `Ctrl+P` → "Salvar como PDF", sobrescrevendo `curriculo/Jordan_Souza_Curriculo.pdf`.
