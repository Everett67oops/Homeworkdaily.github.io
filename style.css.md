/* Homework Daily | style.css */

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 20px;
    text-align: center;
}

header {
    margin-bottom: 20px;
}

h1 {
    font-size: 2em;
    color: #333;
}

.game-container, .calculator {
    background: white;
    padding: 20px;
    margin: 0 auto;
    max-width: 400px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

select, button, input[type="number"], input[type="text"] {
    margin: 10px 0;
    padding: 10px;
    font-size: 1em;
    width: 80%;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.question {
    font-size: 1.5em;
    margin: 20px 0;
}

nav a {
    margin: 0 10px;
    text-decoration: none;
    color: #0077cc;
    font-weight: bold;
}

button {
    background-color: #4caf50;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

iframe {
    width: 100%;
    height: 400px;
    margin-top: 20px;
    border: none;
    border-radius: 10px;
}
