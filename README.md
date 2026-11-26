# Brunin Imports – site

Site da loja online Brunin Imports (São Sebastião - DF). É um único arquivo, `index.html`, com imagens e estilos dentro dele. Não precisa instalar nada.

## Colocar no ar com GitHub Pages
1. Crie um repositório novo no GitHub (ex.: `brunin-imports`).
2. Envie `index.html` e `README.md` para a raiz do repositório (botão **Add file → Upload files**).
3. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch **main** e pasta **/ (root)**, e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/brunin-imports/`.

## WhatsApp da loja (já configurado: +55 61 99234-4134)
Se um dia o número mudar:
Abra `index.html`, procure a linha abaixo e coloque o número com 55 + DDD, só dígitos:

    const WA_NUMBER="";

Exemplo: `const WA_NUMBER="5561999999999";`
Enquanto estiver vazio, os botões de WhatsApp mostram um aviso e não abrem nada. Depois de colocar o número, todos os botões de pedido abrem direto o WhatsApp da loja, com o produto e o tamanho já escritos na mensagem.

## Instagram
Os links usam `brunin_imports_`. Para trocar, procure por `brunin_imports_` no arquivo.
