<script>
    import Header from "$lib/Header.svelte";
    import Section from "$lib/Section.svelte";
    import Footer from "$lib/Footer.svelte";
    

    let myInfo = {
    title: "Info",
    item1: "Tan Mei Wen",
    item2: 14,
    item3: "WMSPI",
    }
    let hobby = {
    title: "hobby",
    item1: "playing drums",
    item2: "playing games",
    item3: "chatting with friends",
    }
    let personality = {
    title: "personality",
    item1: "quiet",
    item2: "chaotic",
    item3: "brave",
    }


</script>
<Header title = "My Biography" />
<Section {...myInfo} />
<Section {...hobby} />
<Section {...personality} />
<Footer github="https://github.com/p0tkun" />
