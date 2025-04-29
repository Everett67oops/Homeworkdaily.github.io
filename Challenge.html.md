<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homework Daily | Fun Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        header {
            margin-bottom: 20px;
        }
        h1 {
            font-size: 2em;
            color: #4caf50;
        }
        .fun-container {
            background: #f9f9f9;
            padding: 20px;
            margin: 0 auto;
            max-width: 800px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }
        iframe {
            width: 100%;
            height: 400px;
            margin-top: 20px;
            border: none;
            border-radius: 10px;
        }
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to the Fun Portal!</h1>
</header>

<div class="fun-container">
    <button onclick="loadGame('https://scratch.mit.edu/projects/651731558/embed')">Geometry Dash Clone</button>
    <button onclick="loadGame('https://scratch.mit.edu/projects/581064075/embed')">Block Blast Clone</button>
    <button onclick="loadMusic('https://open.spotify.com/embed/playlist/37i9dQZF1DXcBWIGoYBM5M')">Top 40 Clean Music</button>
    <button onclick="loadMusic('https://open.spotify.com/embed/playlist/37i9dQZF1DX4dyzvuaRJ0n')">Top 40 Normal Music</button>

    <iframe id="funFrame" src=""></iframe>
</div>

<script>
    function loadGame(url) {
        document.getElementById('funFrame').src = url;
    }

    function loadMusic(url) {
        document.getElementById('funFrame').src = url;
    }

    document.addEventListener('keydown', function(e) {
        if (e.shiftKey && e.key === 'H') {
            alert('Fun portal hidden! Returning to safe homepage.');
            window.location.href = 'index.html';
        }
    });
</script>

</body>
</html>
