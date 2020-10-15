<script>
    export let count;
    function incrementation(){
        return count +=1
    }
    $: double = count*2
</script>

<button on:click={incrementation}>
    click:{count}fois
</button>