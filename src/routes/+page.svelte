<script>
    import { HelloWorld, SearchBar } from "@shannafdnd/fdnd-components";
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<HelloWorld />

<div class="wrapper">
    <SearchBar placeholder="Zoeken..." resultsPage="/zoeken" name="searchTerm" />
</div>

<style>
    .wrapper {
        width: 50%;
        display: flex;
        justify-content: end;
    }
</style>