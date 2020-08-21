<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Webpage</title>
    <link rel="Shortcut icon" href="../images/Shortcut.png">
    <link rel="stylesheet" href="../style.css">
</head>
<body>
    <header class="fixed-bar"> <h1 class="page-title">Mike's World</h1> </header>
    <nav>
        <ul class="navigation">
            <li><a href="../index.html">Home</a></li>
            <li>Contact</li>
        </ul>
    </nav>
    <main >
        <form class="form">
            <label for="input-name">Name</label>
            <input type="text" name="name" class="form-input" id="input-name" oninput= "checkButton()">
            <label for="input-mail">Mail</label>
            <input type="text" name="email" class="form-input" id="input-mail">
            <label for="input-message">Your Message</label>
            <textarea name="message" cols="30" rows="10" class="form-input" id="input-message"></textarea>
            <button type="submit" class="submit-button" disabled>Submit</button>
        </form>
    </main>
    <script src="main.js"></script>
</body>
</html>
