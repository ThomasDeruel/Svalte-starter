<script>
    import MainSlot from "../components/MainSlot.svelte";
    export let pageName;
</script>

<MainSlot {pageName}>
    <p>This is the homepage</p>
    <label for="nom">nom</label>
</MainSlot>