<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outlook Inloggen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f3f3f3;
        }
        .login-container {
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            width: 300px;
            text-align: center;
        }
        .login-container img {
            width: 150px;
            margin-bottom: 20px;
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #0078d4;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #005a9e;
        }
        .warning {
            color: red;
            margin-top: 15px;
            font-weight: bold;
        }
    </st
</head>
<body>yle>
    <div class="login-container">
        <img src="https://logincdn.msftauth.net/mslogo/microsoft_logo.svg" alt="Microsoft Logo">
        <h2>Inloggen</h2>
        <input type="text" placeholder="E-mailadres of telefoonnummer" id="email">
        <input type="password" placeholder="Wachtwoord" id="password">
        <button onclick="showWarning()">Volgende</button>
        <p class="warning" id="warning" style="display:none;">LET OP! Dit is een demo phishingpagina.</p>
    </div>

    <script>
        function showWarning() {
            document.getElementById('warning').style.display = 'block';
        }
    </script>
</body>
</html>
# hoornbeeck
