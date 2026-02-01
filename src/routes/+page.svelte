<script>
	const w = 1920;
	const h = 1080;
	const src = '../images/bliss.png';
</script>

<!-- inline styles but no variables for property names -->
<div id="desktop" class="desktop" style="background-image: url({src});
											background-size: 100%;
		 									width: {w}px;
											height: {h}px">
    <button on:click={null}>Roll dice</button>

    <meta charset="utf-8">
    <title>My first three.js app</title>
    <style>
      body { margin: 0; }
    </style>
    <script type="module" src="lib/three/threecontroller.js"></script>

</div>
