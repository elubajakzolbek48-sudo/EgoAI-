# EgoAI-<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>EgoAI</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0b0b0f;
            color: white;
            height: 100vh;
            overflow: hidden;
        }

        .app {
            display: flex;
            flex-direction: column;
            height: 100vh;
        }

        .header {
            padding: 18px 20px;
            text-align: center;
            font-size: 26px;
            font-weight: bold;
            border-bottom: 1px solid #24242c;
        }

        .header span {
            color: #8b5cf6;
        }

        .chat {
            flex: 1;
            overflow-y: auto;
            padding: 20px;
        }

        .welcome {
            text-align: center;
            margin-top: 20vh;
        }

        .welcome h1 {
            font-size: 32px;
            margin-bottom: 10px;
        }

        .welcome p {
            color: #aaa;
            font-size: 16px;
        }

        .message {
            max-width: 85%;
            padding: 13px 16px;
            margin-bottom: 12px;
            border-radius: 16px;
            line-height: 1.5;
            white-space: pre-wrap;
        }

        .user {
            background: #6d28d9;
            margin-left: auto;
            border-bottom-right-radius: 4px;
        }

        .ai {
            background: #1c1c24;
            margin-right: auto;
            border-bottom-left-radius: 4px;
        }

        .bottom {
            padding: 12px;
            border-top: 1px solid #24242c;
            background: #0b0b0f;
        }

        .input-area {
            display: flex;
            gap: 8px;
            background: #18181f;
            padding: 8px;
            border-radius: 18px;
        }

        .plus {
            width: 45px;
            height: 45px;
            border: none;
            border-radius: 50%;
            background: #292933;
            color: white;
            font-size: 25px;
            cursor: pointer;
        }

        textarea {
            flex: 1;
            resize: none;
            border: none;
            outline: none;
            background: transparent;
            color: white;
            font-size: 16px;
            padding: 12px 5px;
            height: 45px;
        }

        .send {
            width: 45px;
            height: 45px;
            border: none;
            border-radius: 50%;
            background: #8b5cf6;
            color: white;
            font-size: 20px;
            cursor: pointer;
        }

        .menu {
            display: none;
            position: absolute;
            bottom: 75px;
            left: 12px;
            background: #202028;
            border-radius: 14px;
            padding: 8px;
            width: 190px;
            box-shadow: 0 10px 30px #000;
        }

        .menu button {
            width: 100%;
            padding: 12px;
            margin: 3px 0;
            border: none;
            border-radius: 10px;
            background: transparent;
            color: white;
            text-align: left;
            cursor: pointer;
        }

        .menu button:hover {
            background: #30303a;
        }
    </style>
</head>

<body>

<div class="app">

    <div class="header">
        Ego<span>AI</span>
    </div>

    <div class="chat" id="chat">

        <div class="welcome" id="welcome">
            <h1>Сәлем! 👋</h1>
            <p>Мен EgoAI. Маған кез келген сұрақ қойып көр.</p>
        </div>

    </div>

    <div class="bottom">

        <div class="menu" id="menu">
            <button onclick="createImage()">
                🖼️ Сурет жасау
            </button>

            <button onclick="alert('Бұл функция кейін қосылады.')">
                📎 Файл қосу
            </button>
        </div>

        <div class="input-area">

            <button class="plus" onclick="toggleMenu()">
                +
            </button>

            <textarea
                id="input"
                placeholder="EgoAI-ға жазыңыз..."
            ></textarea>

            <button class="send" onclick="sendMessage()">
                ➤
            </button>

        </div>

    </div>

</div>

<script>

    const input = document.getElementById("input");
    const chat = document.getElementById("chat");
    const welcome = document.getElementById("welcome");
    const menu = document.getElementById("menu");

    function toggleMenu() {

        if (menu.style.display === "block") {
            menu.style.display = "none";
        } else {
            menu.style.display = "block";
        }

    }

    function addMessage(text, type) {

        if (welcome) {
            welcome.style.display = "none";
        }

        const message = document.createElement("div");

        message.className = "message " + type;

        message.textContent = text;

        chat.appendChild(message);

        chat.scrollTop = chat.scrollHeight;

    }

    function sendMessage() {

        const text = input.value.trim();

        if (text === "") {
            return;
        }

        addMessage(text, "user");

        input.value = "";

        setTimeout(function() {

            let answer = "Мен әзірге демо-нұсқамын. Нақты AI жүйесі серверге қосылғаннан кейін жұмыс істейді. 🤖";

            if (
                text.toLowerCase().includes("сәлем") ||
                text.toLowerCase().includes("салам")
            ) {

                answer = "Сәлем! 👋 Мен EgoAI-мын. Сенімен сөйлесуге дайынмын!";

            }

            addMessage(answer, "ai");

        }, 700);

    }

    function createImage() {

        menu.style.display = "none";

        addMessage(
            "🖼️ Сурет жасау функциясы әзірге демо режимінде. Нақты сурет генераторы кейін қосылады.",
            "ai"
        );

    }

    input.addEventListener("keydown", function(event) {

        if (event.key === "Enter" && !event.shiftKey) {

            event.preventDefault();

            sendMessage();

        }

    });

</script>

</body>
</html>
