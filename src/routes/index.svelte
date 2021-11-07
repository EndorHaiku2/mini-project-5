<script>
    import Header from "$lib/Header.svelte";
    import Section from "$lib/Section.svelte";
    let myInfo = {
     title: "Info",
   	 item1: "LZY",
   	 item2: 14,
   	 item3: "Telebort",
     title1: "Hobby",
     item4: "Drawing",
     item5: "Cooking",
     item6: "Badminton",
     title2: "Personality",
     item7: "Loud",
     item8: "Depends",
     item9: "Kind"}
</script>

<Header title={'My Biography'} />
<Section {...myInfo} />