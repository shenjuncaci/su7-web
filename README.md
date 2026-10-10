SU7 风格轿跑 3D 模型（参照公开外观比例的近似模型，非小米官方数据，无车标）
- su7.glb: Draco 压缩版 (网页用, model-viewer 自动解码)
- su7_nodraco.glb: 未压缩版 (兼容性最好)
- index.html: 展示页。需通过 http 服务打开: python3 -m http.server 然后访问 http://localhost:8000/
嵌入: <script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.0.0/model-viewer.min.js"></script>
<model-viewer src="su7.glb" camera-controls auto-rotate shadow-intensity="1" environment-image="neutral"></model-viewer>
