# Senai-versoes-colaboracoes
Repositório Inicial
readme de exemplo

Título do projeto :
Extensão do navegador de download em massa de dados da Terra

Descrição:
Uma extensão do navegador para adicionar capacidade de download de dados em massa ao site Earthdata Search.

Estrutura do código:
manifest.json:
Inclui todas as permissões e instruções para os nomes dos arquivos a serem selecionados para a extensão.

content.js:
O código JavaScript para alterar qualquer coisa no conteúdo da página da web está incluído aqui. Por exemplo, o código para anexar o botão de download, observar mutações granulares e buscar os links de download do site de dados CMR quando o botão é clicado etc.

bg.js:
Este é um código JavaScript para baixar os links em segundo plano que recebe os links dos scripts de conteúdo na forma de mensagens e salva no armazenamento local do navegador.

pop-up.html:
Esta é uma página html que aparece quando o ícone da extensão na barra de título do navegador é clicado.

pop-up.js:
Este é um arquivo JavaScript que possui um código que busca os nomes dos arquivos baixados do armazenamento local do navegador que está incluído no script da página html.

estilo.css:
Isso tem o truque css do código de estilo para as bordas dos botões de pausa e reprodução para alternar quando clicados

imagens:
Estes possuem as imagens com extensão .png para serem utilizadas para os ícones da extensão do navegador.

Como executar:
Clone o repositório git para sua área de trabalho local
Abra um navegador da Web,
se for Google Chrome, abra chrome://extensions/
Ative o modo Desenvolvedor no canto superior direito da página
Clique em carregar descompactado e navegue na pasta git clonada e selecione src e clique em "Selecionar pasta"
Agora abra o site Earth Data em uma nova página, selecione o conjunto de dados e clique em Bulk Download now
se for Firefox, abra about:debugging
Clique em carregar complemento temporário, navegue até a pasta src e abra o arquivo de manifesto
Agora abra o site Earth Data em uma nova página, selecione o conjunto de dados e clique em Bulk Download now
Como testar:
A execução do arquivo de teste em um Eclipse IDE com os arquivos Selenium jar incluídos, automatiza o processo de teste e imprime o sucesso/falha dos casos de teste listados.


LEMBREI DO COMANDO: GIT STATUS

