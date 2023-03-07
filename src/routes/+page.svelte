<div id="envoltorio">
    <h1>Contador</h1>
    <div>{numero}</div>
    <Boton texto="Suma" accion={manexadorClickSuma}/>
    <Boton texto="Resta" accion={manexadorClickResta}/>
</div>

<script>

    import Boton from "./Boton.svelte";

    let numero = 0

    function manexadorClickSuma(){
        numero++
    }

    function manexadorClickResta(){
        numero--
    }

</script>

<style>

</style>