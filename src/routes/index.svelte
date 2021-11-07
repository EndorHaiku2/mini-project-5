<script>
    import Header from "$lib/Header.svelte";
    import Section from "$lib/Section.svelte";
    let myInfo = {
     title: "Info",
   	 item1: "LZY",
   	 item2: "14",
   	 item3: "Telebort"}

    let myHobby = {
     title: "Hobby",
   	 item1: "Drawing",
   	 item2: "Badminton",
   	 item3: "More drawing"}

    let myPersonality = {
     title: "Personality",
   	 item1: "Loud",
   	 item2:  "Happy",
   	 item3: "Usually carefree"}      
</script>

<Header title={'My Biography'} />
<Section {...myInfo} />