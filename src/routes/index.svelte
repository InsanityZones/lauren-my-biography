<script>
    import Header from "$lib/Header.svelte";
    import Section from "$lib/Section.svelte";
    import Footer from "$lib/Footer.svelte";
    let myInfo = {
    title: "Info",
    item1: "Lauren Chua Wei Qian",
    item2: 13,
    item3: "Chung Ling Private High School",
}
    let myHobbies = {
    title: "Hobbies",
    item1: "Surfing the Internet",
    item2: "Drawing",
    item3: "Daydreaming",
}
    let myPersonality = {
    title: "Personality",
    item1: "Stubborn",
    item2: "Eccentric",
    item3: "Rebellious",
}
</script>

<Header title={"My Biography"}/>
<Section {...myInfo}/>
<Section {...myHobbies}/>
<Section {...myPersonality}/>
<Footer gitHub={"https://github.com/InsanityZones/lauren-my-biography"}/>