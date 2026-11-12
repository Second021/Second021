<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="1500" viewBox="0 0 1000 1500">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#050505"/>
      <stop offset=".5" stop-color="#171717"/>
      <stop offset="1" stop-color="#0a0a0a"/>
    </linearGradient>
    <linearGradient id="border" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#ffffff" stop-opacity=".7"/>
      <stop offset=".5" stop-color="#ffffff" stop-opacity=".08"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity=".4"/>
    </linearGradient>
    <linearGradient id="shine" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset=".5" stop-color="#ffffff" stop-opacity=".18"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="45"/>
    </filter>
    <clipPath id="clipHead"><rect x="60" y="40" width="880" height="220" rx="30"/></clipPath>
    <clipPath id="clipFoot"><rect x="60" y="1395" width="880" height="80" rx="28"/></clipPath>
  </defs>

  <!-- Background -->
  <rect width="1000" height="1500" fill="url(#bg)"/>
  <g filter="url(#blur)">
    <circle cx="200" cy="90" r="90" fill="#ffffff" opacity=".5">
      <animateTransform attributeName="transform" type="translate" values="0,0;160,60;0,0" dur="9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="800" cy="230" r="95" fill="#bdbdbd" opacity=".45">
      <animateTransform attributeName="transform" type="translate" values="0,0;-160,-50;0,0" dur="11s" repeatCount="indefinite"/>
    </circle>
    <circle cx="150" cy="700" r="80" fill="#ffffff" opacity=".28">
      <animateTransform attributeName="transform" type="translate" values="0,0;120,80;0,0" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="850" cy="950" r="90" fill="#bdbdbd" opacity=".28">
      <animateTransform attributeName="transform" type="translate" values="0,0;-120,60;0,0" dur="13s" repeatCount="indefinite"/>
    </circle>
    <circle cx="300" cy="1280" r="85" fill="#ffffff" opacity=".28">
      <animateTransform attributeName="transform" type="translate" values="0,0;200,-40;0,0" dur="10s" repeatCount="indefinite"/>
    </circle>
  </g>

  <g font-family="Segoe UI, Helvetica, Arial, sans-serif" fill="#ffffff">

    <!-- HEADER -->
    <rect x="60" y="40" width="880" height="220" rx="30" fill="#ffffff" fill-opacity=".08" stroke="url(#border)" stroke-width="1.5"/>
    <g clip-path="url(#clipHead)">
      <rect x="0" y="40" width="220" height="220" fill="url(#shine)">
        <animateTransform attributeName="transform" type="translate" values="-260,0;1100,0" dur="5s" repeatCount="indefinite"/>
      </rect>
    </g>
    <text x="500" y="125" text-anchor="middle" font-size="50" font-weight="800" opacity="0">SINENTLANTLA TSHANGASE
      <animate attributeName="opacity" from="0" to="1" dur="1.6s" fill="freeze"/>
    </text>
    <text x="500" y="168" text-anchor="middle" font-size="17" letter-spacing="4" fill="#d4d4d4" opacity="0">ASPIRING SOFTWARE DEVELOPER  •  DATA ANALYTICS
      <animate attributeName="opacity" from="0" to="1" dur="1.6s" begin="0.8s" fill="freeze"/>
    </text>
    <text x="500" y="205" text-anchor="middle" font-size="15" fill="#9a9a9a" opacity="0">Final-Year BSc Information Technology  ·  North-West University
      <animate attributeName="opacity" from="0" to="1" dur="1.6s" begin="1.6s" fill="freeze"/>
    </text>
    <text x="500" y="236" text-anchor="middle" font-size="13" fill="#7a7a7a">Learn  •  Build  •  Analyse  •  Grow</text>

    <!-- ABOUT -->
    <rect x="60" y="300" width="560" height="250" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <text x="90" y="338" font-size="13" font-weight="800" letter-spacing="4" fill="#a3a3a3">ABOUT ME</text>
    <g font-size="15" fill="#d9d9d9">
      <text x="90" y="375">I'm a final-year BSc Information Technology student at</text>
      <text x="90" y="400">North-West University with a strong passion for Software</text>
      <text x="90" y="425">Development and Data Analytics. I enjoy solving problems,</text>
      <text x="90" y="450">building practical solutions, working with databases and</text>
      <text x="90" y="475">exploring data.</text>
      <text x="90" y="518" font-weight="700" fill="#ffffff">Goal: grow as a Software Developer and gain real-world experience.</text>
    </g>

    <rect x="640" y="300" width="300" height="250" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <g font-size="11" font-weight="800" letter-spacing="2" fill="#8c8c8c">
      <text x="670" y="338">LOCATION</text>
      <text x="670" y="391">STUDYING</text>
      <text x="670" y="444">FOCUS</text>
      <text x="670" y="497">CERTIFIED</text>
    </g>
    <g font-size="15" font-weight="600">
      <text x="670" y="358">Johannesburg, South Africa</text>
      <text x="670" y="411">BSc Information Technology</text>
      <text x="670" y="464">Software Dev &amp; Data Analytics</text>
      <text x="670" y="517">Cybersecurity (Cisco, 2025)</text>
    </g>

    <!-- SKILLS -->
    <text x="60" y="610" font-size="13" font-weight="800" letter-spacing="4" fill="#a3a3a3">TECHNICAL SKILLS</text>
    <g text-anchor="middle">
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" repeatCount="indefinite"/>
        <rect x="50" y="630" width="168" height="76" rx="26" fill="#ffffff" fill-opacity=".09" stroke="url(#border)" stroke-width="1.5"/>
        <text x="134" y="663" font-size="20" font-weight="800">Java</text>
        <text x="134" y="686" font-size="12" fill="#a3a3a3">Object-Oriented Dev</text>
      </g>
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" begin="0.4s" repeatCount="indefinite"/>
        <rect x="233" y="630" width="168" height="76" rx="26" fill="#ffffff" fill-opacity=".09" stroke="url(#border)" stroke-width="1.5"/>
        <text x="317" y="663" font-size="20" font-weight="800">C++</text>
        <text x="317" y="686" font-size="12" fill="#a3a3a3">Logic &amp; File Handling</text>
      </g>
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" begin="0.8s" repeatCount="indefinite"/>
        <rect x="416" y="630" width="168" height="76" rx="26" fill="#ffffff" fill-opacity=".09" stroke="url(#border)" stroke-width="1.5"/>
        <text x="500" y="663" font-size="20" font-weight="800">C#</text>
        <text x="500" y="686" font-size="12" fill="#a3a3a3">Application Dev</text>
      </g>
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" begin="1.2s" repeatCount="indefinite"/>
        <rect x="599" y="630" width="168" height="76" rx="26" fill="#ffffff" fill-opacity=".09" stroke="url(#border)" stroke-width="1.5"/>
        <text x="683" y="663" font-size="20" font-weight="800">Python</text>
        <text x="683" y="686" font-size="12" fill="#a3a3a3">Programming &amp; Analytics</text>
      </g>
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" begin="1.6s" repeatCount="indefinite"/>
        <rect x="782" y="630" width="168" height="76" rx="26" fill="#ffffff" fill-opacity=".09" stroke="url(#border)" stroke-width="1.5"/>
        <text x="866" y="663" font-size="20" font-weight="800">SQL</text>
        <text x="866" y="686" font-size="12" fill="#a3a3a3">Databases &amp; Retrieval</text>
      </g>
    </g>

    <!-- PROJECTS -->
    <text x="60" y="775" font-size="13" font-weight="800" letter-spacing="4" fill="#a3a3a3">FEATURED PROJECTS</text>

    <rect x="60" y="800" width="280" height="260" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <text x="310" y="835" font-size="14" font-weight="800" fill="#6f6f6f" text-anchor="end">01</text>
    <text x="85" y="850" font-size="19" font-weight="800">isibuko-website</text>
    <g font-size="14" fill="#c9c9c9">
      <text x="85" y="885">A website project that you can</text>
      <text x="85" y="907">explore live online.</text>
    </g>
    <text x="85" y="945" font-size="12" fill="#ffffff" font-weight="700">Live demo available →</text>
    <rect x="85" y="1005" width="112" height="26" rx="13" fill="#ffffff" fill-opacity=".1" stroke="#ffffff" stroke-opacity=".25"/>
    <text x="141" y="1023" font-size="11" font-weight="700" text-anchor="middle">Web Development</text>
    <rect x="205" y="1005" width="82" height="26" rx="13" fill="#ffffff" fill-opacity=".1" stroke="#ffffff" stroke-opacity=".25"/>
    <text x="246" y="1023" font-size="11" font-weight="700" text-anchor="middle">Live Demo</text>

    <rect x="360" y="800" width="280" height="260" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <text x="610" y="835" font-size="14" font-weight="800" fill="#6f6f6f" text-anchor="end">02</text>
    <text x="385" y="850" font-size="19" font-weight="800">umzimkhulu-connect</text>
    <g font-size="14" fill="#c9c9c9">
      <text x="385" y="885">A web project focused on</text>
      <text x="385" y="907">connecting people and information</text>
      <text x="385" y="929">in the Umzimkhulu community.</text>
    </g>
    <rect x="385" y="1005" width="112" height="26" rx="13" fill="#ffffff" fill-opacity=".1" stroke="#ffffff" stroke-opacity=".25"/>
    <text x="441" y="1023" font-size="11" font-weight="700" text-anchor="middle">Web Development</text>
    <rect x="505" y="1005" width="86" height="26" rx="13" fill="#ffffff" fill-opacity=".1" stroke="#ffffff" stroke-opacity=".25"/>
    <text x="548" y="1023" font-size="11" font-weight="700" text-anchor="middle">Community</text>

    <rect x="660" y="800" width="280" height="260" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <text x="910" y="835" font-size="14" font-weight="800" fill="#6f6f6f" text-anchor="end">03</text>
    <text x="685" y="850" font-size="19" font-weight="800">HelpLift</text>
    <g font-size="14" fill="#c9c9c9">
      <text x="685" y="885">A collaborative group project</text>
      <text x="685" y="907">developed through teamwork and</text>
      <text x="685" y="929">shared contributions.</text>
    </g>
    <rect x="685" y="1005" width="98" height="26" rx="13" fill="#ffffff" fill-opacity=".1" stroke="#ffffff" stroke-opacity=".25"/>
    <text x="734" y="1023" font-size="11" font-weight="700" text-anchor="middle">Group Project</text>
    <rect x="791" y="1005" width="80" height="26" rx="13" fill="#ffffff" fill-opacity=".1" stroke="#ffffff" stroke-opacity=".25"/>
    <text x="831" y="1023" font-size="11" font-weight="700" text-anchor="middle">Teamwork</text>

    <!-- EXPERIENCE & EDUCATION -->
    <text x="60" y="1110" font-size="13" font-weight="800" letter-spacing="4" fill="#a3a3a3">EXPERIENCE &amp; EDUCATION</text>

    <rect x="60" y="1135" width="430" height="240" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <text x="90" y="1172" font-size="11" font-weight="800" letter-spacing="2" fill="#8c8c8c">WORK EXPERIENCE</text>
    <text x="90" y="1205" font-size="19" font-weight="800">General Worker</text>
    <text x="90" y="1228" font-size="13" fill="#a3a3a3">Brumby Shoe Components  ·  2022 – 2023</text>
    <g font-size="14" fill="#c9c9c9">
      <text x="90" y="1265">Worked as part of a team to meet daily targets</text>
      <text x="90" y="1288">and complete assigned responsibilities. Built skills</text>
      <text x="90" y="1311">in communication, reliability, discipline, teamwork</text>
      <text x="90" y="1334">and time management.</text>
    </g>

    <rect x="510" y="1135" width="430" height="240" rx="26" fill="#ffffff" fill-opacity=".07" stroke="url(#border)" stroke-width="1.5"/>
    <text x="540" y="1172" font-size="11" font-weight="800" letter-spacing="2" fill="#8c8c8c">EDUCATION &amp; CERTIFICATION</text>
    <text x="540" y="1207" font-size="16" font-weight="800">BSc Information Technology</text>
    <text x="540" y="1227" font-size="13" fill="#a3a3a3">North-West University  ·  2023 – Present</text>
    <text x="540" y="1269" font-size="16" font-weight="800">National Senior Certificate</text>
    <text x="540" y="1289" font-size="13" fill="#a3a3a3">Ncomani High School  ·  2020 – 2021</text>
    <text x="540" y="1331" font-size="16" font-weight="800">Introduction to Cybersecurity</text>
    <text x="540" y="1351" font-size="13" fill="#a3a3a3">Cisco Networking Academy  ·  2025</text>

    <!-- FOOTER -->
    <rect x="60" y="1395" width="880" height="80" rx="28" fill="#ffffff" fill-opacity=".08" stroke="url(#border)" stroke-width="1.5"/>
    <g clip-path="url(#clipFoot)">
      <rect x="0" y="1395" width="200" height="80" fill="url(#shine)">
        <animateTransform attributeName="transform" type="translate" values="-250,0;1100,0" dur="5s" repeatCount="indefinite"/>
      </rect>
    </g>
    <text x="500" y="1431" text-anchor="middle" font-size="19" font-weight="700" letter-spacing="3">SOFTWARE DEVELOPMENT × DATA ANALYTICS</text>
    <text x="500" y="1456" text-anchor="middle" font-size="13" fill="#9a9a9a">Learning  ·  Building  ·  Growing</text>
  </g>
</svg>
