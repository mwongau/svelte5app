<script>
  import { base } from "$app/paths";
  import '$lib/styles/style.css'
  import Header from '$lib/components/Header.svelte'
</script>

<Header />

<div class="nav" style="background-color: AliceBlue;">
<a href="{base}/">Home</a> &nbsp; &nbsp;
<a href="{base}/cv">CV</a> &nbsp; &nbsp;
<a href="{base}/photos">Photos</a> &nbsp; &nbsp;
<a href="{base}/privacy">Privacy</a>
<br />
</div>

<slot />


