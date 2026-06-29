# 🌿 A Note from the Creator

> *This app was born from a real need — a place that felt like a warm, quiet room just for you. No noise. No comparison. Just you and your growth.*
>
> *I built Girl, Breathe for women who are healing. For women who are learning to slow down and be gentle with themselves. For women who need a space that is entirely, completely their own.*
>
> *Every feature was chosen with love and intention. Every word was written as if I was writing it to myself.*

— Made by **Ta'Zahnae Matthews** with love 🌻
<svg width="100%" viewBox="0 0 680 320" role="img" xmlns="http://www.w3.org/2000/svg">
<title>Girl, Breathe — Sunflower Garden</title>
<desc>An animated sunflower garden with six sunflowers of different heights swaying gently, with floating petals and a warm golden sky background.</desc>

<defs>
  <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
    <stop offset="0%" stop-color="#1C0800"/>
    <stop offset="60%" stop-color="#3D1A00"/>
    <stop offset="100%" stop-color="#5C2A00"/>
  </linearGradient>
  <linearGradient id="ground" x1="0" y1="0" x2="0" y2="1">
    <stop offset="0%" stop-color="#2E5A08"/>
    <stop offset="100%" stop-color="#1A3204"/>
  </linearGradient>
  <radialGradient id="glow" cx="50%" cy="50%" r="50%">
    <stop offset="0%" stop-color="#F5C842" stop-opacity="0.18"/>
    <stop offset="100%" stop-color="#F5C842" stop-opacity="0"/>
  </radialGradient>
  <radialGradient id="sun" cx="50%" cy="50%" r="50%">
    <stop offset="0%" stop-color="#FFE888"/>
    <stop offset="100%" stop-color="#F5C842"/>
  </radialGradient>
  <style>
    .sway1 { animation: sway1 4s ease-in-out infinite; transform-origin: center bottom; }
    .sway2 { animation: sway2 5s ease-in-out infinite; transform-origin: center bottom; }
    .sway3 { animation: sway3 4.5s ease-in-out infinite; transform-origin: center bottom; }
    .sway4 { animation: sway4 3.8s ease-in-out infinite; transform-origin: center bottom; }
    .sway5 { animation: sway5 5.2s ease-in-out infinite; transform-origin: center bottom; }
    .sway6 { animation: sway6 4.2s ease-in-out infinite; transform-origin: center bottom; }
    .petal-float1 { animation: float1 9s ease-in-out infinite; }
    .petal-float2 { animation: float2 12s ease-in-out infinite 2s; }
    .petal-float3 { animation: float3 10s ease-in-out infinite 4s; }
    .petal-float4 { animation: float4 11s ease-in-out infinite 1s; }
    .sun-pulse { animation: pulse 6s ease-in-out infinite; }
    @keyframes sway1 { 0%,100%{transform:rotate(-2deg)} 50%{transform:rotate(2deg)} }
    @keyframes sway2 { 0%,100%{transform:rotate(1.5deg)} 50%{transform:rotate(-2.5deg)} }
    @keyframes sway3 { 0%,100%{transform:rotate(-1.8deg)} 50%{transform:rotate(2.2deg)} }
    @keyframes sway4 { 0%,100%{transform:rotate(2deg)} 50%{transform:rotate(-1.5deg)} }
    @keyframes sway5 { 0%,100%{transform:rotate(-2.5deg)} 50%{transform:rotate(1.8deg)} }
    @keyframes sway6 { 0%,100%{transform:rotate(1.2deg)} 50%{transform:rotate(-2deg)} }
    @keyframes float1 { 0%{transform:translate(0,0) rotate(0deg);opacity:0} 10%{opacity:0.7} 90%{opacity:0.3} 100%{transform:translate(40px,-180px) rotate(320deg);opacity:0} }
    @keyframes float2 { 0%{transform:translate(0,0) rotate(0deg);opacity:0} 10%{opacity:0.6} 90%{opacity:0.2} 100%{transform:translate(-50px,-200px) rotate(-280deg);opacity:0} }
    @keyframes float3 { 0%{transform:translate(0,0) rotate(0deg);opacity:0} 10%{opacity:0.5} 90%{opacity:0.3} 100%{transform:translate(30px,-160px) rotate(400deg);opacity:0} }
    @keyframes float4 { 0%{transform:translate(0,0) rotate(0deg);opacity:0} 10%{opacity:0.6} 90%{opacity:0.2} 100%{transform:translate(-35px,-190px) rotate(-350deg);opacity:0} }
    @keyframes pulse { 0%,100%{opacity:0.5} 50%{opacity:0.9} }
  </style>
</defs>

<rect width="680" height="320" fill="url(#sky)"/>
<circle cx="340" cy="70" r="90" fill="url(#glow)"/>
<circle class="sun-pulse" cx="340" cy="65" r="44" fill="url(#sun)" opacity="0.85"/>
<g opacity="0.5" stroke="#FFE888" stroke-width="1.5" stroke-linecap="round">
  <line x1="340" y1="10" x2="340" y2="2"/>
  <line x1="370" y1="18" x2="376" y2="12"/>
  <line x1="390" y1="42" x2="398" y2="38"/>
  <line x1="394" y1="72" x2="403" y2="72"/>
  <line x1="384" y1="96" x2="390" y2="102"/>
  <line x1="310" y1="18" x2="304" y2="12"/>
  <line x1="290" y1="42" x2="282" y2="38"/>
  <line x1="286" y1="72" x2="277" y2="72"/>
  <line x1="296" y1="96" x2="290" y2="102"/>
</g>
<rect x="0" y="270" width="680" height="50" fill="url(#ground)"/>
<ellipse cx="340" cy="270" rx="360" ry="12" fill="#234A06" opacity="0.6"/>
<ellipse class="petal-float1" cx="160" cy="240" rx="6" ry="3" fill="#F5C842" opacity="0" transform="rotate(-15 160 240)"/>
<ellipse class="petal-float2" cx="420" cy="250" rx="5" ry="2.5" fill="#FFE060" opacity="0" transform="rotate(20 420 250)"/>
<ellipse class="petal-float3" cx="280" cy="245" rx="5" ry="2.5" fill="#F5C842" opacity="0" transform="rotate(-8 280 245)"/>
<ellipse class="petal-float4" cx="510" cy="238" rx="6" ry="3" fill="#FFD700" opacity="0" transform="rotate(12 510 238)"/>

<g class="sway1" style="transform-origin:340px 270px">
  <rect x="336" y="130" width="8" height="140" rx="4" fill="#2E5A08"/>
  <ellipse cx="322" cy="210" rx="18" ry="9" fill="#3A6B0F" transform="rotate(-30 322 210)"/>
  <ellipse cx="360" cy="185" rx="18" ry="9" fill="#3A6B0F" transform="rotate(25 360 185)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(30 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(60 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(90 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(120 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#FFD700" transform="rotate(150 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#FFD700" transform="rotate(180 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#FFD700" transform="rotate(210 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(240 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(270 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#F5C842" transform="rotate(300 340 130)"/>
  <ellipse cx="340" cy="110" rx="10" ry="16" fill="#FFD700" transform="rotate(330 340 130)"/>
  <circle cx="340" cy="130" r="20" fill="#3D1F00"/>
  <circle cx="340" cy="130" r="16" fill="#5C2A00"/>
  <circle cx="340" cy="130" r="10" fill="#3D1F00"/>
</g>

<g class="sway2" style="transform-origin:180px 270px">
  <rect x="177" y="155" width="7" height="115" rx="3.5" fill="#2E5A08"/>
  <ellipse cx="166" cy="228" rx="15" ry="8" fill="#3A6B0F" transform="rotate(-28 166 228)"/>
  <ellipse cx="196" cy="206" rx="15" ry="8" fill="#3A6B0F" transform="rotate(22 196 206)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(30 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#FFD700" transform="rotate(60 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(90 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(120 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#FFD700" transform="rotate(150 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(180 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(210 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#FFD700" transform="rotate(240 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(270 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#F5C842" transform="rotate(300 180 155)"/>
  <ellipse cx="180" cy="137" rx="9" ry="14" fill="#FFD700" transform="rotate(330 180 155)"/>
  <circle cx="180" cy="155" r="17" fill="#3D1F00"/>
  <circle cx="180" cy="155" r="13" fill="#5C2A00"/>
  <circle cx="180" cy="155" r="8" fill="#3D1F00"/>
</g>

<g class="sway3" style="transform-origin:500px 270px">
  <rect x="497" y="150" width="7" height="120" rx="3.5" fill="#2E5A08"/>
  <ellipse cx="485" cy="220" rx="15" ry="8" fill="#3A6B0F" transform="rotate(-25 485 220)"/>
  <ellipse cx="516" cy="200" rx="15" ry="8" fill="#3A6B0F" transform="rotate(28 516 200)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#FFD700"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(30 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(60 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#FFD700" transform="rotate(90 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(120 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(150 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#FFD700" transform="rotate(180 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(210 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(240 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#FFD700" transform="rotate(270 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(300 500 150)"/>
  <ellipse cx="500" cy="132" rx="9" ry="14" fill="#F5C842" transform="rotate(330 500 150)"/>
  <circle cx="500" cy="150" r="17" fill="#3D1F00"/>
  <circle cx="500" cy="150" r="13" fill="#5C2A00"/>
  <circle cx="500" cy="150" r="8" fill="#3D1F00"/>
</g>

<g class="sway4" style="transform-origin:72px 270px">
  <rect x="69" y="195" width="6" height="75" rx="3" fill="#2E5A08"/>
  <ellipse cx="60" cy="244" rx="12" ry="6" fill="#3A6B0F" transform="rotate(-22 60 244)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#FFD700" transform="rotate(36 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842" transform="rotate(72 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842" transform="rotate(108 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#FFD700" transform="rotate(144 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842" transform="rotate(180 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842" transform="rotate(216 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#FFD700" transform="rotate(252 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842" transform="rotate(288 72 195)"/>
  <ellipse cx="72" cy="180" rx="7" ry="11" fill="#F5C842" transform="rotate(324 72 195)"/>
  <circle cx="72" cy="195" r="13" fill="#3D1F00"/>
  <circle cx="72" cy="195" r="10" fill="#5C2A00"/>
  <circle cx="72" cy="195" r="6" fill="#3D1F00"/>
</g>

<g class="sway5" style="transform-origin:608px 270px">
  <rect x="605" y="200" width="6" height="70" rx="3" fill="#2E5A08"/>
  <ellipse cx="618" cy="246" rx="12" ry="6" fill="#3A6B0F" transform="rotate(24 618 246)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#FFD700"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(36 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(72 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#FFD700" transform="rotate(108 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(144 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(180 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#FFD700" transform="rotate(216 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(252 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(288 608 200)"/>
  <ellipse cx="608" cy="185" rx="7" ry="11" fill="#F5C842" transform="rotate(324 608 200)"/>
  <circle cx="608" cy="200" r="13" fill="#3D1F00"/>
  <circle cx="608" cy="200" r="10" fill="#5C2A00"/>
  <circle cx="608" cy="200" r="6" fill="#3D1F00"/>
</g>

<g class="sway6" style="transform-origin:255px 270px">
  <rect x="252" y="172" width="7" height="98" rx="3.5" fill="#2E5A08"/>
  <ellipse cx="241" cy="238" rx="14" ry="7" fill="#3A6B0F" transform="rotate(-26 241 238)"/>
  <ellipse cx="270" cy="218" rx="13" ry="7" fill="#3A6B0F" transform="rotate(20 270 218)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#FFD700" transform="rotate(30 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(60 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(90 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#FFD700" transform="rotate(120 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(150 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(180 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#FFD700" transform="rotate(210 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(240 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(270 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#FFD700" transform="rotate(300 255 172)"/>
  <ellipse cx="255" cy="155" rx="8" ry="13" fill="#F5C842" transform="rotate(330 255 172)"/>
  <circle cx="255" cy="172" r="16" fill="#3D1F00"/>
  <circle cx="255" cy="172" r="12" fill="#5C2A00"/>
  <circle cx="255" cy="172" r="7" fill="#3D1F00"/>
</g>

<rect x="0" y="278" width="680" height="42" fill="#1E3C04" opacity="0.5"/>
<text x="340" y="305" text-anchor="middle" font-family="Georgia, serif" font-size="15" font-style="italic" fill="#F5C842" opacity="0.85">Girl, Breathe. — Sunflower Sanctuary</text>
</svg>
