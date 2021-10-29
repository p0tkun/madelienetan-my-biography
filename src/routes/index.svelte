<script>
    import Header from "$lib/Header.svelte";
    import Section from "$lib/Section.svelte";

    let myInfo = {
    title: "Info",
    item1: "Tan Mei Wen",
    item2: 14,
    item3: "WMSPI",
    }

</script>
<Header title = "My Biography" />
<Section {...myInfo} />