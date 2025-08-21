<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>margin</title>
     <style>
        html{
            font-size:40px;
        }
        .a{ /* viết chung */
            width:75px;
            height:75px;
            background:violet;  
            float: left; 
            margin-left: 10px;
            margin-bottom:10px;           
            margin-top:10px;          
            margin-right: 10px;
        }
        .b{ /*viế tắt */
            width:75px;
            height:75px;
            background:rgb(140, 181, 93);
            float: left;
            margin: 10px 10px 10px 10px;
        }
     </style>
</head>
<body>
    <div class="a"></div>
    <div class="b"></div>
</body>
</html> 
