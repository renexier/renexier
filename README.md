<p align="center">
  <img src="https://raw.githubusercontent.com/renexier/renexier/main/renexier.png" />
</p>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Binary Rain</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
    }

    body{
        overflow:hidden;
        background:#000;
        font-family:monospace;
    }

    canvas{
        display:block;
    }

    .overlay{
        position:absolute;
        top:50%;
        left:50%;
        transform:translate(-50%,-50%);
        color:#00ff88;
        font-size:2rem;
        letter-spacing:4px;
        text-shadow:0 0 10px #00ff88;
        pointer-events:none;
        opacity:0.85;
    }
</style>
</head>

<body>

<canvas id="matrix"></canvas>

<script>
const canvas = document.getElementById("matrix");
const ctx = canvas.getContext("2d");

canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

const binary = "01";
const fontSize = 18;
const columns = canvas.width / fontSize;

const drops = [];

for(let x = 0; x < columns; x++){
    drops[x] = 1;
}

function draw(){

    // dark fading trail
    ctx.fillStyle = "rgba(0, 0, 0, 0.08)";
    ctx.fillRect(0, 0, canvas.width, canvas.height);

    ctx.fillStyle = "#00ff88";
    ctx.font = fontSize + "px monospace";

    for(let i = 0; i < drops.length; i++){

        const text = binary[Math.floor(Math.random() * binary.length)];

        ctx.fillText(
            text,
            i * fontSize,
            drops[i] * fontSize
        );

        // random reset for endless rain
        if(
            drops[i] * fontSize > canvas.height &&
            Math.random() > 0.975
        ){
            drops[i] = 0;
        }

        drops[i]++;
    }
}

setInterval(draw, 35);

window.addEventListener("resize", () => {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
});
</script>

</body>
</html>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Press+Start+2P&size=18&pause=1000&color=8A2BE2&center=true&vCenter=true&width=1000&lines=MAYANK+RANJAN;RENEXIER;CREATIVE+DESIGNER;ROBLOX+GAME+DEVELOPER;MOTION+GRAPHICS+ARTIST;BUILDING+INTERACTIVE+SYSTEMS" />
</h1>

<p align="center">

  <a href="https://mayank-portfolio.framer.website/">
    <img src="https://img.shields.io/badge/PORTFOLIO-111111?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>

  <a href="https://discord.gg/TpXBcNDJsw">
    <img src="https://img.shields.io/badge/DISCORD-111111?style=for-the-badge&logo=discord&logoColor=white"/>
  </a>

  <a href="https://youtube.com/@renexier-ytgame">
    <img src="https://img.shields.io/badge/YOUTUBE-111111?style=for-the-badge&logo=youtube&logoColor=white"/>
  </a>

  <a href="https://www.instagram.com/_mayank._r">
    <img src="https://img.shields.io/badge/INSTAGRAM-111111?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/mayank-r-15a449290">
    <img src="https://img.shields.io/badge/LINKEDIN-111111?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=renexier&label=PROFILE+VIEWS&color=111111&style=for-the-badge" />
</p>

---

# LIVE EXPERIENCES

<p align="center">

  <a href="https://renexier.github.io/Safari-musical-keys/">
    <img src="https://img.shields.io/badge/SAFARI_KEYS-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://renexier.github.io/RENE-Search-Ai/">
    <img src="https://img.shields.io/badge/RENE_SEARCH_AI-111111?style=for-the-badge&logo=github&logoColor=white"/>
</a>

  <a href="https://renexier.github.io/nixie-clock/">
    <img src="https://img.shields.io/badge/NIXIE_CLOCK-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://renexier.github.io/Galaxy-Audio-Room/">
    <img src="https://img.shields.io/badge/GALAXY_AUDIO_ROOM-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

</p>

---

## CUSTOM EXPERIENCES & EMBEDS

```yaml
custom_experiences:

  embeddable:
    - Interactive Websites
    - Audio Reactive Systems
    - Futuristic UI
    - Landing Page Visuals
    - Interactive Widgets

  services:
    - Creative Frontend Design
    - Cinematic Interfaces
    - Realtime Visual Systems
    - Interactive Experiences

  availability:
    status: OPEN
    commissions: ACTIVE
    collaborations: AVAILABLE
```

<p align="center">

  <a href="https://mayank-portfolio.framer.website/">
    <img src="https://img.shields.io/badge/HIRE_ME-8A2BE2?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>

  <a href="mailto:mayankranjan486@gmail.com">
    <img src="https://img.shields.io/badge/CONTACT-111111?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

</p>

---

# FEATURED PROJECTS

## Galaxy Audio Room X

A cinematic realtime 3D galaxy audio room featuring
live microphone audio visualization, reactive neon lighting,
cinematic mouse controlled camera movement, dynamic galaxy
effects, supernova click bursts and GPU accelerated rendering.

<p align="center">
  <a href="https://renexier.github.io/Galaxy-Audio-Room/">
    <img src="https://raw.githubusercontent.com/renexier/Galaxy-Audio-Room/main/preview.gif" width="900"/>
  </a>
</p>

<p align="center">

  <a href="https://renexier.github.io/Galaxy-Audio-Room/">
    <img src="https://img.shields.io/badge/OPEN_EXPERIENCE-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://github.com/renexier/Galaxy-Audio-Room">
    <img src="https://img.shields.io/badge/VIEW_REPOSITORY-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

</p>

---

## Safari Musical Keys

A playful virtual keyboard experiment that transforms
typing into an interactive audio visual playground with
animated animals, music feedback and reactive effects.

<p align="center">
  <a href="https://renexier.github.io/Safari-musical-keys/">
    <img src="https://raw.githubusercontent.com/renexier/Safari-musical-keys/main/preview.gif" width="900"/>
  </a>
</p>

<p align="center">

  <a href="https://renexier.github.io/Safari-musical-keys/">
    <img src="https://img.shields.io/badge/OPEN_WEBSITE-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://github.com/renexier/Safari-musical-keys">
    <img src="https://img.shields.io/badge/VIEW_REPOSITORY-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

</p>

---

## Interactive Nixie Clock

A cinematic retro futuristic nixie tube clock featuring
realistic glass reflections, live timezone detection,
ambient atmosphere and interactive lighting effects.

<p align="center">
  <a href="https://renexier.github.io/nixie-clock/">
    <img src="https://raw.githubusercontent.com/renexier/nixie-clock/main/preview.gif" width="900"/>
  </a>
</p>

<p align="center">

  <a href="https://renexier.github.io/nixie-clock/">
    <img src="https://img.shields.io/badge/OPEN_CLOCK-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://github.com/renexier/nixie-clock">
    <img src="https://img.shields.io/badge/VIEW_REPOSITORY-111111?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

</p>

---

# ABOUT

```yaml
name: Mayank Ranjan
alias: renexier

roles:
  - Creative Designer
  - Motion Graphics Artist
  - Video Editor
  - Roblox Developer
  - Web Designer

focus:
  - Interactive Experiences
  - Multiplayer Systems
  - Motion Design
  - Visual Identity
  - Creative Development
```

---

# STACK

<p align="center">
  <img src="https://skillicons.dev/icons?i=ps,ai,pr,ae,blender,figma,html,css,js,lua,vscode,github" />
</p>

---

# DESIGN STACK

```txt
◉ PREMIERE PRO
◉ AFTER EFFECTS
◉ PHOTOSHOP
◉ ILLUSTRATOR
◉ BLENDER
◉ CANVA
◉ ROBLOX STUDIO
◉ CHATGPT
◉ RUNWAY
◉ MIDJOURNEY
◉ LEONARDO AI
◉ ADOBE FIREFLY
```

---

# CURRENTLY BUILDING

```txt
► INTERACTIVE WEB EXPERIENCES
► ROBLOX MULTIPLAYER SYSTEMS
► MOTION DRIVEN INTERFACES
► EXPERIMENTAL UI CONCEPTS
► CREATIVE AUTOMATION WORKFLOWS
```

---

# STATS

<p align="center">
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api?username=renexier&show_icons=true&theme=radical&hide_border=true"/>

  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=renexier&layout=compact&theme=radical&hide_border=true"/>
</p>

---

# STREAK

<p align="center">
  <img src="https://streak-stats.demolab.com?user=renexier&theme=radical&hide_border=true" />
</p>

---

# ACTIVITY GRAPH

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=renexier&theme=tokyo-night&hide_border=true&bg_color=0D1117" />
</p>

---

# CONTRIBUTION SNAKE

<p align="center">
  <img src="https://raw.githubusercontent.com/renexier/renexier/output/github-contribution-grid-snake-dark.svg" />
</p>

---

# PHILOSOPHY

```txt
I BUILD INTERFACES THAT MOVE.
SYSTEMS THAT REACT.
VISUALS THAT STAY IN MEMORY.
```

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,100:0D1117&height=120&section=footer"/>
</p>
