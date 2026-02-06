<p align="center">
  <svg width="600" height="180" viewBox="0 0 600 180" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

   
    <text x="50%" y="55%"
          text-anchor="middle"
          font-size="90"
          font-weight="800"
          fill="none"
          stroke="#00f0ff"
          stroke-width="2"
          font-family="Arial, Helvetica, sans-serif"
          filter="url(#glow)">
      GOKU
    </text>

    
    <g fill="#00f0ff">
      <!-- Partícula 1 -->
      <circle r="2">
        <animateMotion dur="4s" repeatCount="indefinite"
          path="M100 90 Q300 10 500 90"/>
      </circle>

      
      <circle r="1.5">
        <animateMotion dur="5s" repeatCount="indefinite"
          path="M120 110 Q300 170 480 110"/>
      </circle>

   
      <circle r="1.8">
        <animateMotion dur="6s" repeatCount="indefinite"
          path="M80 90 Q300 90 520 90"/>
      </circle>

     
      <circle r="1.2">
        <animateMotion dur="3.5s" repeatCount="indefinite"
          path="M150 70 Q300 140 450 70"/>
      </circle>
    </g>
  </svg>
</p>

<h2 align="center">🧠 GOKU</h2>

<p align="center">
  Un asistente universitario que no piensa por ti, <br>
  <b>piensa contigo.</b>
</p>
