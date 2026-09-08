---
layout: landing
title: Plasma Research
description: Highlighted projects
image: assets/images/Plasmoids.jpg
tile_image: 
nav-menu: true
show_tile: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>(G)R(R)MHD simulations of plasma in extreme astrophysical environments</h2>
		</header>
		<p>Black holes are home to some of the most extreme environments in the Universe, and the highly relativistic plasma accreting onto black holes is the key to studying the them.  To simulate such systems, we use general relativistic magnetohydrodynamic (GRMHD) simulations, which treat the plasma as a fluid in curved spacetime.  While this approach models the global dynamics of an accreting black hole, it cannot capute the small scale microphysics responsible for some of the most interesting plasma processes, such as radiation.  This microphysical scale requires particle-in-cell (PIC) simulations, which treat the plasma as clusters of particles, but are computationally limitted to local domains neglecting the compact object and its gravity.  My research aims to introduce subgrid models to bridge the separation-of-scales gap between GRMHD and PIC by writing the macrophsyical outcomes of microphysical processes into global simulations.</p>
        <p>Here I highlight some selected first-author projects from my plasma astrophysics research.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{{ site.baseurl }}assets/images/pic08.jpg %" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Making Reconnection Cooler</h3>
				</header>
				<p>We add an energy and momentum sink term to the RRMHD equations coupled to an effective charge-starved resistivty prescription to model radiative losses due to inverse Compton cooling in a local-box reconnection layer.  Our sink term is able to reproduce macroscopic properties from kineitc simulations, including the fast reconnection rate, the temperature in the current sheet, and the bulk motions of the outflow.  Our results set the stage for more accurate reconnection sites in global simulations of black holes and neutron stars.</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ site.baseurl }}assets/images/pic09.jpg" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Resistive thin disk (work in progress)</h3>
				</header>
				<p>We simulate a cooled accretion disk around a black hole with effective charge-starved resistivity in the truncated state.  We wish to understand how the fast reconnection rate from charge-starved resistivity affects the flaring and flux erruptions in the disk.</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ site.baseurl }}assets/images/pic10.jpg" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>2-temperature reconnection (work in progress)</h3>
				</header>
				<p>We evolve an electron entropy equation with a resistive source term in an RRMHD simulation of a local-box reconnection layer for a physically-informed heating prescription between electrons and ions.</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>All publications</h2>
		</header>
		<p>Above I have provided in-depth descriptions of selected projects I have worked on.  For a full list of my publications, click the link below.</p>
		<ul class="actions">My publications</a></li>
		</ul>
	</div>
</section>

</div>