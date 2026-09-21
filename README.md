<!DOCTYPE html>
<html>
<head>
    <title>My Dragon Game</title>

    <style>
        body {
            margin: 0;
            overflow: hidden;
            background: skyblue;
            font-family: Arial;
        }

        #game {
            width: 100vw;
            height: 100vh;

            display: flex;
            align-items: center;
            justify-content: center;

            flex-direction: column;
        }

        h1 {
            font-size: 60px;
            color: white;
            text-shadow: 0 4px 10px black;
        }

        button {
            padding: 20px 40px;
            font-size: 22px;
            cursor: pointer;
        }
    </style>
</head>

<body>

<div id="game">

    <h1>🐉 DRAGON REALMS</h1>

    <button onclick="startGame()">
        START GAME
    </button>

</div>

<script>

function startGame() {

    document.getElementById("game").innerHTML = `
        <h1>🐉 YOU ARE PLAYING!</h1>
        <p style="font-size:25px;color:white;">
            Your game is working.
        </p>
    `;

}

</script>

</body>
</html>
