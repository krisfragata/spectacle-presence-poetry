<script>
	import Christian from "./Christian.svelte";
import Furniture from "./furniture.svelte";
   import arrowLeft from '../../assets/arrow-left.svg'
	import Todo from "./todo.svelte";
    
</script>

<main class="flex flex-col justify-center">
     <a href="/" class="w-[30px] pl-2">
        <img src={arrowLeft} alt="arrow-left"/>
    </a>
        <Furniture/>
        <Todo/>
    <Christian/>
</main>