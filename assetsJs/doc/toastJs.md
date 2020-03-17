# Biblioteca toast.js
> como utilizar a biblioteca toast.js
 
    <script>
        toast("Mensagem"); //exibe uma mensagem (tempo e cor padrão)
        toast("Mensagem", 3000); //exibe uma mensagem com tempo de exibição de 3 segundos.
        toast("Mensagem", 3000, "toast-success"); //aplica a classe 'toast-success' ao toast.
        
        //opções de classes pré-definidas para usar no toast
        // toast-success   (verde)
        // toast-warning   (amarelo)
        // toast-error     (vermelho)
        //                 (preto)
    </script>   
 
abaixo uma imagem para visualizar o seguinte exemplo de toast em execução
    
    <script src='assetsJs/toast.js'></script> //inclui a bilioteca toast
    <script>
        toast("Atualizando Sistema...");
    </script>  
![](../../imagens_de_exemplo/exemplo_Toast_Js.jpeg)