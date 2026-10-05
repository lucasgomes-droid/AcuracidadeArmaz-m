# Auditoria de Armazém

App de contagem e auditoria de endereços. É uma página única (`index.html`), sem servidor.

- O saldo é consultado direto na API do Zion WMS (`GET /estoque/detalhe`), somente leitura.
- A chave de acesso **não fica neste repositório**: cada aparelho informa a sua na aba Armazém.
- Contagens, ajustes e planos ficam guardados no navegador de cada aparelho.

## Publicar no GitHub Pages

1. Envie o `index.html` para a raiz do repositório.
2. Em **Settings › Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Abra o endereço que o GitHub mostrar, no formato `https://USUARIO.github.io/REPOSITORIO/`.

## Primeiro uso em cada aparelho

1. Aba **Armazém**: cole a chave de acesso e clique em **Salvar chave**.
2. Informe seu nome.
3. Aba **Contar**: informe o endereço e bipe as UAs.
