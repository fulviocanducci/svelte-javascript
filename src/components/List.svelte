<script>
    let numbers = [];
    const handleClick = () => {
        numbers = [
            ...numbers, Math.random().toFixed(2)
        ];
    }
</script>

<h1>List</h1>
<button on:click={handleClick}>Add</button>
<ul>
    {#each numbers as item}
        <li>{item}</li>
    {/each}    
</ul>