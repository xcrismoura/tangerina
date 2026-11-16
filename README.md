# 🍊 Tangerina

Timer de estudo com Foco, Flow e Descanso proporcional. Funciona como app instalável (PWA).

## Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `tangerina`) e envie **todos** os arquivos desta pasta para a raiz dele
   (Add file → Upload files, arraste o conteúdo e confirme em *Commit changes*).
2. Vá em **Settings → Pages**.
3. Em *Build and deployment*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e clique em **Save**.
4. Em 1–2 minutos o site fica em `https://SEU-USUARIO.github.io/tangerina/`.

## Instalar como app
- **Android / Chrome:** menu ⋮ → *Instalar app* (ou *Adicionar à tela inicial*).
- **Computador / Chrome ou Edge:** ícone de instalar na barra de endereço.
- **iPhone / Safari:** Compartilhar → *Adicionar à Tela de Início*.

## Atualizar o site depois
Ao alterar o `index.html`, aumente o número em `const CACHE='tangerina-v1'` no arquivo `sw.js`
(para `v2`, `v3`...). Assim os aparelhos que já instalaram recebem a nova versão.
