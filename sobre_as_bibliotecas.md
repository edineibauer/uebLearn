#Bibliotecas JS utilizadas na Ueb
    as seguintes bibliotecas javascript são minificadas e concatenas em um único arquivo 
    chamado de 'appCore.min.js' disponibilizado na pasta 'assetsPublic' na raiz de qualquer projeto Ueb.
    Este arquivo 'appCore.min.js' é utilizado em todas as páginas de um projeto Ueb.
    
* jquery.min.js
* hammer.min.js
* moment.js
* toast.js
* mustache.js
* idb.js
* indexedDB.js
* draggable.js
* appCore.js
* mask.js
* grid.js
* formValidate.js
* form.js
* apexcharts.js
* grafico.js
* jquery-migrate.1.4.1.min.js


    a seguir, vamos falar um pouco de cada biblioteca e para o que serve.

>legenda sobre a utilização de cada biblioteca:

* grande escala | Fundamental. Uso frequênte no framework Ueb.
* média escala  | Necessário. Uso moderado, sempre que houver a possibilidade.
* baixa escala  | Helper. Uso oportuno, servindo como uma ferramenta para determinados casos.
* escala mínima  | Específico. uso em determinados casos, para funcionalidades específicas.

###jquery.min.js
    disponível em "https://jquery.com"
    grande escala
    
    Agilizar a escrita e trazer mairo velocidade de codificação javascript.
    
###hammer.min.js
    disponível em "https://hammerjs.github.io"
    escala mínima
    
    Adiciona gestos de toque a um site, 
    no momento, só esta sendo utilizado pela outra biblioteca desta lista chamada de 'toast.js'.
    
###moment.js
    disponível em "https://momentjs.com"
    baixa escala
    
    utilizada para facilitar a formatação de datas no javascript
    
###toast.js
    disponível na Ueb.
    grande escala
    
    Apresenta mensagens para o usuário. Para saber mais, leia o arquivo toastJs.md
    
###mustache.js
    disponível em "https://github.com/janl/mustache.js"
    grande escala
    
    Renderizar templates escritos em .mustache (é um motor de templates)
    
###idb.js
    disponível em "https://github.com/jakearchibald/idb"
    grande escala
    
    Comunicação com o banco de dados do navegador "indexedDb", utilizado para armazenar os dados
    de forma local, para que estes estejam disponível offline, esta biblioteca serve como base 
    para a próxima biblioteca
    
###indexedDB.js
    disponível na Ueb.
    grande escala
    
    Faz o gerenciamento do banco de dados local, com funções CRUD que funcionam de forma sincronizada
    com o banco de dados no back-end.
    