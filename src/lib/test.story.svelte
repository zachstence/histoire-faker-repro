<script>
    import { faker } from '@faker-js/faker'

    export let Hst;

    let someBoolean = false
</script>

<Hst.Story>
    <svelte:fragment slot="controls">
        <Hst.Checkbox title="someBoolean" bind:value={someBoolean} />
    </svelte:fragment>
</Hst.Story>