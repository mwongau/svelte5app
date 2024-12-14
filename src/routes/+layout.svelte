<script>
  import { base } from "$app/paths";
</script>

<div class="MyHeader" style="background-color: AliceBlue; color: purple">
<h1>M Wong</h1>
<h3>My personal site</h3>
<br />
</div> 

<div class="nav" style="background-color: LightGray;">
<a href="{base}/">Home</a> &nbsp; &nbsp;
<a href="{base}/cv">CV</a> &nbsp; &nbsp;
<a href="{base}/privacy">Privacy</a>
<br />
</div>

<slot />

<style>
</style>