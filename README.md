# Contalger — Tributação e Precificação PI/MA

Pacote preparado para publicação no **GitHub Pages** a partir do arquivo `Contalger Tributacao e Precificacao PI-MA v1.0.0.html`.

## Publicação

1. Crie um repositório no GitHub.
2. Envie **todos os arquivos e pastas deste pacote** para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main`, pasta `/(root)` e salve.
6. Aguarde o endereço do GitHub Pages aparecer nessa mesma tela.

## Estrutura

- `index.html`: aplicativo principal;
- `manifest.webmanifest`: configuração de instalação como aplicativo;
- `sw.js`: cache dos arquivos locais para uso após o primeiro carregamento;
- `icons/`: ícones da aplicação;
- `assets/vendor/pdf.worker.b64.js`: worker local do leitor de PDF;
- `pdf.worker.js`: carregador compatível com o caminho usado pela biblioteca PDF.js;
- `.nojekyll`: impede processamento indevido pelo Jekyll.

## Observações

- Os dados cadastrados pelo aplicativo continuam armazenados no navegador do usuário. Eles não são sincronizados automaticamente entre computadores ou navegadores.
- O GitHub Pages é uma hospedagem estática. A tela de login protege o uso normal do app, mas não substitui autenticação em servidor.
- A aplicação deve ser acessada pelo endereço HTTPS do GitHub Pages, e não abrindo o `index.html` diretamente pelo Explorador de Arquivos.
- Foram removidas 12 marcas de edição acidentais da tela de primeiro acesso.
- Worker PDF extraído: 1,087,212 bytes.
