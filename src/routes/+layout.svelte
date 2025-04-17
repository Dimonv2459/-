<script lang="ts">
    import Header from "$lib/components/Header.svelte"
import { Container, Styles } from "$sve"
    let {children} = $props()
</script>

<Styles/>
<Container>
    <Header/>
    {@render children()}
</Container>
