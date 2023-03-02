Portfólio Responsivo | Enzzo F
Este projeto consiste em um portfólio responsivo desenvolvido utilizando HTML, CSS e JavaScript, juntamente com o auxílio de bibliotecas como Bootstrap e jQuery. O objetivo era criar uma plataforma atraente e funcional, que refletisse as habilidades de design e programação do desenvolvedor.

Instruções
Abra o arquivo index.html em uma IDE
Navegue pelo site utilizando o menu no topo da página.
Confira os certificados do desenvolvedor na seção "Certificados".
Entre em contato com o desenvolvedor utilizando as informações fornecidas na seção "Contato".
Conteúdo
Na seção "Contato" do site, há uma caixa "Envie uma mensagem" onde o usuário pode inserir seu nome, endereço de e-mail e mensagem. Ao clicar no botão "Enviar", uma função JavaScript é acionada.
Essa função é responsável por concatenar as informações inseridas pelo usuário e abrir o aplicativo de e-mail padrão do computador, pré-preenchendo os campos "Para", "Assunto" e "Corpo da mensagem" com as informações concatenadas.
A função começa recuperando as informações inseridas pelo usuário, usando o método JavaScript document.getElementById() para obter o valor dos campos de entrada. Em seguida, ela usa o método encodeURIComponent() para codificar os caracteres especiais na mensagem, garantindo que ela seja transmitida corretamente.
Depois disso, a função concatena as informações usando uma string de modelo JavaScript. Essa string de modelo usa placeholders ${} para inserir as informações do usuário no corpo da mensagem.
Por fim, a função usa o método window.location.href para abrir o aplicativo de e-mail padrão do computador, com os campos "Para", "Assunto" e "Corpo da mensagem" pré-preenchidos com as informações concatenadas.
Essa funcionalidade é útil porque simplifica o processo de envio de uma mensagem de contato para o desenvolvedor do site. O usuário pode enviar uma mensagem diretamente do site, sem precisar sair da página e abrir manualmente o aplicativo de e-mail.

O estilo foi aplicado de forma consistente em todo o site, utilizando uma paleta de cores harmônica e uma tipografia legível. Foram utilizados seletores CSS para aplicar estilos específicos em elementos como links, botões e imagens, tornando a navegação mais clara e intuitiva para o usuário.
O design responsivo foi implementado utilizando as classes do Bootstrap, que permitem que o site se adapte automaticamente a diferentes tamanhos de tela. Isso garante uma experiência de usuário consistente em dispositivos móveis e desktops.

Este projeto contém os seguintes arquivos:

index.html: arquivo HTML principal.
style.css: arquivo CSS que contém as regras de estilo para o site.
logo3.png: imagem utilizada no cabeçalho do site.
okay.png, okay2.png, okay4.png: imagens utilizadas na seção "Certificados".
README.md: este arquivo.
Créditos
Este projeto foi desenvolvido por Enzzo Ferrari.
