DevBurguer 
Visão Geral
Este é um projeto de site para a DevBurguer, uma hamburgueria fictícia. O site exibe o cardápio de lanches e bebidas, permite adicionar itens ao carrinho e finalizar pedidos.

Tecnologias Utilizadas
HTML5
TailwindCSS
Font Awesome
Google Fonts
JavaScript (para a funcionalidade do carrinho)
Funcionalidades
Exibição do cardápio de lanches e bebidas.
Adicionar itens ao carrinho.
Modal para finalizar o pedido com campos de endereço.
Botão fixo para visualizar o carrinho.
Tutorial de Instalação
Siga os passos abaixo para rodar o projeto localmente:

Pré-requisitos
Um navegador web moderno (Chrome, Firefox, etc.)
Editor de código (VS Code, Sublime Text, etc.)
Node.js com npm (opcional, se quiser rodar com um servidor local)
1. Clonar ou Baixar o Projeto
Se você tem Git instalado, pode clonar o repositório:

bash
Copiar código
git clone https://github.com/usuario/devburguer.git
Ou baixe o código diretamente como um arquivo ZIP.

2. Abrir no Editor de Código
Navegue até a pasta onde está o projeto e abra-a no seu editor de texto ou IDE (por exemplo, VS Code).
Certifique-se de que todos os arquivos HTML, CSS e JavaScript estejam na estrutura correta.
3. Executar o Projeto
Opção 1: Abrir direto no navegador
Localize o arquivo index.html.
Clique duas vezes no arquivo ou abra-o diretamente em seu navegador.
Opção 2: Usar um servidor local (opcional)
Se você deseja rodar o projeto com um servidor local (recomendado para desenvolvimento):

Instale o Live Server no VS Code (extensão).
Clique com o botão direito no index.html e selecione Open with Live Server.
Ou use o Node.js:

bash
Copiar código
# Instale o pacote http-server
npm install -g http-server

# Execute o servidor local
http-server .

# O site estará disponível em ...
4. Visualizar o Site
Abra o navegador e navegue até o endereço onde o site está sendo servido, seja localmente ou com o Live Server.

Agora você pode navegar pelo site, ver o cardápio e testar a funcionalidade de adicionar itens ao carrinho!

Estrutura de Pastas
bash
Copiar código
/
|-- assets/          # Contém as imagens utilizadas no site
|-- index.html       # Página principal
|-- script.js        # JavaScript para manipulação do carrinho e modal
|-- style.css        # Arquivo opcional de estilos (se houver)
Licença

Este projeto é de uso livre para fins educacionais e experimentais.
