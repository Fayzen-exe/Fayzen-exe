<svg xmlns="http://www.w3.org/2000/svg" width="720" height="440" viewBox="0 0 720 440" fill="none">
  <defs>
    <linearGradient id="bg" x1="45" y1="20" x2="680" y2="420" gradientUnits="userSpaceOnUse">
      <stop stop-color="#10172D"/>
      <stop offset="0.52" stop-color="#151A36"/>
      <stop offset="1" stop-color="#30165B"/>
    </linearGradient>
    <linearGradient id="edge" x1="85" y1="45" x2="630" y2="400" gradientUnits="userSpaceOnUse">
      <stop stop-color="#67E8F9"/>
      <stop offset="0.5" stop-color="#8B5CF6"/>
      <stop offset="1" stop-color="#EC4899"/>
    </linearGradient>
    <linearGradient id="lanyard" x1="290" y1="0" x2="430" y2="140" gradientUnits="userSpaceOnUse">
      <stop stop-color="#67E8F9"/>
      <stop offset="1" stop-color="#7C3AED"/>
    </linearGradient>
    <linearGradient id="shine" x1="0" y1="0" x2="1" y2="1">
      <stop stop-color="#FFFFFF" stop-opacity=".17"/>
      <stop offset=".45" stop-color="#FFFFFF" stop-opacity=".02"/>
      <stop offset="1" stop-color="#FFFFFF" stop-opacity="0"/>
    </linearGradient>
    <filter id="shadow" x="0" y="0" width="720" height="460" filterUnits="userSpaceOnUse">
      <feGaussianBlur stdDeviation="12"/>
    </filter>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <clipPath id="cardClip">
      <rect x="95" y="119" width="530" height="285" rx="24"/>
    </clipPath>
  </defs>

  <rect width="720" height="440" rx="26" fill="#090D19"/>
  <circle cx="110" cy="100" r="90" fill="#6D28D9" opacity=".12"/>
  <circle cx="625" cy="350" r="120" fill="#06B6D4" opacity=".10"/>

  <g opacity=".17" stroke="#67E8F9" stroke-width=".8">
    <path d="M0 70H720M0 140H720M0 210H720M0 280H720M0 350H720"/>
    <path d="M70 0V440M140 0V440M210 0V440M280 0V440M350 0V440M420 0V440M490 0V440M560 0V440M630 0V440"/>
  </g>

  <!-- Lanyard -->
  <path d="M286 -20L319 116Q360 142 401 116L434 -20" stroke="#000000" stroke-opacity=".35" stroke-width="28" stroke-linecap="round" fill="none"/>
  <path d="M286 -20L319 116Q360 142 401 116L434 -20" stroke="url(#lanyard)" stroke-width="20" stroke-linecap="round" fill="none"/>
  <path d="M295 -15L327 107Q360 126 393 107L425 -15" stroke="#FFFFFF" stroke-opacity=".25" stroke-width="2" fill="none"/>

  <!-- Metal clip -->
  <rect x="339" y="91" width="42" height="48" rx="9" fill="#30394D" stroke="#9CA3AF" stroke-width="2"/>
  <rect x="348" y="99" width="24" height="29" rx="5" fill="#0F172A" stroke="#67E8F9" stroke-width="2"/>
  <circle cx="360" cy="111" r="4" fill="#67E8F9"/>

  <!-- Shadow and card -->
  <rect x="115" y="135" width="530" height="285" rx="24" fill="#7C3AED" opacity=".25" filter="url(#shadow)"/>
  <g>
    <rect x="95" y="119" width="530" height="285" rx="24" fill="url(#bg)" stroke="url(#edge)" stroke-width="2.5"/>
    <g clip-path="url(#cardClip)">
      <rect x="95" y="119" width="530" height="285" fill="url(#shine)"/>
      <path d="M445 119H625V404H355Z" fill="#8B5CF6" opacity=".07"/>
      <path d="M540 119H625V250L440 404H355Z" fill="#67E8F9" opacity=".05"/>
      <circle cx="585" cy="170" r="80" stroke="#67E8F9" stroke-opacity=".15" stroke-width="1.5"/>
      <circle cx="585" cy="170" r="60" stroke="#A78BFA" stroke-opacity=".17" stroke-width="1.5"/>
    </g>

    <!-- Header -->
    <rect x="118" y="139" width="484" height="36" rx="8" fill="#FFFFFF" fill-opacity=".055"/>
    <circle cx="136" cy="157" r="4" fill="#67E8F9" filter="url(#glow)"/>
    <text x="149" y="161" fill="#B9C8E9" font-family="Arial, Helvetica, sans-serif" font-size="11" font-weight="700" letter-spacing="2">DIGITAL DEVELOPER ID</text>
    <text x="580" y="161" text-anchor="end" fill="#67E8F9" font-family="Arial, Helvetica, sans-serif" font-size="10" letter-spacing="1.5">01 / DEV</text>

    <!-- Profile avatar -->
    <rect x="120" y="192" width="128" height="150" rx="15" fill="#0C1428" stroke="#67E8F9" stroke-opacity=".65" stroke-width="1.5"/>
    <rect x="129" y="201" width="110" height="132" rx="10" fill="#17213D"/>
    <circle cx="184" cy="244" r="23" fill="#67E8F9" fill-opacity=".16" stroke="#67E8F9" stroke-opacity=".65" stroke-width="1.5"/>
    <text x="184" y="253" text-anchor="middle" fill="#E0F2FE" font-family="Arial, Helvetica, sans-serif" font-size="26" font-weight="700">F</text>
    <path d="M148 303Q148 272 184 272Q220 272 220 303" stroke="#A78BFA" stroke-width="2" fill="#8B5CF6" fill-opacity=".18"/>
    <path d="M138 317H230" stroke="#67E8F9" stroke-opacity=".45"/>
    <text x="184" y="329" text-anchor="middle" fill="#B9C8E9" font-family="Arial, Helvetica, sans-serif" font-size="8" letter-spacing="1.5">PROFILE ID</text>

    <!-- Identity -->
    <text x="269" y="207" fill="#67E8F9" font-family="Arial, Helvetica, sans-serif" font-size="10" font-weight="700" letter-spacing="2">NAME / IDENTITY</text>
    <text x="269" y="232" fill="#FFFFFF" font-family="Arial, Helvetica, sans-serif" font-size="19" font-weight="700">MUHAMMAD</text>
    <text x="269" y="256" fill="#FFFFFF" font-family="Arial, Helvetica, sans-serif" font-size="19" font-weight="700">FAIZAN UD DIN</text>
    <text x="269" y="280" fill="#C4B5FD" font-family="Arial, Helvetica, sans-serif" font-size="10" font-weight="700" letter-spacing="1.6">FULL STACK DEVELOPER</text>
    <text x="269" y="297" fill="#A5B4CF" font-family="Arial, Helvetica, sans-serif" font-size="11">MERN STACK SPECIALIST</text>

    <rect x="269" y="311" width="145" height="25" rx="6" fill="#67E8F9" fill-opacity=".10" stroke="#67E8F9" stroke-opacity=".45"/>
    <text x="341.5" y="327" text-anchor="middle" fill="#A5F3FC" font-family="Arial, Helvetica, sans-serif" font-size="9" font-weight="700" letter-spacing="1">WEB ENGINEERING</text>

    <!-- QR-inspired decorative grid -->
    <g transform="translate(547 259)" fill="#A78BFA">
      <rect width="10" height="10" rx="1"/>
      <rect x="13" width="10" height="10" rx="1"/>
      <rect x="26" width="10" height="10" rx="1"/>
      <rect y="13" width="10" height="10" rx="1"/>
      <rect x="26" y="13" width="10" height="10" rx="1"/>
      <rect y="26" width="10" height="10" rx="1"/>
      <rect x="13" y="26" width="10" height="10" rx="1"/>
      <rect x="26" y="26" width="10" height="10" rx="1"/>
    </g>

    <!-- Project footer -->
    <path d="M120 355H600" stroke="#FFFFFF" stroke-opacity=".12"/>
    <text x="122" y="377" fill="#94A3B8" font-family="Arial, Helvetica, sans-serif" font-size="9" letter-spacing="1.4">CURRENT BUILDS</text>
    <rect x="264" y="362" width="112" height="25" rx="6" fill="#7C3AED" fill-opacity=".2" stroke="#A78BFA" stroke-opacity=".6"/>
    <text x="320" y="378" text-anchor="middle" fill="#DDD6FE" font-family="Arial, Helvetica, sans-serif" font-size="10" font-weight="700">HYPERNOVA AI</text>
    <rect x="385" y="362" width="95" height="25" rx="6" fill="#0891B2" fill-opacity=".17" stroke="#67E8F9" stroke-opacity=".6"/>
    <text x="432.5" y="378" text-anchor="middle" fill="#A5F3FC" font-family="Arial, Helvetica, sans-serif" font-size="10" font-weight="700">FIZORA LAB</text>
    <circle cx="580" cy="374" r="5" fill="#34D399">
      <animate attributeName="opacity" values="1;0.35;1" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Animated neon scan -->
  <rect x="96" y="120" width="528" height="3" rx="1.5" fill="#67E8F9" opacity=".8" filter="url(#glow)">
    <animate attributeName="y" values="121;400;121" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values=".8;.15;.8" dur="5s" repeatCount="indefinite"/>
  </rect>

  <text x="360" y="428" text-anchor="middle" fill="#7C8AA8" font-family="Arial, Helvetica, sans-serif" font-size="9" letter-spacing="3">DESIGNED TO BUILD · ENGINEERED TO CREATE</text>
</svg>
