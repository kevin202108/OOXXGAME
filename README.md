<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OOXX Game</title>
    <style>
        .box {width: 453px; margin: 20px auto;}
        .box tr td{ width: 150px; height: 150px;
        border: 1px solid #000; color: #333; font-size: 20px;
        line-height: 100px; text-align: center;}
        .btn {
            width:100px; hight:100px; border-radius:50px; font-size: 30px;
        }
    </style>
</head>
<body>
    <table class="box">
        <tr>
            <td><button onclick="btn(0,0)" id="btn00" class="btn">click</button></td>
            <td><button onclick="btn(0,1)" id="btn01" class="btn">click</button></td>
            <td><button onclick="btn(0,2)" id="btn02" class="btn">click</button></td>
        </tr>
        <tr>
            <td><button onclick="btn(1,0)" id="btn10" class="btn">click</button></td>
            <td><button onclick="btn(1,1)" id="btn11" class="btn">click</button></td>
            <td><button onclick="btn(1,2)" id="btn12" class="btn">click</button></td>
        </tr>
        <tr>
            <td><button onclick="btn(2,0)" id="btn20" class="btn">click</button></td>
            <td><button onclick="btn(2,1)" id="btn21" class="btn">click</button></td>
            <td><button onclick="btn(2,2)" id="btn22" class="btn">click</button></td>
        </tr>
    </table>
    <button onclick="clearAll()" class="btn">clear</button>
    <script src="main.js"></script>
</body>
</html>
