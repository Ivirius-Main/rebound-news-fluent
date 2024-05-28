<script lang="ts">
	import { Metadata } from "$lib";
	import { IconButton, TextBlock } from "fluent-svelte";
	import { links } from "$data/links";
	let { github, youtube } = links;
</script>
<section class="centered-section">
    <h1>Rebound Projects</h1>
    <TextBlock>Discover all the projects by the Rebound Team on this page!</TextBlock>
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