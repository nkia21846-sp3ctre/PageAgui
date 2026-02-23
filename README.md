index.html<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agüizotes Tour | Mystical Nicaragua</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Uncial+Antiqua&display=swap" rel="stylesheet">

<style>

body {
    margin: 0;
    padding: 0;
    background: radial-gradient(circle at center, #1a0000 0%, #000000 70%);
    color: #ffffff;
    font-family: 'Cinzel', serif;
    overflow-x: hidden;
}

.overlay {
    position: fixed;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.7);
}

header {
    text-align: center;
    padding: 120px 20px 40px 20px;
}

h1 {
    font-family: 'Uncial Antiqua', cursive;
    font-size: 3.5rem;
    color: #B11226;
    text-shadow: 0 0 20px #8B0000, 0 0 40px #B11226;
    letter-spacing: 3px;
}

.tagline {
    font-size: 1.2rem;
    margin-top: 20px;
    color: #cccccc;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

button {
    margin-top: 40px;
    padding: 15px 40px;
    background: linear-gradient(45deg, #8B0000, #B11226);
    border: none;
    color: white;
    font-size: 1rem;
    cursor: pointer;
    transition: 0.4s;
    box-shadow: 0 0 20px #8B0000;
}

button:hover {
    transform: scale(1.05);
    box-shadow: 0 0 30px #B11226;
}

.section {
    padding: 80px 20px;
    text-align: center;
}

.section h2 {
    color: #B11226;
    font-size: 2rem;
    margin-bottom: 20px;
}

.footer {
    text-align: center;
    padding: 40px;
    background: #0a0000;
    font-size: 0.9rem;
    color: #777;
}

@keyframes pulse {
    0% { text-shadow: 0 0 10px #8B0000; }
    50% { text-shadow: 0 0 25px #B11226; }
    100% { text-shadow: 0 0 10px #8B0000; }
}

h1 {
    animation: pulse 4s infinite;
}

</style>
</head>

<body>

<div class="overlay"></div>

<header>
    <h1>Agüizotes Tour</h1>
    <p class="tagline">
        Walk the land where volcanoes breathe, 
        where ancient rituals echo in the fire, 
        and where history whispers through shadow.
    </p>
    <button onclick="window.location.href='#experience'">Enter the Journey</button>
</header>

<section class="section" id="experience">
    <h2>Fire. Myth. Memory.</h2>
    <p>
        Discover Nicaragua beyond tourism.  
        Explore sacred volcanoes, colonial legends, 
        and the hidden chronicles of Spanish conquest.
    </p>
</section>

<section class="section">
    <h2>The Agüizotes Experience</h2>
    <p>
        Mystical storytelling.  
        Night volcano rituals.  
        Indigenous cosmology.  
        Colonial myths and pirate legends.
    </p>
</section>

<div class="footer">
    © 2026 Agüizotes Tour | Mystical Origins of Nicaragua
</div>

</body>
</html>
