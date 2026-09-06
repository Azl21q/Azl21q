<svg xmlns="http://www.w3.org/2000/svg" width="800" height="1184" viewBox="0 0 800 1184">
<style>
    @font-face { font-family: 'Inter'; font-style: normal; font-weight: 400 900; font-display: swap; src: url(https://fonts.gstatic.com/s/inter/v13/UcCO3FwrK3iLTeHuS_fvQtMwCp50KnMw2boKoduKmMEVuGkyMZhrib2Bg-4.woff2) format('woff2'); }
    @keyframes drift-r { 0%, 100% { transform: translate(0,0); opacity: 0.6; } 50% { transform: translate(35px,-18px); opacity: 1; } }
    @keyframes drift-l { 0%, 100% { transform: translate(0,0); opacity: 0.55; } 50% { transform: translate(-30px,16px); opacity: 0.95; } }
    @keyframes drift-u { 0%, 100% { transform: translate(0,0); opacity: 0.7; } 50% { transform: translate(25px,-25px); opacity: 1.05; } }
    @keyframes pulse { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.2); opacity: 0.35; } }
    @keyframes scan { 0% { transform: translate(-900px,0); } 100% { transform: translate(900px,0); } }
    @keyframes ring-pulse { 0%, 100% { opacity: 0.15; } 50% { opacity: 0.35; } }
    @keyframes draw { 0% { stroke-dashoffset: 500; } 100% { stroke-dashoffset: 0; } }
    @keyframes dot-float { 0%, 100% { opacity: 0.35; } 50% { opacity: 0.9; } }
    @keyframes particle-fade { 0%, 100% { opacity: 0; } 40%, 60% { opacity: var(--peak, 0.5); } }
    .g-dr { animation: drift-r 8s ease-in-out infinite; }
    .g-dl { animation: drift-l 9s ease-in-out infinite 0.3s; }
    .g-du { animation: drift-u 7s ease-in-out infinite 0.6s; }
    .g-p { animation: pulse 6s ease-in-out infinite; }
    .g-scan { animation: scan 4.5s linear infinite; }
    .g-ring { animation: ring-pulse 4s ease-in-out infinite; }
    .g-draw { animation: draw 3s ease-in-out infinite; stroke-dasharray: 250 250; }
    .g-dot { animation: dot-float 5s ease-in-out infinite; }
    .particle { animation: particle-fade var(--dur) ease-in-out infinite; opacity: 0; }
    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after { animation: none !important; }
      .particle { opacity: 0.3 !important; }
    }
  </style>
[![css progressbar](https://readme-components.vercel.app/api?component=linearprogress&skill=Skill&value=16)](https://github.com/harish-sethuraman/readme-components)
