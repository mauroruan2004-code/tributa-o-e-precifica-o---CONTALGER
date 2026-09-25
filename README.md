# Contalger — Tributação e Precificação

HTML estático preparado para GitHub Pages. Logotipo original incorporado, sem fontes, imagens ou bibliotecas externas necessárias para abrir a interface. Mantém o motor de sugestões do Convênio 87/2002, exclusão individual/em lote e exportação XLSX formatada.

## Publicar

1. Extraia o ZIP.
2. Envie o arquivo **index.html** e o arquivo **.nojekyll** diretamente para a raiz do repositório. Não envie apenas o ZIP nem deixe index.html dentro de outra pasta.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment → Source**, selecione **Deploy from a branch**.
5. Selecione a branch **main** (ou a branch que contém os arquivos) e a pasta **/(root)**. Clique em **Save**.
6. Aguarde a publicação e abra o endereço exibido em Pages. Em um repositório comum, o caminho inclui o nome do repositório.

Guia oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## O que esta versão faz

- Abre diretamente em modo de demonstração da Contalger.
- Permite cadastro manual, simulações, sugestões do convênio e exportação Excel.
- Permite selecionar produtos em várias páginas, selecionar os resultados da busca e excluir com confirmação.
- Aplica o logotipo enviado e as cores azul e laranja da Contalger.

## Limites da versão HTML atual

- Dados alterados e exclusões duram somente na sessão: recarregar a página restaura os dados iniciais.
- O arquivo contém o catálogo de referência incorporado. Tudo que está no HTML publicado pode ser lido por quem acessa o site. Use esta versão para demonstração, não como ambiente privado de clientes.
- Empresas, usuários e permissões são demonstrações locais. Não há autenticação nem proteção de dados por usuário.
- Importação de XML, Excel e PDF ainda não está implementada neste HTML. O botão informa essa limitação; o cadastro manual está disponível.
- A base do Convênio 87/2002 é a do motor anterior fornecido, com 271 itens. As sugestões exigem revisão da Contalger e não aplicam isenção automaticamente.
- Não há dependência de PHP para publicar esta versão. Este pacote não altera nem publica o repositório automaticamente.

Para atualizar o site, substitua index.html e aguarde a nova publicação do Pages.
