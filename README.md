<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="300" viewBox="0 0 1200 300">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%">
        <animate attributeName="stop-color"
          values="#020617;#0f172a;#111827;#172554;#1e1b4b;#2e1065;#450a0a;#3f1d0b;#052e16;#083344;#020617"
          dur="10s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%">
        <animate attributeName="stop-color"
          values="#1e3a8a;#312e81;#4c1d95;#7c2d12;#991b1b;#be123c;#9f1239;#065f46;#155e75;#4338ca;#1e3a8a"
          dur="10s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%">
        <animate attributeName="stop-color"
          values="#312e81;#4c1d95;#7e22ce;#9f1239;#dc2626;#ea580c;#ca8a04;#16a34a;#0891b2;#6366f1;#312e81"
          dur="10s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <clipPath id="round">
      <rect width="1200" height="300" rx="35"/>
    </clipPath>
  </defs>

  <g clip-path="url(#round)">
    <rect width="1200" height="300" fill="url(#bg)"/>

    <circle cx="100" cy="40" r="120" fill="#ffffff" opacity=".04">
      <animate attributeName="cx" values="100;1100;100" dur="10s" repeatCount="indefinite"/>
    </circle>

    <circle cx="1100" cy="270" r="180" fill="#ffffff" opacity=".03">
      <animate attributeName="cy" values="270;40;270" dur="10s" repeatCount="indefinite"/>
    </circle>

    <path d="M0 245 Q300 175 600 235 T1200 210 L1200 300 L0 300Z"
          fill="#ffffff" opacity=".035"/>

    <text x="600" y="125"
          text-anchor="middle"
          font-family="Arial, Helvetica, sans-serif"
          font-size="44"
          font-weight="700"
          filter="url(#glow)">
      <tspan fill="#ffffff">Hi 👋, </tspan>
      <tspan fill="#ff3b3b">
        I'm Akhlaque Alam
      </tspan>
    </text>

    <rect x="410" y="155" width="380" height="2" rx="1" fill="#ff3b3b" opacity=".8">
      <animate attributeName="width" values="380;500;380" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="x" values="410;350;410" dur="2s" repeatCount="indefinite"/>
    </rect>

    <text x="600" y="205"
          text-anchor="middle"
          font-family="Fira Code, monospace"
          font-size="22"
          font-weight="500"
          fill="#34d399">
      Aspiring Data Scientist
    </text>

    <text x="600" y="242"
          text-anchor="middle"
          font-family="Arial, Helvetica, sans-serif"
          font-size="14"
          letter-spacing="3"
          fill="#ffffff"
          opacity=".75">
      DATA • MACHINE LEARNING • ANALYTICS
    </text>
  </g>
</svg>
