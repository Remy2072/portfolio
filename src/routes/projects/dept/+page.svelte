<div class="container">
	<div class="title">
		<p class="emoji">☀️</p>
		<h1>Weather Planner</h1>
		<small>DEPT®</small>
	</div>
	<img src="/img/weer.png" alt="Foto van de Planner" />
	<h3>Bekjik hier</h3>
	<a href="https://github.com/Remy2072/dept-weather-planner" target="_blank">Github</a>
	<a href="https://dept-weather-planner.onrender.com/" target="_blank">Live omgeving</a>
	<h3>Tech-stack</h3>
	<ul class="tech-stack">
		<li class="tech-stack-list ejs">EJS</li>
		<li class="tech-stack-list html">HTML</li>
		<li class="tech-stack-list css">CSS</li>
		<li class="tech-stack-list js">JavaScript</li>
		<li class="tech-stack-list node">Node</li>
		<li class="tech-stack-list figma">Figma</li>
	</ul>
	<h3>Het project</h3>
	<p>
		De DEPT® Weather Planner is een project dat ik heb gemaakt tijdens mijn opleiding bij FDND. Ik
		kreeg de opdracht van DEPT® om een Weather Planner te ontwikkelen. Het doel van dit project was
		om een planner te maken die gebruikers helpt bij het plannen van hun activiteiten op basis van
		het weer. De planner maakt gebruik van de eigen API van DEPT® om actuele weersinformatie op te
		halen, en biedt gebruikers de mogelijkheid om hun planning af te stemmen op de
		weersomstandigheden.
	</p>
</div>

<style>
	.tech-stack {
		margin-top: 0.5rem;
		display: flex;
		flex-wrap: wrap;
		gap: 0.5rem;
		align-items: center;
		list-style: none;
		padding: 0;
	}

	.tech-stack-list {
		font-size: 1rem;
		border-radius: 10rem;
		padding: 0.1rem 1rem;
		font-size: 1.25rem;
		margin-bottom: 0;
	}

	.html {
		background-color: #f16f4d;
		color: #ffffff;
	}

	.css {
		background-color: #489bef;
		color: #ffffff;
	}

	.js {
		background-color: #fff68f;
		color: #333333;
	}

	.node {
		background-color: #67b26f;
		color: #ffffff;
	}

	.ejs {
		background-color: #b08dff;
		color: #ffffff;
	}

	.figma {
		background-color: #ff9073;
		color: #ffffff;
	}

	* {
		font-size: 1.125rem;
		line-height: 1.5;
	}

	.container {
		display: flex;
		align-items: left;
		flex-direction: column;
		justify-content: center;
		padding: 0 10%;
		margin-bottom: 12.5rem;
	}

	.emoji {
		margin-top: 3.125rem;
		font-size: 3.75rem;
		text-shadow: var(--box-shadow-emoji);
		cursor: pointer;
	}

	.emoji:hover {
		animation: 1s tilt-n-move-shaking linear infinite;
	}

	@keyframes tilt-n-move-shaking {
		0% {
			transform: translate(0, 0) rotate(0deg);
		}
		25% {
			transform: translate(5px, 5px) rotate(5deg);
		}
		50% {
			transform: translate(0, 0) rotate(0eg);
		}
		75% {
			transform: translate(-5px, 5px) rotate(-5deg);
		}
		100% {
			transform: translate(0, 0) rotate(0deg);
		}
	}

	.title {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	h1 {
		font-size: 2.188rem;
	}

	small {
		margin-top: 10px;
		font-size: 1.25rem;
		font-weight: 300;
	}

	h3 {
		margin-top: 1.25rem;
		font-size: 1.125rem;
		color: var(--slate-blue);
	}

	img {
		margin-top: 1.25rem;
		border-radius: 15px;
		border: 3px solid var(--dusty-lavender);
	}

	ul {
		list-style-type: revert;
		padding-left: 1.25rem;
	}
	ul li {
		margin-bottom: 0.5em;
	}

	a {
		color: var(--tropical-cyan);
		text-decoration: underline;
		margin: 0;
	}

	@media (min-width: 600px) {
		.container {
			padding: 0 20%;
		}
	}

	@media (min-width: 900px) {
		.container {
			padding: 0 30%;
		}

		h1 {
			font-size: 3.125rem;
		}

		.tech-stack {
			flex-wrap: nowrap;
		}
	}

	@media (min-width: 1300px) {
		.container {
			padding: 0 35%;
		}
	}
</style>
