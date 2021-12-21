<template>
  <div id="app">
    <VueScrollActiveMenu tag="nav" :offset="72">
		<div class="container">
			<ul>
				<li class="home"><a class="scroll-active-item home active" href="#home">Home</a></li>
				<li ><a class="scroll-active-item about" href="#about">About</a></li>
				<li ><a class="scroll-active-item contact" href="#contact">Contact</a></li>
				<li ><a class="scroll-active-item footer" href="#footer">Footer</a></li>
			</ul>	    		
		</div>
    </VueScrollActiveMenu>

	<div>
		<section class="scroll-active-section" id="home">
		<h1>Home</h1>
		</section>
		<section class="scroll-active-section" id="about">
		<h1>About</h1>
		</section>
		<section class="scroll-active-section" id="contact">
		<h1>Contact</h1>
		</section>
		<section class="scroll-active-section" id="footer">
		<h1>Footer</h1>
		</section>
		</div>
	</div>
</template>

<script>
import '@/assets/css/app.css';
import VueScrollActiveMenu from './components/VueScrollActiveMenu.vue'

export default {
  name: 'App',
  components: {
    VueScrollActiveMenu
  }
}
</script>
