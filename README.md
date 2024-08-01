# Praposal-website-
3 to 4 pages website with 'html', 'html 2', 'html 3'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proposal</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f5f5f5;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            color: #ff69b4;
        }
    </style>
</head>
<body>
    <h1>Welcome 🤗</h1>
    <p><a href="page2.html">Click here to continue</a></p>
</body>
</html>
</html2> <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jewelry and Pickup Lines</title>
    <style>
        body {
            background-color: #fffaf0;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        img {
            width: 200px;
            margin: 20px;
        }
        .pickup-line {
            font-size: 1.5em;
            margin: 20px;
        }
    </style>
</head>
<body>
    <h1>Here are some beautiful pieces for a beautiful you! 💍</h1>
    <div class="jewelry">
        <img src="earrings.jpg" alt="Earrings">
        <p class="pickup-line">"Are you a magician? Because whenever I look at you, everyone else disappears." 😍</p>
        <img src="necklace.jpg" alt="Necklace">
        <p class="pickup-line">"Do you have a map? I keep getting lost in your eyes." 💖</p>
    </div>
    <p><a href="page3.html">Click here to continue</a></p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proposal</title>
    <style>
        body {
            background-color: #ffe4e1;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .proposal {
            font-size: 2em;
            margin: 50px;
        }
        .buttons {
            display: flex;
            justify-content: center;
            margin-top: 50px;
        }
        .button {
            padding: 10px 20px;
            margin: 0 10px;
            font-size: 1.5em;
            border: none;
            cursor: pointer;
            transition: transform 0.2s;
        }
        .yes {
            background-color: #32cd32;
            color: white;
        }
        .no {
            background-color: #ff6347;
            color: white;
            position: absolute;
        }
    </style>
    <script>
        function moveButton() {
            const noButton = document.getElementById('noButton');
            noButton.style.top = `${Math.random() * (window.innerHeight - noButton.clientHeight)}px`;
            noButton.style.left = `${Math.random() * (window.innerWidth - noButton.clientWidth)}px`;
        }
    </script>
</head>
<body>
    <div class="proposal">
        "Will you be my girlfriend? 💕"
    </div>
    <div class="buttons">
        <button class="button yes">Yes</button>
        <button class="button no" id="noButton" onclick="moveButton()">No</button>
    </div>
</body>
</html>
