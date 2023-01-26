<template>
    <main class="home-page">
		<div>
			<h1 class="home_title">Michal Malek</h1>
			<p class = "text">This is my personal website to showcase my projects and to learn more about me. </p>
		</div>	
		<div>
<CCarousel controls indicators>
  <CCarouselItem>
    <img class="d-block w-100" src="/smartspace.png" alt="slide 1"/>
    <CCarouselCaption class="d-none d-md-block">
      <h5>First slide label</h5>
      <p>Some representative placeholder content for the first slide.</p>
    </CCarouselCaption>
  </CCarouselItem>
  <CCarouselItem>
    <img class="d-block w-100" src="/images/react.jpg" alt="slide 2"/>
    <CCarouselCaption class="d-none d-md-block">
      <h5>First slide label</h5>
      <p>Some representative placeholder content for the first slide.</p>
    </CCarouselCaption>
  </CCarouselItem>
  <CCarouselItem>
    <img class="d-block w-100" src="/images/angular.jpg" alt="slide 3"/>
    <CCarouselCaption class="d-none d-md-block">
      <h5>First slide label</h5>
      <p>Some representative placeholder content for the first slide.</p>
    </CCarouselCaption>
  </CCarouselItem>
</CCarousel>

		</div>
    </main>
</template>

<style lang="scss" scoped>
main, .home-page{
	background-color: var(--primary);
	color: var(--light);
}
.home_title{
	text-align: center;
	padding-bottom: 1rem;
	text-size : 7rem;
	font-family: 'Josefin Sans', sans-serif;
}
.text{
	text-align: left;
}
</style>