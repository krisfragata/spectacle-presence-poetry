<script>
	import Christian from "./Christian.svelte";
import Furniture from "./furniture.svelte";
   import arrowLeft from '../../assets/arrow-left.svg'
    
</script>

<main class="flex flex-col justify-center">
     <a href="/" class="w-[30px] pl-2">
        <img src={arrowLeft} alt="arrow-left"/>
    </a>
        <Furniture/>
    <Christian/>
</main>