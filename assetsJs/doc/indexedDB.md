#Biblioteca indexedDB.js
>indexedDB.js requer a biblioteca idb.js para operar, veja como utilizar a biblioteca indexedDB.js

    todas as funções disponibilizadas pela indexedDB.js retornam uma Promise
# 
    <script>
    
        //a biblioteca disponibiliza uma constante chamada de 'db'.
        //esta constante faz a gestão dos dados no front-end e sincroniza com o back-end
        
        //ler os dados de uma entidade
        db.exeRead("nome_da_entidade");
        
        //criar ou atualizar os dados de uma entidade
        db.exeCreate("nome_da_entidade", {nome: 'jorge'});
        
        //excluir um registro de uma entidade 
        db.exeDelete("nome_da_entidade", 1);

    </script>   