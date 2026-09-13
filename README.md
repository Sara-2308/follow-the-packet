# 🌐 FOLLOW THE PACKET
### *“Your click travels farther than you think.”*

> **MITs ACM Student Chapter Selection Challenge • Topic: ACM/PS/19: How Does the Internet Reach You?**  
> An award-winning, interactive digital experience tracing the physical odyssey of a single data packet from a remote server to your screen.

---

## 🧭 The Journey

```
DATA CENTER ──▶ UNDERSEA CABLES ──▶ ISP CORE ──▶ ROUTER ──▶ YOUR DEVICE
   [01]               [02]            [03]        [04]         [05]
```

1. **01 / Data Center (Origin)**: Explores climate-controlled server racks, animated status LEDs, MTU 1,500-byte packet dissection (IP + TCP headers + TLS payload), and optical transceiver packet genesis.
2. **02 / Undersea Cables (The Ocean)**: Stylized dark emerald vector world map illustrating real-world transatlantic and Indian Ocean fiber routes, inline optical repeaters (amplifiers), and an interactive **"PEEK INSIDE THE CABLE"** 6-layer cross-section explorer.
3. **03 / The ISP (Network of Networks)**: Interactive network topology graph demonstrating Tier 1 Backbone transit (`AS3356`), Internet Exchange Point (IXP) peering fabrics, regional metro rings, and an interactive **"TRACE ROUTE"** BGP simulator.
4. **04 / Your Router (The Local Traffic Cop)**: Hardware-grade Wi-Fi 6 gateway mockup with beamforming antenna waves, live device subnet selector (`192.168.1.x`), and real-time **Network Address Translation (NAT)** readouts.
5. **05 / Your Device (The Last Meter)**: Futuristic laptop and smartphone CSS mockups featuring an animated 4-stage packet unboxing (*Arrival → Demodulation → TCP Reassembly → Browser DOM Paint*) culminating in `200 OK • 104 MS`.

---

## ⚡ Interactive Bonus Features

- **Heads-Up Display (HUD)**: Live telemetry tracking `PACKET_7A3F`, hop count, stage ID, and cumulative latency in real time.
- **Persistent Journey Rail**: Left-hand navigation rail tracking journey progress with glowing emerald indicator nodes.
- **Latency Lab**: Physics simulator comparing light propagation in fiber glass (~204,000 km/s), electronic router hops, and the blink of a human eye (300–400 ms).
- **AI Explorer ("Ask the Packet")**: Interactive knowledge assistant with real-time question search and a toggle between **"Intuitive / Simple"** and **"Deep Technical / Network Engineer"** modes.
- **Procedural Web Audio Synthesizer**: Native in-browser Web Audio API sound generator with ambient 55 Hz drone and packet hop chirps (zero external mp3 files, toggleable in navigation bar).

---

## 🎨 Design System & Visual Identity

- **Palette**: Dark Emerald Forest (`#03120D`, `#061A13`, `#08251B`) with luminous Emerald (`#24B47E`, `#36D99A`), Mint (`#58F0B0`), Soft Lime (`#B9F36A`, `#E0FFB0`), and warm off-white (`#F4F8F3`) for high-contrast accessibility.
- **Typography**: Editorial Display Serif (*Playfair Display*, *Cormorant Garamond*, *Source Serif 4*) paired with technical monospace (*IBM Plex Mono*, *JetBrains Mono*).
- **Zero-Dependency Architecture**: Built using pure HTML5, Modern CSS3, Vanilla ES6+ JavaScript, SVG vector graphics, HTML5 Canvas, and the native Web Audio API. Requires **no Node.js build step, no npm packages, and no external servers**.

---

## 📂 Project Structure

```
PIXEL/
├── standalone.html       # 100% self-contained single-file distribution (161 KB)
├── index.html            # Modular semantic HTML5 master file
├── README.md             # Project documentation & challenge overview
├── .gitignore            # Git ignore configuration
├── css/
│   ├── main.css          # Design tokens, typography, HUD, ambient canvas, reset
│   ├── journey.css       # Visual art direction for Hero, DC, Ocean, ISP, Router, Device
│   └── interactive.css   # Latency Lab, AI Explorer, Cable Peek modal, race tracks
└── js/
    ├── sound.js          # Procedural Web Audio API synthesizer
    ├── packet.js         # Canvas background particle system and hero orbit simulation
    ├── world-map.js      # Interactive SVG submarine cable map with packet traversal
    ├── cable-peek.js     # Cable cross-section 6-layer exploder & modal inspector
    ├── topology.js       # ISP network graph & BGP autonomous system tracer
    ├── router-sim.js     # Router hardware visualizer, beamforming, and NAT distributor
    ├── latency-lab.js    # Speed of light latency simulator & visual race tracks
    ├── ai-explorer.js    # Interactive knowledge explorer with simple/tech modes
    └── app.js            # Main scroll observers, HUD telemetry sync, keyboard accessibility
```

---

## 🚀 Quick Start & Running Locally

1. **Option 1: Direct File Open**
   Double-click `standalone.html` or `index.html` to open directly in any modern web browser (Google Chrome, Microsoft Edge, Safari, Firefox).
2. **Option 2: Local Static Server**
   ```bash
   # Python (if installed)
   python -m http.server 8000
   # Open http://localhost:8000
   ```

---

## 🏆 Submission Details

- **Event**: MITs ACM Student Chapter Selection Challenge
- **Problem Statement**: `ACM/PS/19: How Does the Internet Reach You?`
- **Candidate Project**: FOLLOW THE PACKET
