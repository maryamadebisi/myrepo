
<style>
    @import url("https://fonts.googleapis.com/css2?family=Noto+Serif+SC&display=swap");

    body {
        background-color: #0082c8;
    color: #ffffff;
    font-size: 30px;
    line-height: 30px;
    word-wrap: anywhere;
    font-family: "Noto Serif SC";  
    }
</style>

<head>

    <meta charset=”UTF-8″>

    <meta name=”viewport” content=”width=device-width, initial-scale=1.0″>

    <meta http-equiv=”X-UA-Compatible” content=”ie=edge”>

    <title>My Website [note to ethan]</title>

  </head>

<body>
    
</body>
    
<script>

    function coinToss() {
        let chance = Math.random()
        if (chance > 0.5) {
            document.body.innerText += ' i love you '
        } else {
            document.body.innerText += ' <3 '
        }
        requestAnimationFrame(coinToss)
    }

    coinToss()



</script>