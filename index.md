---
layout: main
---
<main class="home">
	<div class="container">
		<section class="home-section" id="info">
			<div class="section-title">
				<h1>{Distributed} <br>Digital Research <br>Infrastructures <br>for the Humanities</h1>
			</div>
			<div class="columns">
				<div class="column info-widget">
					<span class="fas fa-code-branch"></span>
					<h2>Harmonization</h2>
					<p>The Consortium for Open Research Data in the Humanities is committed to harmonizing data standards and infrastructures to facilitate interoperability and the cross-pollination of research data.</p>
				</div>
				<div class="column info-widget">
					<span class="fas fa-sitemap"></span>
					<h2>Integration</h2>
					<p>The consortium aims to contribute to a vibrant culture of open scholarship and collaboration among researchers, disrupting barriers posed by proprietary databases where information is kept in silos.</p>
				</div>
				<div class="column info-widget">
					<span class="fas fa-lock-open"></span>
					<h2>Open</h2>
					<p>We seek to advance the global paradigm shift in publishing models, away from inward looking, closed and costly strategies, towards an open and inclusive model that encourages collaboration and open-access.</p>
				</div>
			</div>
		</section>
		<section class="home-section" id="partners">
			<div class="section-title">
				<h1>Partners</h1>
				<!-- <p>We seek to advance the global paradigm shift in publishing models, away from inward looking, closed and costly strategies, towards an open and inclusive model that encourages collaboration and open-access.</p> -->
			</div>
			<div id="partners-list">
				<div class="partner"><img src="assets/images/bibliotheca-hertziana.svg" alt="Bibliotheca Hertziana"></div>
				<div class="partner"><img src="assets/images/villa-i-tatti.svg" alt="Villa I Tatti"></div>
				<div class="partner"><img src="assets/images/universitat-zurich.svg" alt="Universitat Zurich"></div>
				<div class="partner"><img src="assets/images/max-planck.svg" alt="Max Planck Institute for the History of Science"></div>
				<div class="partner"><img src="assets/images/eth-zurich.svg" alt="ETH Zurich"></div>
			</div>
		</section>
		<!--
				<section class="home-section" id="news">
						<div class="section-title">
								<h1>News</h1>
						</div>
						<div class="home-posts-container columns">
								{% assign count = 0 %}
								{% for post in site.posts %}
										{% if count == 3 %}{% break %}{% endif %}
										<article class="post column">
												<a href="{{ post.url | prepend: site.baseurl }}" class="post-image">
														<img src="{{ post.hero }}">
												</a>
												<a href="{{ site.url }}{{ site.baseurl }}/category/{{ post.category }}" class="post-categories">
														{{ post.categories }}
												</a>
												<a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
														<h2 class="post-title">{{ post.title }}</h2>
												</a>
												<a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
														<p class="post-description">
																{{ post.introduction }}
														</p>
												</a>
										</article>
										{% assign count = count | plus:1 %}
								{% endfor %}
						</div>
						<div class="button-container">
								<a href="{{ site.url }}{{ site.baseurl }}/news/" class="button">News</a>
						</div>
				</section>
		-->
		<section class="home-section" id="collaborators">
			<div class="section-title">
				<h1>Collaborators</h1>
			<!--		<p>We seek to advance the global paradigm shift in publishing models, away from inward looking, closed and costly strategies, towards an open and inclusive model that encourages collaboration and open-access.</p>
-->
			</div>
			<div id="collab-list">
				<div class="partner"><img src="assets/images/crm.svg" alt="CRM"></div>
				<div class="partner"><img src="assets/images/researchspace.svg" alt="ResearchSpace"></div> 
				<div class="partner"><img src="assets/images/metaphacts.svg" alt="Metaphacts"></div>
			</div>
		</section>
	</div>
</main>
