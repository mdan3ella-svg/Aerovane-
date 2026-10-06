AEROVANE V4 | VERTASCAN | CONCEPTSBYDAN
FLYING PLATFORM CONCEPT

Launch the published website or serve this directory via HTTP. For local review:
python -m http.server 8000
then open http://localhost:8000. For GitHub Pages publish this directory at the root.
All model, image and JavaScript assets are included locally.

CONTROLS
Drag/pinch/scroll to inspect. Hero, low, pod detail and orthographic views.
Fan spool gradually accelerates four independent X-axis rotors. Lift/hover initiates
spring-damped height changes. Yaw turns the vehicle; turntable orbit gives continuous review.
Sound is optional and starts only after pressing Sound off. It synthesizes fan/motor airflow,
beeps and hydraulic movement cues. Optional haptics require device/browser support.
Escape settles the vehicle and spools down. R resets. Save view exports PNG.

SURFACES
Classic non-PBR materials retained. Eight configurable surface zones: framework, each
of four pods, fan blades, windshield and structural trim. Windshield defaults to opaque
glossy black. Colour, shininess, reflection and opacity are editable. Presets persist locally.
Sketch supports ivory, blueprint and graphite. Perspective occlusion uses SSAO; it is
disabled by default on smaller screens to reduce GPU load. No parallax-occlusion texture
shader is claimed: depth comes from actual 3D perspective, shadowing and screen-space AO.

GEOMETRY
Source was one merged mesh. Delivered GLB has six root assemblies: framework, four pods,
and a fan assembly containing four independent rotors. Outboard fan surfaces were rebuilt
with 14 swept blades per rotor. Pod housings stay stationary. The native GLB has four
rotation animation tracks. Partition boundaries can retain seams; this is not rebuilt CAD.
The portable model uses unlit colour materials; the viewer assigns classic Phong shading.

DIMENSIONS / FEASIBILITY
Length assumed 4.80m. Source proportional envelope approximately 3.20m wide x 1.31m high.
Two seats observed in reference. Rotor diameter approximately 0.66m. These are concept
estimates, not measured or fabrication dimensions. The fan axes shown are lateral:
vertical thrust routing or tilting would have to be designed for real hover.
Illustrative 850kg sizing case: ideal hover ~418kW, assumed losses ~700kW. Candidate
4x200kW drive budget and 60-80kWh battery are proposals, not validated performance.
Displayed rotor RPM is deliberately slowed for visual inspection, not operating RPM.

DELIVERABLES
AEROVANE-V4.glb; reference gallery; PDF dossier; dimensioned orthographic PNG;
vector CADD SVG with feature/silhouette edges (hidden edges retained); original SVG logo.

VALIDATION
Six scene assemblies and four independent rotor tracks checked with the GLTF loader.
Pod transforms verified stationary during rotor rotation. GLB validation and script/asset
checks performed. Browser visual/audio QA unavailable in this environment.
THIRD PARTY: Three.js MIT, vendor/LICENSE-three.txt. NASA research sources in dossier.
