<html>
    <head><meta charset="UTF-8"> </head> 
    <style>
        body {
            background-color: rgb(0, 0, 0);
            background-size:100%; 
            color:rgb(255, 255, 255);
            text-align: center;
            font-size:100px;

        }
    </style>
       
    
   
    <script>
    
        function pulaLinha() {
             document.write("<br>");
    }

        function mostra(frase) {
            document.write(frase);
        pulaLinha();
    }
        function  perdedor(){
            document.write("Tente Novamente! <br> ;-;")
        }
        function ganhador(){
            document.write("Uhul, você é incrível! <br> <3")
        }
        // mat.round --> arrendonda o número 
        // mat.random --> número aleatório
        // parseInt --> retorna um inteiro 
        var numero=Math.round(Math.random()*10);
        var chute=parseInt(prompt("Digite seu chute de 1 a 10:"));
        if (numero==chute){
            pulaLinha();
            mostra("Você acertou!");
            ganhador();
        } else {
            pulaLinha();
            mostra ("Você errou, o número pensado foi "+numero); 
            perdedor();
        }
   



    </script>

  
    
</html>
