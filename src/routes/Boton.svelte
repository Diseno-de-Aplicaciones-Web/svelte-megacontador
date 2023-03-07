<button on:click={manexadorClick}>{texto} ({numero})</button>

<script>
    export let texto
    export let accion
    let numero = 0

    function manexadorClick() {
        numero++
        accion()
    }
</script>