<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container{
            height: 1490px;
            width: 1475px;
            grid-template-columns: 200px 300px 300px 200px 200px 200px;
            grid-template-rows: 200px 300px 300px 200px 200px 200px;
            background-color: rgb(0, 0, 0);
            gap: 15px;
            display: grid;
            
        }
        .color{
            background-color: white;
        }
        .puti {
            grid-column: span 2;
        }
        .puti4{
            grid-column: span 2;
        }
        .yellow , .yellow1{
            background-color: yellow;
            grid-column: span 2;
        }
        .pula{
            background-color: red;
            grid-column: span 2;
            grid-row: span 2;
        }
        .putingputi{
            grid-row: span 3;
        }
        .putingputiputi{
            grid-row: span 2;
        }
        .itim{
            background-color: black;
            grid-row: span 2;

        }
        .yellow2{
            grid-row: span 2;
            background-color: yellow;
        }
        .blue{
            grid-column: span 2;
            grid-row: span 2;
            background-color: blue;
        }
        .itimnaitim{
            background-color: black;
        }
        .pulangpula{
            grid-row: span 2;
            background-color: red;
        }
        
    </style>
</head>
<body>

    <div class="container">
        <div class="color puti"></div>
        <div class="color "></div>
        <div class="color yellow"></div>

        <div class="color "></div>
        <div class="color "></div>
        <div class="color pula"></div>

        <div class="color yellow1"></div>
        <div class="color putingputi"></div>
        <div class="color putingputiputi"></div>
        <div class="color "></div>
        <div class="color "></div>

        <div class="color negro"></div>
        <div class="color "></div>
        <div class="color maputi4"></div>

        <div class="color yellow2"></div>
        <div class="color "></div>
        <div class="color blue"></div>

        <div class="color pulangkulaydugo"></div>
        <div class="color "></div>
        <div class="color darkBlack"></div>
    </div>

</body>
</html>