# Digi 3D Store

Loja virtual simples: o cliente monta o carrinho e envia o pedido pelo WhatsApp. Sem pagamento no site.

## Arquivos
- `index.html` – loja e painel do administrador
- `products.json` – produtos, categorias e configurações que os clientes veem
- `logo.png` – logo da loja
- `.nojekyll` – necessário para o GitHub Pages

## Como colocar no ar (GitHub Pages)
1. Crie uma conta em github.com e clique em **New repository**. Nome sugerido: `loja`. Deixe **Public**.
2. Clique em **uploading an existing file** e envie TODOS os arquivos desta pasta (incluindo `.nojekyll`).
3. Vá em **Settings > Pages**. Em **Branch**, escolha `main` e `/ (root)` e clique em **Save**.
4. Em cerca de 1 minuto o site fica em `https://SEU-USUARIO.github.io/loja/`.

## Painel do administrador
Acesse `https://SEU-USUARIO.github.io/loja/#admin` (não há link para ele na loja).
- Senha inicial: `admin123` (troque em Configurações).
- Em Configurações, troque o número do WhatsApp (formato `5511999999999`).

## Como atualizar produtos
1. Entre no painel, cadastre ou edite produtos e fotos.
2. Clique em **Exportar dados**. Será baixado o arquivo `products.json`.
3. No GitHub, abra o repositório, clique em `products.json` e substitua pelo novo arquivo.
4. Aguarde cerca de 1 minuto e a loja estará atualizada para todos.

Observação: o painel guarda um rascunho no navegador onde você editou. Os clientes só veem o que estiver no `products.json` do GitHub. A senha do painel fica dentro do arquivo, então serve só para evitar mexidas acidentais, não é segurança forte.
