Usando a LibCurl no DevC++
=======================

Talvez o amigo leitor esteja se perguntando porque usar uma libcurl se podemos fazer com sockets, a resposta é simples: porque é muito mais simples, principalmente para os recém iniciados em C/C++.

Usar a libcurl em Linux é muito simples e encontra-se em vários sites e principalmente no site oficial vários exemplos e como se compilar, mas existe um porém, quando se vai usa-lá no DevC++ é preciso fazer alguns ajustes e este artigo irá tratar estes ajustes.

**1º Passo – Baixar a biblioteca**

Será necessário fazer o download de dois pacotes: zlib-1.2.3-1spec e libcurl-7.14.0_nossl-1sid sendo a zlib uma dependência para a libcurl.

Após o download, basta um duplo clique sobre a zlib para iniciar o wizard de instalação de pacotes do DevC++, depois disto instale então o pacote referente a libcurl

**2º Passo – Criar um projeto e configurá-lo**

 - Após o projeto estar criado e todos os arquivos estarem salvos, clique no menu **Project**, em seguida em **Project Options**.
 - Na guia **Parameters** clique em **Add Library or Object**, vá até o diretório de instalação do DevC++ e procura pelo diretório lib, acesse e clique em **libcurl.a**
 - Clique na guia **Directories**, em seguida clique em **Library Directories**, digite o caminho, nos meu caso: c:\Dev-cpp\lib, ou clique no botão com ícone de diretórios e escolha o diretório lib que está dentro da sua instalação do DevC++. Após ter selecionado, o botão **Add**
 - Clique em Include **Directories** e faça o mesmo passo descrito anteriormente e porém para o diretório include

Pronto agora é só escrever o código ou usar um dos exemplos no site oficial e compilar.

Exemplos: http://curl.haxx.se/libcurl/c/example.html

E é isso abraços!
