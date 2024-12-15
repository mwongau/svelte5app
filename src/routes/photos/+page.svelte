<script>
import { base } from "$app/paths";

const des = [ "Australian Catholic University, Strathfield Campus, NSW, Australia",
		"University of Technology Sydney, Building 5",
		"Homebush Public School, Homebush, NSW, Australia"]
const alt = [ "acu", "uts", "hps"]
const images = ["acupy.jpg", "uts-bldg5.jpg", "hps.jpg"]  

let count = $state(0);

function select() {
   count +=1;
   if (count > images.length - 1) 
      {count = 0;}
}
</script>

<div>
   <h1>Photos</h1>
   <button onclick={select}> <b>Next photo</b></button>
   <br />

   
   <h4>{count+1}: {des[count]}</h4>
   <img src="{base}/{images[count]}" alt="{alt[count]}">   
</div>

<style>
img {
   max-width: 100%;
   height: auto;
}

h1 {
	color: purple;
}
</style>
