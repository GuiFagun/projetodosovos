<html>
    <head>
        <title>Sua Receita</title>
    </head>
    <body>
        <style>
        body{
            background-image: url('https://motionarray.imgix.net/preview-823559-HMikwIGwBLF1UKee-large.jpg?w=660&q=60&fit=max&auto=format');
            background-repeat: no-repeat;
            background-size: cover;
            background-attachment: fixed;
        }
        h1,h3{
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            color: rgb(255, 229, 100);
            text-shadow: 1px 2px 2px rgb(74, 65, 44);
            text-align: center;
        }
        form{
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            font-size: larger;
            color: #3e3300;
            text-shadow: 1px 1px 1px cornsilk;
        }
        </style>
        <h1>Faça sua própria receita!</h1>
        <h3>Preencha os campos, mande uma imagem, e envie sua receita para nós!</h3>
        <hr>
        <h2>Insira aqui os detalhes da sua receita:</h2>
        <form>
            <label for="nome_receita">Nome da sua Receita:</label><br>
            <input id="nome_receita" type="text"><br>
            <label for="ingredientes">Ingredientes da receita:</label><br>
            <input id="ingredientes" type="text"><br>
            <label for="modo_de_preparo">Modo de Preparo:</label><br>
            <textarea name="modo_de_preparo" id="modo_de_preparo" cols="30" rows="30"></textarea><br>
            <label for="imagem">Coloque uma foto da sua receita!</label><br>
            <p style="font-size: small;"> &nbsp;</p>
            <input type="file" id="imagem"><br>
            <p>&nbsp;</p>
            <input type="submit">
        </form>
    </body>
</html>
