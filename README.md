<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0f"/>
      <stop offset="50%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#0a0a0f"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ffffff"/>
      <stop offset="50%" style="stop-color:#e2e8f0"/>
      <stop offset="100%" style="stop-color:#94a3b8"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00000000"/>
      <stop offset="30%" style="stop-color:#38bdf8"/>
      <stop offset="70%" style="stop-color:#818cf8"/>
      <stop offset="100%" style="stop-color:#00000000"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bg)" rx="12"/>

  <!-- Grid lines subtle -->
  <g opacity="0.04" stroke="#ffffff" stroke-width="0.5">
    <line x1="0" y1="56" x2="900" y2="56"/>
    <line x1="0" y1="112" x2="900" y2="112"/>
    <line x1="0" y1="168" x2="900" y2="168"/>
    <line x1="0" y1="224" x2="900" y2="224"/>
    <line x1="180" y1="0" x2="180" y2="280"/>
    <line x1="360" y1="0" x2="360" y2="280"/>
    <line x1="540" y1="0" x2="540" y2="280"/>
    <line x1="720" y1="0" x2="720" y2="280"/>
  </g>

  <!-- Glow orbs -->
  <circle cx="180" cy="140" r="120" fill="#38bdf8" opacity="0.04"/>
  <circle cx="720" cy="140" r="100" fill="#818cf8" opacity="0.05"/>
  <circle cx="450" cy="140" r="160" fill="#0ea5e9" opacity="0.025"/>

  <!-- Top accent line -->
  <rect x="0" y="0" width="900" height="2" fill="url(#lineGrad)" rx="1"/>

  <!-- Corner brackets -->
  <g stroke="#38bdf8" stroke-width="1.5" fill="none" opacity="0.6">
    <path d="M 20 20 L 20 8 L 32 8"/>
    <path d="M 880 20 L 880 8 L 868 8"/>
    <path d="M 20 260 L 20 272 L 32 272"/>
    <path d="M 880 260 L 880 272 L 868 272"/>
  </g>

  <!-- Dot pattern right side -->
  <g fill="#38bdf8" opacity="0.15">
    <circle cx="800" cy="60" r="1.5"/>
    <circle cx="820" cy="60" r="1.5"/>
    <circle cx="840" cy="60" r="1.5"/>
    <circle cx="800" cy="80" r="1.5"/>
    <circle cx="820" cy="80" r="1.5"/>
    <circle cx="840" cy="80" r="1.5"/>
    <circle cx="800" cy="100" r="1.5"/>
    <circle cx="820" cy="100" r="1.5"/>
    <circle cx="840" cy="100" r="1.5"/>
  </g>

  <!-- Small tag top left -->
  <text x="40" y="35" font-family="monospace" font-size="11" fill="#38bdf8" opacity="0.7" letter-spacing="3">PORTFOLIO.README</text>

  <!-- Main name -->
  <text x="450" y="130" font-family="'Courier New', monospace" font-size="64" font-weight="900"
    fill="url(#nameGrad)" text-anchor="middle" letter-spacing="12" filter="url(#softglow)">
    TULYA
  </text>
  <text x="450" y="195" font-family="'Courier New', monospace" font-size="64" font-weight="900"
    fill="url(#nameGrad)" text-anchor="middle" letter-spacing="12" filter="url(#softglow)">
    JAIN
  </text>

  <!-- Subtitle -->
  <text x="450" y="235" font-family="monospace" font-size="13" fill="#64748b"
    text-anchor="middle" letter-spacing="6">FRONTEND DEVELOPER · GUJARAT, INDIA</text>

  <!-- Bottom accent line -->
  <rect x="0" y="278" width="900" height="2" fill="url(#lineGrad)" rx="1"/>

  <!-- Animated pulse dot -->
  <circle cx="450" cy="252" r="3" fill="#38bdf8">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
