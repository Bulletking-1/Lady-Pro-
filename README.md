
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Little Message ❤️</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #250018, #751b42, #190d25);
    font-family: Georgia, serif;
    color: white;
    padding: 20px;
}

.card {
    max-width: 430px;
    width: 100%;
    padding: 35px 25px;
    text-align: center;
    background: rgba(255,255,255,0.10);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 22px;
    box-shadow: 0 15px 45px #0005;
    backdrop-filter: blur(12px);
}

.heart {
    font-size: 55px;
    animation: beat 1.2s infinite;
}

@keyframes beat {
    50% { transform: scale(1.2); }
}

h1 {
    color: #ffb6ce;
}

p {
    line-height: 1.8;
    font-size: 16px;
}

button {
    margin-top: 20px;
    padding: 13px 25px;
    border: none;
    border-radius: 30px;
    background: #ff8eaf;
    color: #351022;
    font-size: 15px;
    font-weight: bold;
    cursor: pointer;
}

#message {
    display: none;
    margin-top: 25px;
    animation: fade 2s ease;
}

@keyframes fade {
    from { opacity: 0; }
    to { opacity: 1; }
}

.footer {
    margin-top: 30px;
    font-size: 12px;
    color: #e9bfd0;
}
</style>
</head>

<body>

<div class="card">
    <div class="heart">❤️</div>

    <h1>Something From My Heart</h1>

    <p>
        Sometimes two people can care about each other
        but still understand love differently.
    </p>

    <p>
        I believe love should come with patience,
        understanding, trust and genuine intentions.
    </p>

    <button onclick="revealMessage()">
        Open my heart ❤️
    </button>

    <div id="message">
        <h2>One Last Thought...</h2>

        <p>
            I never wanted perfection.
            I only wanted something genuine.
            Perhaps we both have lessons to learn,
            and sometimes the most mature thing
            we can do is accept things as they are.
        </p>

        <p>
            Thank you for the moments we shared.
            I wish you nothing but happiness,
            peace and beautiful things in life.
        </p>

        <h2>Take care. ❤️</h2>
    </div>

    <div class="footer">
        Written with sincerity.
    </div>
</div>

<script>
function revealMessage() {
    document.getElementById("message").style.display = "block";
}
</script>

</body>
</html>
