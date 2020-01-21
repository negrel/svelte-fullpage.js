<main>
	<Fullpage {options}>
		<div id="section-1" class="section">
			<h1>svelte-fullpage.js</h1>
			<h2>Create Beautiful Fullscreen Scrolling Websites</h2>
		</div>
		<div id="section-2" class="section"></div>
		<div id="section-3" class="section"></div>
		<div id="section-4" class="section"></div>
	</Fullpage>
</main>

<script>
import Fullpage from 'svelte-fullpage.js';

const options = {
	anchors: ['page1', 'page2', 'page3', 'page4'],
	licenseKey: 'your license key'
};
</script>

<style>
.section {
	position: relative;
}

#section-1 {
	background-color: #ff5f45;
}

#section-1 h1 {
	position: absolute;
	top: 30%;
	left: 50%;
	transform: translate(-50%, -50%);
	font-size: calc(5vw + 2vh);
	white-space: nowrap;
}

#section-2 {
	background-color: #0798ec;
}

#section-3 {
	background-color: #fc6c7c;
}

#section-3 {
	background-color: #fec401;
}
</style>