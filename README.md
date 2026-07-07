# test-site
testing
can yo hear it?
oh! this is very easy
um, okay Let's test a little bit

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>score up!!!</title>
    <style>
        body{
            margin:0;
            height:100vh;
            display:flex;
            justify-content:center;
            align-items:center;
            background:#222;
            color:white;
            font-family:Arial, sans-serif;
        }

        .box{
            text-align:center;
        }

        h1{
            font-size:50px;
            margin-bottom:20px;
        }

        button{
            padding:15px 40px;
            font-size:24px;
            border:none;
            border-radius:10px;
            cursor:pointer;
            background:#4CAF50;
            color:white;
            transition:.2s;
        }

        button:hover{
            transform:scale(1.05);
        }
    </style>
</head>
<body>

<div class="box">
    <h1 id="score">0</h1>
    <button id="btn">score up!!!</button>
</div>

<script>
let score = 0;

const scoreText = document.getElementById("score");
const btn = document.getElementById("btn");

btn.addEventListener("click", () => {
    score++;
    scoreText.textContent = score;
});

why is this dosen't work??
</script>

</body>
</html>
