<script>
  import { base } from "$app/paths";
  import '$lib/styles/style.css'
</script>

<div class="header">
<h1>M Wong</h1>
<h3>My personal site</h3>
<br />
</div> 

<div class="nav" style="background-color: AliceBlue;">
<a href="{base}/">Home</a> &nbsp; &nbsp;
<a href="{base}/cv">CV</a> &nbsp; &nbsp;
<a href="{base}/photos">Photos</a> &nbsp; &nbsp;
<a href="{base}/privacy">Privacy</a>
<br />
</div>

<slot />

<style>
.header {
	background-color: Lavender;
	color: purple;
	padding: 5px;
}
</style>
