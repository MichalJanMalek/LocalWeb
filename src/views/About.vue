<template>
    <main class="about-page">
        <h1>About Michal</h1>
        <div align-items="center" class="flex">
            <a href="https://github.com/MichalJanMalek" class="button">
				<Icon class="material-icons" inline icon="mdi:github" style="color: white;" width="35"  height="35"/>
			</a>
			<a href="https://www.linkedin.com/in/michaljmalek/" class="button">
				<Icon class="material-icons" inline icon="mdi:linkedin" style="color: white;" width="35"  height="35"/>
			</a>
            <h2>Download my Resume</h2> 
            <a href="/MichalMalek_Resume.pdf" download>
                <Icon class="material-icons" inline icon="material-symbols:sim-card-download" style="color: white;" width="35"  height="35"/>
            </a>
        </div>
        <p>I am a software developer based in Chicago. I am currently a student at the Illinois Institute of Technology, studying Computer Science. I have experience with a variety of programming languages and frameworks, including Java, C, Python, JavaScript, React, and Vue. I am currently looking for a full-time position after graduating in May 2023.
        </p>
    </main>
</template>

<script>
import { Icon } from '@iconify/vue';
export default {
	components: {
		Icon,
	},
};
</script>


<style lang="scss" scoped>
main {
	color: var(--light);
	background-color: var(--primary);
}
.flex {
    display: flex;
    align-items: center;
}
</style>