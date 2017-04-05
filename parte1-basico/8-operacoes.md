Parte I - Javascript Básico

8. Operações

8.1. Conteúdo: 

8.2. Estrutura: 

8.3. Exemplo:

Arquivo HTML:

<!DOCTYPE html>
        <html lang="pt-br">
                <head>
                        <meta charset="utf-8"/>
                        <title>JavaScript</title>
                        <script type="text/javascript" src="js/OperacoesMatematicas.js"></script>
                </head>
            <body>
            <div>
                 <input  id="campo1" type="text" name="campo1">
                 <input  id="campo2" type="text" name="campo2">
                 <button onclick="somar()">Somar</button>
            </div>
            </body>
        </html>
        
        
   Aruivo OperacoesMatematicas.js
   
   
        function somar (){
    var campo1 = parseInt(document.getElementById("campo1").value);
    var campo2 = parseInt(document.getElementById("campo2").value);
    var r=campo1+campo2;

    alert("Resultado = "+r);
}
