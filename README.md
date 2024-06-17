

Desafio Dio - Definição de Orçamento de Billing na Google Cloud Platform

Aqui está um exemplo de como podemos criar um arquivo docker-compose.yml para executar uma aplicação HTML simples em um container Apache:

version: '3.8'
services:
  web:
    image: httpd:latest
    ports:
      - "80:80"
    volumes:
      - ./html:/usr/local/apache2/htdocs/
Neste arquivo docker-compose.yml, definimos um serviço chamado web que usa a imagem httpd mais recente do Docker Hub. O mapeamento de portas "80:80" permite que acessemos o servidor Apache pela porta 80 do seu host. A seção volumes especifica que o diretório ./html no seu host (onde colocaremos nossos arquivos HTML, CSS e JS) será montado no diretório /usr/local/apache2/htdocs/ dentro do container, que é o diretório padrão onde o Apache serve os arquivos.

Para uma aplicação "Hello World" simples, podemos criar um arquivo index.html dentro do diretório ./html com o seguinte conteúdo:

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <title>Hello World</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
Depois de configurar o docker-compose.yml e criar o seu index.html, podemos iniciar o container Apache executando o comando docker-compose up no terminal.

Quando estiver pronto para subir o seu projeto para o GitHub, certifique-se de incluir o arquivo docker-compose.yml e a pasta html com seus arquivos da aplicação no repositório.

Estilizar sua página é uma parte importante do desenvolvimento web. Aqui estão algumas dicas para melhorar o visual da sua aplicação:

CSS (Cascading Style Sheets):

Use CSS para aplicar estilos aos elementos HTML. Você pode criar um arquivo CSS separado ou incluir estilos diretamente no <head> do seu arquivo HTML.
Defina cores, fontes, tamanhos e margens para seus elementos. Por exemplo:

h1 {
    color: #333;
    font-family: Arial, sans-serif;
    font-size: 24px;
    margin-bottom: 20px;
}
Explore seletores CSS, como classes (.minha-classe) e IDs (#meu-id), para aplicar estilos específicos a elementos individuais.
Layout Responsivo:


Certifique-se de que sua página funcione bem em diferentes dispositivos (desktop, tablet, celular). Use media queries para ajustar o layout conforme o tamanho da tela.
Considere usar frameworks CSS como Bootstrap ou Foundation para facilitar o desenvolvimento responsivo.
Imagens e Ícones:


Use imagens relevantes para ilustrar seu conteúdo. Certifique-se de otimizá-las para carregamento rápido.
Explore ícones de fontes como FontAwesome ou Material Icons para adicionar ícones a botões, links e outros elementos.
Tipografia:


Escolha fontes legíveis para o texto do seu site. Evite usar muitas fontes diferentes.
Defina tamanhos de fonte adequados para títulos, parágrafos e outros elementos.
Espaçamento e Alinhamento:


Use margens e preenchimentos para criar espaçamento entre elementos.

Alinhe seus elementos de forma consistente (por exemplo, centralize títulos ou alinhe à esquerda).

Animações e Transições:

Adicione animações sutis para melhorar a experiência do usuário. Por exemplo, você pode usar transições CSS para suavizar mudanças de cor ou posição.
Evite exagerar nas animações para não distrair o usuário.

Teste em Navegadores Diferentes:

Verifique se sua página funciona corretamente nos principais navegadores (Chrome, Firefox, Safari, Edge).

Use ferramentas de desenvolvedor para depurar problemas de layout ou estilo.

Lembre-se de que a estilização é uma parte subjetiva do desenvolvimento, e o que parece bom para você pode não agradar a todos.

Experimente diferentes estilos e peça feedback de outras pessoas para melhorar sua página.

https://docs.google.com/presentation/d/1SXvfoGdNWGfxI0mJD6wddt9EzWK2fXHfyKSenVpeMHs/edit?usp=sharing

https://github.com/denilsonbonatti/docker-projeto1-dio
