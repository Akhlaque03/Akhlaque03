<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="300" viewBox="0 0 1200 300">
  <defs>

    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%">
        <animate attributeName="stop-color"
          values="#020617;#0f172a;#172554;#1e1b4b;#2e1065;#450a0a;#052e16;#083344;#020617"
          dur="9s" repeatCount="indefinite"/>
      </stop>

      <stop offset="50%">
        <animate attributeName="stop-color"
          values="#1e3a8a;#4c1d95;#7c2d12;#991b1b;#be123c;#065f46;#155e75;#4338ca;#1e3a8a"
          dur="9s" repeatCount="indefinite"/>
      </stop>

      <stop offset="100%">
        <animate attributeName="stop-color"
          values="#312e81;#7e22ce;#9f1239;#dc2626;#ea580c;#16a34a;#0891b2;#6366f1;#312e81"
          dur="9s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

  </defs>

  <!-- Animated Background -->
  <rect width="1200" height="300" rx="35" fill="url(#bg)"/>

  <!-- Moving Shapes -->
  <circle cx="100" cy="50" r="120" fill="#ffffff" opacity=".04">
    <animate attributeName="cx"
      values="100;1100;100"
      dur="9s" repeatCount="indefinite"/>
  </circle>

  <circle cx="1100" cy="250" r="160" fill="#ffffff" opacity=".035">
    <animate attributeName="cy"
      values="250;50;250"
      dur="9s" repeatCount="indefinite"/>
  </circle>

  <!-- Main Heading -->
  <text x="600" y="125"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="44"
        font-weight="700"
        filter="url(#glow)">

    <tspan fill="#ffffff">Hi 👋, </tspan>

    <tspan>
      <animate attributeName="fill"
        values="#ff3b3b;#f97316;#facc15;#22c55e;#06b6d4;#3b82f6;#8b5cf6;#ec4899;#ffffff;#ff3b3b"
        dur="9s" repeatCount="indefinite"/>
      I'm Akhlaque Alam
    </tspan>

  </text>

  <!-- Animated Line -->
  <rect x="410" y="155" width="380" height="3" rx="2">
    <animate attributeName="fill"
      values="#ff3b3b;#f97316;#facc15;#22c55e;#06b6d4;#3b82f6;#8b5cf6;#ec4899;#ff3b3b"
      dur="9s" repeatCount="indefinite"/>

    <animate attributeName="width"
      values="380;500;380"
      dur="2s" repeatCount="indefinite"/>

    <animate attributeName="x"
      values="410;350;410"
      dur="2s" repeatCount="indefinite"/>
  </rect>

  <!-- Subtitle -->
  <text x="600" y="205"
        text-anchor="middle"
        font-family="Fira Code, monospace"
        font-size="22"
        font-weight="500"
        fill="#34d399">
    Aspiring Data Scientist
  </text>

  <!-- Bottom Text -->
  <text x="600" y="242"
        text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="14"
        letter-spacing="3"
        fill="#ffffff"
        opacity=".8">
    DATA • MACHINE LEARNING • ANALYTICS
  </text>

</svg>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=1000&color=34D399&center=true&vCenter=true&width=800&lines=Aspiring+Data+Scientist;Data+Analysis+%7C+Data+Visualization;Machine+Learning+%7C+SQL+%7C+Tableau;Building+Data-Driven+Solutions;Turning+Complex+Data+into+Meaningful+Insights;Learning+%7C+Building+%7C+Improving" alt="Typing Animation">

</div>
