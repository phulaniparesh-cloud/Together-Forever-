<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Sahil 💙 Riya 💖</title>

<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(to right, #e0f2fe, #fce7f3);
    overflow: hidden;
    font-family: 'Segoe UI', sans-serif;
}

/* Top Message */
.message {
    position: absolute;
    top: 40px;
    font-size: 28px;
    font-weight: bold;
    color: #ff4d6d;
    text-shadow: 0 0 10px rgba(255, 77, 109, 0.4);
    animation: fadeIn 2s ease-in-out;
}

/* Container */
.container {
    display: flex;
    align-items: center;
    gap: 40px;
    position: relative;
    z-index: 2;
}

/* Doll */
.doll {
    text-align: center;
    position: relative;
    animation: float 4s ease-in-out infinite;
}

/* Head */
.head {
    width: 90px;
    height: 100px;
    background: #ffe0bd;
    border-radius: 50%;
    position: relative;
    margin: auto;
    box-shadow: inset -5px -8px rgba(0,0,0,0.1);
}

/* Hair */
.hair-boy {
    width: 95px;
    height: 50px;
    background: #111;
    position: absolute;
    top: -10px;
    left: -2px;
    border-radius: 50% 50% 30% 30%;
}

.hair-girl {
    width: 110px;
    height: 120px;
    background: #333;
    position: absolute;
    top: -20px;
    left: -10px;
    border-radius: 60% 60% 40% 40%;
    z-index: -1;
}

/* Eyes */
.eye {
    width: 14px;
    height: 14px;
    background: black;
    border-radius: 50%;
    position: absolute;
    top: 40px;
    animation: blink 5s infinite;
}
.eye.left { left: 25px; }
.eye.right { right: 25px; }

.eye::after {
    content: '';
    width: 5px;
    height: 5px;
    background: white;
    border-radius: 50%;
    position: absolute;
    top: 2px;
    left: 2px;
}

/* Smile */
.smile {
    width: 35px;
    height: 18px;
    border-bottom: 3px solid #333;
    border-radius: 0 0 25px 25px;
    position: absolute;
    top: 60px;
    left: 27px;
}

/* Body */
.body {
    width: 110px;
    height: 140px;
    border-radius: 30px;
    margin-top: 10px;
    position: relative;
}

/* Clothes */
.hoodie {
    background: linear-gradient(#4facfe, #2563eb);
    box-shadow: 0 10px 25px rgba(0,0,255,0.3);
}

.dress {
    background: linear-gradient(#ff9a9e, #ff4d6d);
    box-shadow: 0 10px 25px rgba(255,0,100,0.3);
    border-radius: 50% 50% 30% 30%;
}

/* Arms */
.arm {
    width: 20px;
    height: 90px;
    background: #ffe0bd;
    position: absolute;
    top: 10px;
    border-radius: 20px;
}

/* Holding hands */
.blue .arm.right {
    right: -15px;
    transform: rotate(35deg);
}

.pink .arm.left {
    left: -15px;
    transform: rotate(-35deg);
}

/* Hand link */
.hand-link {
    width: 40px;
    height: 10px;
    background: #ffe0bd;
    position: absolute;
    top: 160px;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 10px;
}

/* Legs */
.leg {
    width: 20px;
    height: 60px;
    background: #ffe0bd;
    position: absolute;
    bottom: -50px;
    border-radius: 20px;
}
.leg.left { left: 20px; }
.leg.right { right: 20px; }

/* Names */
.name {
    margin-top: 70px;
    font-size: 20px;
    font-weight: bold;
}

/* Floating */
@keyframes float {
    0%,100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
}

/* Blink */
@keyframes blink {
    0%, 92%, 100% { height: 14px; }
    95% { height: 2px; }
}

/* Fade message */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
}

/* Hearts (behind dolls) */
.heart {
    position: absolute;
    font-size: 18px;
    animation: floatHearts 7s linear infinite;
    z-index: 1;
    opacity: 0.8;
}

@keyframes floatHearts {
    0% { transform: translateY(0); opacity: 0; }
    20% { opacity: 1; }
    100% { transform: translateY(-400px); opacity: 0; }
}

</style>
</head>

<body>

<div class="message">💞 Together Forever 💞</div>

<div class="container">

    <!-- Paresh -->
    <div class="doll blue">
        <div class="head">
            <div class="hair-boy"></div>
            <div class="eye left"></div>
            <div class="eye right"></div>
            <div class="smile"></div>
        </div>
        <div class="body hoodie">
            <div class="arm right"></div>
            <div class="leg left"></div>
            <div class="leg right"></div>
        </div>
        <div class="name">Sahil 💙</div>
    </div>

    <div class="hand-link"></div>

    <!-- Avantika -->
    <div class="doll pink">
        <div class="head">
            <div class="hair-girl"></div>
            <div class="eye left"></div>
            <div class="eye right"></div>
            <div class="smile"></div>
        </div>
        <div class="body dress">
            <div class="arm left"></div>
            <div class="leg left"></div>
            <div class="leg right"></div>
        </div>
        <div class="name">Riya 💖</div>
    </div>

</div>

<script>
function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "💖";

    heart.style.left = Math.random() * window.innerWidth + "px";
    heart.style.top = "100%";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 7000);
}

/* Reduced frequency */
setInterval(createHeart, 900);
</script>

</body>
</html>
