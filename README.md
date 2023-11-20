# examen_PP.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <title>Examen Aplicaciones web</title>
</head>
<body>
    <h1> APLICACIONES WEB EXAMEN - CESAR NAVAS</h1>
    <section class="flex-container">
        <div class="caja">
            Caja 1
        </div>
        <div class="caja">
            Caja 2
        </div>
        <div class="caja">
            Caja 3
        </div>
        <div class="caja">
            Caja 4
        </div>
    </section>
</body>
</html>
body { 
    background-color: #C795E3;
}
.flex-container{
    border: 1px solid black; 
    background: #ffffff;
    padding: 20px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.caja {
    border: 1px solid #000000;
    background-color: white;
    color: black;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    width: 150px;
    height: 150px;
    line-height: 150px;
    text-align: center;
    margin: 3px;
}
