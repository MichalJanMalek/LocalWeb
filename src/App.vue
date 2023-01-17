<template>
      <div class="app">
            <Sidebar />

            <router-view />
      </div>
</template>

<script setup>
import Sidebar from './components/side-bar.vue'
</script>


<style lang="scss">
:root {
	--primary: #ff0066; //3500d3 //ff005d
	--primary-alt: #820030; //240090
	--grey: #718692;
	--dark: #282828; //282828
	--dark-alt: #ffffff;//e3e2df
	--light: #ffffff;
	--sidebar-width: 200px;
}
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: 'Fira sans', sans-serif;
}
body {
	background: var(--light);
}
button {
	cursor: pointer;
	appearance: none;
	border: none;
	outline: none;
	background: none;
}
.app {
	display: flex;
	main {
		flex: 1 1 0;
		padding: 2rem;
		@media (max-width: 1024px) {
			padding-left: 6rem;
		}
	}
}
</style>
