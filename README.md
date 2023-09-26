# DOE (Diário Oficial Eletrônico)

Sass (https://sass-lang.com/) é utilizado para definir o estilo da aplicação.

O arquivo style/scss/_conf.scss centraliza várias configurações visuais da aplicação, como: cores de fundo, cores de bordas de blocos (BEM),
cores de fontes, ícones, e outras configurações.
Para alterar configurações de estilo da aplicação por meio do arquivo style/scss/_conf.scss uma implementação Sass deve ser utilizada para compilação,
recebendo como entrada o arquivo style/scss/_conf.scss e gerando como saída o arquivo style/css/styles.css. 

Exemplo de instalação e compilção.

1 - Instalar Node.js (https://nodejs.org/en/download/)

2 - Instalar implementação dart2js executando o comando "npm install -g sass" na linha de comando.

3 - Compilar os arquivos de estilo Sass por meio do comando "sass $home_da_aplicacao_doe/style/scss/styles.scss:$home_da_aplicacao_doe/style/css/styles.css"
ou utilizar o argumento "--watch" para a aplicação sass permanecer observando mudanças e realizar compilações a cada mudança detectada.
  
 
