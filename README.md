# squares-hover
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>shapes game</title>
    <style>*{
        margin:0% ;
        padding: 0%;
    }
    html,body{
        height: 100%;
        width: 100%;
    }
    #main{
        
        height:100%;
        width:100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    h1{
        font-weight: normal;
    }
    .shape{
        
        margin-left: 10px;
        margin-top: 10px;
        border: 2px solid black;
        height: 200px;
        width:200px ;
        background-color: rgb(255, 255, 255);
        align-items: center;
        justify-content: center;
        display: flex;
        font-family: 'Gill Sans';
    }
    #circle{
        border-radius: 50%;
        
    }
    #circle:hover{
        background-color: green;
    }
    #daimond{
        rotate: 45deg;
    margin-top:50px ;
    
    }
    #daimond:hover{
        background-color: blue;
    }
    #daimond h1{
        rotate:-45deg;
    }
    #square:hover{
        background-color: red;
        
    }
    </style>
</head>
<body>
    <div id="main">
        <div id="box">
            <div id="square"class="shape"><h1>1</h1></div>
        <div id="daimond"class="shape"><h1>2</h1></div>
        </div>
        <div id="circle"class="shape"><h1>3</h1></div>
    </div>
        
</body>
</html>
