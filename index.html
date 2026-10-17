```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LuminaCAD - 3D Printable Lamp Shade & Shadow Studio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <script type="importmap">
    {
      "imports": {
        "three": "https://cdn.jsdelivr.net/npm/three@0.160.0/build/three.module.js",
        "three/addons/": "https://cdn.jsdelivr.net/npm/three@0.160.0/examples/jsm/"
      }
    }
  </script>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background-color: #090d16;
      color: #f8fafc;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
    }
    .font-mono {
      font-family: 'JetBrains Mono', monospace;
    }
    ::-webkit-scrollbar { width: 6px; height: 6px; }
    ::-webkit-scrollbar-track { background: #0f172a; }
    ::-webkit-scrollbar-thumb { background: #334155; border-radius: 3px; }
    ::-webkit-scrollbar-thumb:hover { background: #475569; }
    input[type="range"] {
      accent-color: #f59e0b;
      height: 5px;
      border-radius: 4px;
      cursor: pointer;
    }
  </style>
</head>
<body class="flex flex-col md:flex-row h-screen w-screen overflow-hidden">

  <!-- Left Control Sidebar -->
  <aside class="w-full md:w-96 bg-slate-900/95 border-b md:border-b-0 md:border-r border-slate-800 flex flex-col h-[48vh] md:h-full z-20 select-none shadow-2xl shrink-0">
    
    <!-- App Header -->
    <div class="px-4 py-3 border-b border-slate-800 flex items-center justify-between bg-slate-950/60">
      <div class="flex items-center space-x-2.5">
        <div class="w-3.5 h-3.5 rounded-full bg-amber-400 shadow-[0_0_12px_#f59e0b]"></div>
        <div>
          <h1 class="font-bold text-base tracking-wide text-white leading-none">Lumina<span class="text-amber-400">CAD</span> <span class="text-[10px] font-mono uppercase px-1.5 py-0.5 bg-amber-500/20 text-amber-300 rounded border border-amber-500/30 ml-1">v2.0</span></h1>
          <p class="text-[11px] text-slate-400 mt-0.5">Perforated & Parametric Shade Studio</p>
        </div>
      </div>
      <span class="text-xs font-mono bg-slate-800 text-slate-300 px-2 py-1 rounded border border-slate-700">mm</span>
    </div>

    <!-- Scrollable Parameters Container -->
    <div class="flex-1 overflow-y-auto p-4 space-y-5 text-xs">

      <!-- Quick Presets -->
      <div>
        <label class="block text-[11px] font-semibold uppercase tracking-wider text-slate-400 mb-2">Designer Presets</label>
        <div class="grid grid-cols-2 gap-2">
          <button onclick="applyPreset('voronoiLantern')" class="px-2.5 py-2 bg-slate-800/90 hover:bg-amber-500/20 hover:border-amber-500/50 rounded-lg border border-slate-700 text-left transition flex items-center justify-between group">
            <span class="font-medium text-slate-200 group-hover:text-amber-300">Voronoi Lantern</span>
            <span class="text-[10px] text-amber-400">✨</span>
          </button>
          <button onclick="applyPreset('honeycombGourd')" class="px-2.5 py-2 bg-slate-800/90 hover:bg-amber-500/20 hover:border-amber-500/50 rounded-lg border border-slate-700 text-left transition flex items-center justify-between group">
            <span class="font-medium text-slate-200 group-hover:text-amber-300">Honeycomb Gourd</span>
            <span class="text-[10px] text-amber-400">⬢</span>
          </button>
          <button onclick="applyPreset('moroccanStar')" class="px-2.5 py-2 bg-slate-800/90 hover:bg-amber-500/20 hover:border-amber-500/50 rounded-lg border border-slate-700 text-left transition flex items-center justify-between group">
            <span class="font-medium text-slate-200 group-hover:text-amber-300">Moroccan Trellis</span>
            <span class="text-[10px] text-amber-400">❖</span>
          </button>
          <button onclick="applyPreset('nordicPleat')" class="px-2.5 py-2 bg-slate-800/90 hover:bg-amber-500/20 hover:border-amber-500/50 rounded-lg border border-slate-700 text-left transition flex items-center justify-between group">
            <span class="font-medium text-slate-200 group-hover:text-amber-300">Nordic Pleat</span>
            <span class="text-[10px] text-slate-400">≋</span>
          </button>
        </div>
      </div>

      <!-- Section 1: Perforated Cutout Patterns (NEW) -->
      <div class="space-y-3 bg-gradient-to-b from-amber-500/10 to-slate-800/40 p-3.5 rounded-xl border border-amber-500/30">
        <div class="flex items-center justify-between">
          <h2 class="text-xs font-semibold uppercase tracking-wider text-amber-400 flex items-center gap-1.5">
            <span>1. Perforated Shadow Pattern</span>
          </h2>
          <span class="text-[10px] bg-amber-500/20 text-amber-300 px-1.5 py-0.5 rounded font-mono">Manifold</span>
        </div>

        <div>
          <label class="block mb-1 text-slate-300">Cutout Lattice Style</label>
          <select id="patternType" class="w-full bg-slate-900 border border-slate-700 rounded-lg p-2 text-white focus:outline-none focus:border-amber-400">
            <option value="voronoi" selected>Voronoi Cellular Lattice</option>
            <option value="hex">Hexagonal Honeycomb Lattice</option>
            <option value="diamond">Moroccan Diamond Trellis</option>
            <option value="dots">Circular Polka Perforations</option>
            <option value="spiral">Helical Spiral Louvers</option>
            <option value="none">Solid Wall (Translucent Diffusion)</option>
          </select>
        </div>

        <div id="patternControls" class="space-y-3 pt-1">
          <div>
            <div class="flex justify-between mb-1">
              <label class="text-slate-300">Pattern Density / Cells</label>
              <span id="val-patternScale" class="text-amber-400 font-mono">14</span>
            </div>
            <input id="patternScale" type="range" min="6" max="28" value="14" step="1" class="w-full">
          </div>

          <div>
            <div class="flex justify-between mb-1">
              <label class="text-slate-300">Strut Width (Bridge Size)</label>
              <span id="val-strutWidth" class="text-amber-400 font-mono">0.28</span>
            </div>
            <input id="strutWidth" type="range" min="0.14" max="0.65" value="0.28" step="0.02" class="w-full">
          </div>

          <div>
            <div class="flex justify-between mb-1">
              <label class="text-slate-300">Top/Bottom Solid Rim</label>
              <span id="val-rimMargin" class="text-amber-400 font-mono">14 mm</span>
            </div>
            <input id="rimMargin" type="range" min="5" max="40" value="14" step="1" class="w-full">
          </div>

          <div id="seedControlRow" class="flex items-center justify-between pt-1">
            <span class="text-slate-300">Voronoi Random Seed</span>
            <div class="flex items-center space-x-2">
              <input id="patternSeed" type="number" min="1" max="999" value="42" class="w-16 bg-slate-900 border border-slate-700 rounded px-2 py-1 text-center font-mono text-amber-400">
              <button id="randomSeedBtn" class="px-2.5 py-1 bg-slate-800 hover:bg-slate-700 text-slate-200 rounded border border-slate-600 transition">🎲 Shuffle</button>
            </div>
          </div>
        </div>
      </div>

      <!-- Section 2: Dimensions & Silhouette -->
      <div class="space-y-3 bg-slate-800/40 p-3.5 rounded-xl border border-slate-800">
        <h2 class="text-xs font-semibold uppercase tracking-wider text-amber-400">2. Dimensions & Silhouette</h2>
        
        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Height</label><span id="val-height" class="text-amber-400 font-mono">180 mm</span></div>
          <input id="height" type="range" min="70" max="320" value="180" step="2" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Bottom Radius</label><span id="val-bottomRadius" class="text-amber-400 font-mono">68 mm</span></div>
          <input id="bottomRadius" type="range" min="25" max="140" value="68" step="1" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Top Radius</label><span id="val-topRadius" class="text-amber-400 font-mono">48 mm</span></div>
          <input id="topRadius" type="range" min="20" max="140" value="48" step="1" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Mid Bulge (Belly)</label><span id="val-bulge" class="text-amber-400 font-mono">24 mm</span></div>
          <input id="bulge" type="range" min="-45" max="75" value="24" step="1" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Bulge Vertical Center</label><span id="val-bulgePos" class="text-amber-400 font-mono">0.45</span></div>
          <input id="bulgePos" type="range" min="0.20" max="0.80" value="0.45" step="0.05" class="w-full">
        </div>
      </div>

      <!-- Section 3: Surface Texture & Ribs -->
      <div class="space-y-3 bg-slate-800/40 p-3.5 rounded-xl border border-slate-800">
        <h2 class="text-xs font-semibold uppercase tracking-wider text-amber-400">3. Surface Texture & Ribs</h2>

        <div>
          <label class="block mb-1 text-slate-300">Surface Wave Contour</label>
          <select id="waveType" class="w-full bg-slate-900 border border-slate-700 rounded-lg p-2 text-white focus:outline-none focus:border-amber-400">
            <option value="sine">Smooth Sine Ribs</option>
            <option value="pleat">Sharp Accordion Pleats</option>
            <option value="flute">Concave Flutes</option>
            <option value="diamond">Origami Diamond Facets</option>
          </select>
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Rib Count</label><span id="val-ribs" class="text-amber-400 font-mono">16</span></div>
          <input id="ribs" type="range" min="0" max="64" value="16" step="1" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Rib Depth</label><span id="val-ribDepth" class="text-amber-400 font-mono">3.5 mm</span></div>
          <input id="ribDepth" type="range" min="0" max="20" value="3.5" step="0.5" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Helical Twist Angle</label><span id="val-twist" class="text-amber-400 font-mono">60°</span></div>
          <input id="twist" type="range" min="-360" max="360" value="60" step="5" class="w-full">
        </div>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Vertical Ripple Freq</label><span id="val-vFreq" class="text-amber-400 font-mono">0</span></div>
          <input id="vFreq" type="range" min="0" max="12" value="0" step="1" class="w-full">
        </div>
      </div>

      <!-- Section 4: 3D Print & Socket Fitter -->
      <div class="space-y-3 bg-slate-800/40 p-3.5 rounded-xl border border-slate-800">
        <h2 class="text-xs font-semibold uppercase tracking-wider text-amber-400">4. 3D Print & Socket Fitter</h2>

        <div>
          <div class="flex justify-between mb-1"><label class="text-slate-300">Wall Thickness</label><span id="val-wall" class="text-amber-400 font-mono">2.4 mm</span></div>
          <input id="wall" type="range" min="1.2" max="5.0" value="2.4" step="0.2" class="w-full">
        </div>

        <div>
          <label class="block mb-1 text-slate-300">Socket Mount Position</label>
          <select id="fitterPos" class="w-full bg-slate-900 border border-slate-700 rounded-lg p-2 text-white focus:outline-none focus:border-amber-400">
            <option value="bottom">Bottom (Table Lamp Base)</option>
            <option value="top">Top (Pendant / Hanging Cord)</option>
            <option value="none">None (Open Cylinder / Vase)</option>
          </select>
        </div>

        <div id="fitterControls" class="space-y-3 pt-2 border-t border-slate-700/60">
          <div>
            <label class="block mb-1 text-slate-300">Socket Ring Standard</label>
            <select id="socketPreset" class="w-full bg-slate-900 border border-slate-700 rounded-lg p-2 text-white text-xs">
              <option value="40">E26 / E27 Standard Ring (40 mm)</option>
              <option value="28">E14 European Small (28 mm)</option>
              <option value="26">E12 North America Candelabra (26 mm)</option>
              <option value="35">IKEA HEMMA / Strala Cord (35 mm)</option>
            </select>
          </div>

          <div>
            <div class="flex justify-between mb-1"><label class="text-slate-300">Socket Hole Diameter</label><span id="val-holeDia" class="text-amber-400 font-mono">40 mm</span></div>
            <input id="holeDia" type="range" min="16" max="90" value="40" step="0.5" class="w-full">
          </div>

          <div>
            <div class="flex justify-between mb-1"><label class="text-slate-300">Support Spokes</label><span id="val-spokes" class="text-amber-400 font-mono">4</span></div>
            <input id="spokes" type="range" min="3" max="8" value="4" step="1" class="w-full">
          </div>
        </div>
      </div>

    </div>

    <!-- Footer Actions -->
    <div class="p-3.5 border-t border-slate-800 bg-slate-950/90 space-y-2">
      <div class="flex items-center justify-between text-[11px] text-slate-400">
        <span id="polyCount" class="font-mono">Triangles: 0</span>
        <span class="flex items-center gap-1 text-emerald-400 font-medium">
          <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
          Watertight Manifold
        </span>
      </div>
      <button id="exportBtn" class="w-full py-2.5 bg-amber-500 hover:bg-amber-400 active:scale-[0.99] text-slate-950 font-bold rounded-xl shadow-lg shadow-amber-500/20 transition flex items-center justify-center space-x-2 text-sm">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"/></svg>
        <span>Export Printable .STL</span>
      </button>
    </div>
  </aside>

  <!-- Main 3D Viewport -->
  <main class="flex-1 relative h-[52vh] md:h-full overflow-hidden">
    <div id="canvas-container" class="w-full h-full"></div>

    <!-- Top Floating Viewport Toolbar -->
    <div class="absolute top-3 left-3 right-3 md:left-auto md:right-4 flex flex-wrap items-center justify-between md:justify-end gap-2 bg-slate-900/90 backdrop-blur-md border border-slate-700/80 rounded-xl p-2 shadow-2xl z-10">
      <button id="toggleBulb" class="flex items-center space-x-1.5 px-3 py-1.5 rounded-lg bg-amber-500/20 border border-amber-500/50 text-amber-300 text-xs font-medium hover:bg-amber-500/30 transition">
        <span>💡 Bulb ON</span>
      </button>

      <button id="toggleRoom" class="flex items-center space-x-1.5 px-3 py-1.5 rounded-lg bg-indigo-500/20 border border-indigo-500/50 text-indigo-300 text-xs font-medium hover:bg-indigo-500/30 transition">
        <span>🏠 Shadow Room ON</span>
      </button>

      <button id="toggleWireframe" class="px-3 py-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 text-xs font-medium border border-slate-700 transition">
        Wireframe
      </button>

      <div class="flex items-center space-x-2 pl-2 border-l border-slate-700">
        <label class="text-[11px] text-slate-400">Brightness</label>
        <input id="bulbPower" type="range" min="0.5" max="12" value="5.5" step="0.5" class="w-16">
      </div>

      <div class="flex items-center space-x-1.5 pl-2 border-l border-slate-700">
        <label class="text-[11px] text-slate-400">PLA:</label>
        <input id="filamentColor" type="color" value="#fffbeb" class="w-6 h-6 rounded cursor-pointer bg-transparent border-0">
      </div>
    </div>

    <!-- Bottom Slicer Print Tip Overlay -->
    <div class="hidden sm:flex items-center justify-between absolute bottom-3 left-4 right-4 bg-slate-900/85 backdrop-blur border border-slate-800/90 rounded-xl px-4 py-2 text-xs text-slate-400 pointer-events-none shadow-lg">
      <div>
        <strong class="text-amber-400">Shadow Projection Mode:</strong> Cutout patterns project crisp caustics & geometric shadows onto the surrounding walls when using a clear <span class="text-slate-200">filament-style LED bulb</span>.
      </div>
      <div class="font-mono text-[11px] text-slate-400 ml-4 shrink-0">
        Bed Grid: 240×240 mm
      </div>
    </div>
  </main>

  <script type="module">
    import * as THREE from 'three';
    import { OrbitControls } from 'three/addons/controls/OrbitControls.js';
    import { STLExporter } from 'three/addons/exporters/STLExporter.js';
    import * as BufferGeometryUtils from 'three/addons/utils/BufferGeometryUtils.js';

    // --- 1. Scene, Camera & Renderer Setup ---
    const container = document.getElementById('canvas-container');
    const scene = new THREE.Scene();
    scene.background = new THREE.Color(0x070a12);

    const camera = new THREE.PerspectiveCamera(45, container.clientWidth / container.clientHeight, 1, 4000);
    camera.position.set(0, 210, 440);

    const renderer = new THREE.WebGLRenderer({ antialias: true });
    renderer.setSize(container.clientWidth, container.clientHeight);
    renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
    renderer.shadowMap.enabled = true;
    renderer.shadowMap.type = THREE.PCFSoftShadowMap;
    renderer.toneMapping = THREE.ACESFilmicToneMapping;
    renderer.toneMappingExposure = 1.05;
    container.appendChild(renderer.domElement);

    const controls = new OrbitControls(camera, renderer.domElement);
    controls.enableDamping = true;
    controls.dampingFactor = 0.06;
    controls.maxDistance = 950;
    controls.minDistance = 60;
    controls.target.set(0, 95, 0);

    // --- 2. Reference Build Plate & Shadow Projection Room ---
    const gridHelper = new THREE.GridHelper(240, 24, 0xf59e0b, 0x1e293b);
    gridHelper.position.y = 0.2;
    scene.add(gridHelper);

    // Shadow Projection Enclosure (Cyclorama Room for dramatic wall & floor shadow projection)
    const roomGroup = new THREE.Group();
    const roomMat = new THREE.MeshStandardMaterial({
      color: 0x1e293b,
      roughness: 0.88,
      metalness: 0.05,
      side: THREE.BackSide
    });

    // Cylindrical room enclosure so shadows project 360 degrees around the lamp
    const roomWallGeo = new THREE.CylinderGeometry(520, 520, 750, 72, 1, false);
    roomWallGeo.translate(0, 374, 0);
    const roomWallMesh = new THREE.Mesh(roomWallGeo, roomMat);
    roomWallMesh.receiveShadow = true;
    roomGroup.add(roomWallMesh);

    // Pedestal / Table surface
    const floorGeo = new THREE.CircleGeometry(520, 72);
    floorGeo.rotateX(-Math.PI / 2);
    const floorMat = new THREE.MeshStandardMaterial({
      color: 0x161f30,
      roughness: 0.85,
      metalness: 0.05
    });
    const floorMesh = new THREE.Mesh(floorGeo, floorMat);
    floorMesh.receiveShadow = true;
    roomGroup.add(floorMesh);

    scene.add(roomGroup);

    // --- 3. Lighting & High-Precision Point Shadow Source ---
    const ambientLight = new THREE.AmbientLight(0xdbeafe, 0.18);
    scene.add(ambientLight);

    const studioKeyLight = new THREE.DirectionalLight(0xffffff, 0.35);
    studioKeyLight.position.set(200, 380, 260);
    scene.add(studioKeyLight);

    // Internal Lamp Bulb (Omnidirectional PointLight with hi