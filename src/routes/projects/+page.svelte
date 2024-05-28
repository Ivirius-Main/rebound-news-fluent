<script lang="ts">
	import { Metadata } from "$lib";
	import { IconButton, TextBlock } from "fluent-svelte";
	import { links } from "$data/links";
	let { github, youtube } = links;
</script>
<section class="centered-section">
    <TextBlock><h2>Rebound Projects</h2></TextBlock>
    <TextBlock>Discover all the projects by the Rebound Team on this page!</TextBlock>
</section>
<section class="project">
    <TextBlock><h3>Ivirius Text Editor Plus</h3></TextBlock>
    <TextBlock>A versatile, modern, Fluent text editor. Available for $1.09 off the MS Store.</TextBlock>
    <TextBlock><b>Developed by:</b> Ivirius, ErrorTek, TheDevil</TextBlock>
</section>
<style>
 .centered-section
  {
    text-align: center;
    margin: 0 auto;
    padding: 50px;
    max-width: 1250px;
  }
  </style>