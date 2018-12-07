<template>
	<header id="header" class="header">
		<div class="row center small-full medium-full large-22">
			<div class="column">
				<div class="header__logo">
					<nuxt-link class="header__logo-link" to="/">
						<!-- <div :style="`background-image: url(${logo})`" class="logo"/> -->
					</nuxt-link>
				</div>
				<nav class="main-nav">
					<ul class="main-nav__list">
						<li class="main-nav__item">
							<nuxt-link to="/biography" class="main-nav__link">
								<span class="main-nav__text">Biography</span>
							</nuxt-link>
						</li>
						<li class="main-nav__item">
							<nuxt-link to="/discography" class="main-nav__link">
								<span class="main-nav__text">Discography</span>
							</nuxt-link>
						</li>
						<li class="main-nav__item">
							<nuxt-link to="/news" class="main-nav__link">
								<span class="main-nav__text">News</span>
							</nuxt-link>
						</li>
						<li class="main-nav__item">
							<nuxt-link to="/media" class="main-nav__link">
								<span class="main-nav__text">Media</span>
							</nuxt-link>
						</li>
						<li class="main-nav__item">
							<nuxt-link to="/tour" class="main-nav__link">
								<span class="main-nav__text">Tour</span>
							</nuxt-link>
						</li>
						<li class="main-nav__item">
							<nuxt-link to="/merch" class="main-nav__link">
								<span class="main-nav__text">Merch</span>
							</nuxt-link>
						</li>
						<li class="main-nav__item">
							<nuxt-link to="/contact" class="main-nav__link">
								<span class="main-nav__text">Contact</span>
							</nuxt-link>
						</li>
					</ul>
				</nav>
			</div>
		</div>	
	</header>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import '~tools';

.header {
	// Header styles
}
</style>
