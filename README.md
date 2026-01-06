<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChatGPT Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="chat-container">
        <header class="chat-header">
            <h2>ChatGPT Clone</h2>
        </header>

        <div class="chat-window" id="chatWindow">
            <div class="message bot">Hello! How can I help you today?</div>
        </div>

        <form class="chat-input" id="chatForm">
            <input type="text" id="userInput" placeholder="Type a message..." autocomplete="off">
            <button type="submit">Send</button>
        </form>
    </div>

    <script src="script.js"></script>
</body>
</html>


/* General body styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

/* Chat container */
.chat-container {
    width: 400px;
    max-width: 90%;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    display: flex;
    flex-direction: column;
    overflow: hidden;
}

/* Header */
.chat-header {
    background-color: #10a37f;
    color: white;
    padding: 15px;
    text-align: center;
}

/* Chat window */
.chat-window {
    flex: 1;
    padding: 15px;
    overflow-y: auto;
    background-color: #f0f0f0;
}

/* Messages */
.message {
    margin: 10px 0;
    padding: 10px 15px;
    border-radius: 20px;
    max-width: 80%;
    clear: both;
}

/* Bot message */
.message.bot {
    background-color: #e0e0e0;
    float: left;
}

/* User message */
.message.user {
    background-color: #10a37f;
    color: white;
    float: right;
}

/* Input area */
.chat-input {
    display: flex;
    border-top: 1px solid #ccc;
}

.chat-input input {
    flex: 1;
    padding: 15px;
    border: none;
    outline: none;
    font-size: 16px;
}

.chat-input button {
    background-color: #10a37f;
    color: white;
    border: none;
    padding: 0 20px;
    cursor: pointer;
    font-size: 16px;
    transition: 0.3s;
}

.chat-input button:hover {
    background-color: #0e8b6c;
}
