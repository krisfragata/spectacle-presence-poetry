<script>
	import Title from "./Title.svelte";
   import arrowLeft from '../../assets/arrow-left.svg'
    
</script>

<main class="flex flex-col justify-center pl-50">
        <a href="/" class="w-[30px] pl-2">
        <img src={arrowLeft} alt="arrow-left"/>
    </a>
    <Title/>
</main>