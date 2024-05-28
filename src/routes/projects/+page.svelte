<script lang="ts">
	import { Metadata } from "$lib";
	import { IconButton, TextBlock } from "fluent-svelte";
	import { links } from "$data/links";
	let { github, youtube } = links;
</script>
<section class="centered-section">
    <TextBlock variant="titleLarge">Rebound Projects</TextBlock><br>
    <TextBlock>Discover all the projects by the Rebound Team on this page!</TextBlock>
</section>
<section class="project">
    <TextBlock variant="title">Ivirius Text Editor Plus</TextBlock><br>
    <TextBlock>A versatile, modern, Fluent text editor. Available for $1.09 off the MS Store.</TextBlock><br>
    <TextBlock><b>Developed by:</b> Ivirius, ErrorTek, TheDevil</TextBlock>
</section>
<section class="project">
    <TextBlock variant="title">Ivirius Text Editor</TextBlock><br>
    <TextBlock>A versatile, modern, Fluent text editor. Available for free off the MS Store and open soruce on GitHub. The latest releases are released on GitHub!</TextBlock><br>
    <TextBlock><b>Developed by:</b> Ivirius, ErrorTek</TextBlock>
</section>
<section class="project">
    <TextBlock variant="title">UltraTextEdit UWP Plus</TextBlock><br>
    <TextBlock>Modern, Fluent, Fast</TextBlock><br>
    <TextBlock><b>Developed by:</b> ErrorTek, Ivirius</TextBlock>
</section>
<style>
 .centered-section
  {
    text-align: center;
    margin: 0 auto;
    padding: 50px;
    max-width: 1250px;
  }
  .project {
 padding: 15px;
  }
  </style>