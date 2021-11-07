<script>
    import Header from "$lib/Header.svelte";
    import Section from "$lib/Section.svelte";
    let myInfo = {
     title: "Info",
   	 item1: "LZY",
   	 item2: 14,
   	 item3: "Telebort",}
</script>
 
<Header title={"My Biography"}/>
<Section {...myInfo} />
