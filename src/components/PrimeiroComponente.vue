<template>
    <div>
        <h1>Olá Vue!</h1>
        <p>Meu nome é {{ nome }}</p>
    </div>
</template>

<script>
export default {
    name: 'PrimeiroComponente',
    data() {
        return {
            nome: "Roberto",
            profissao: "Programador"
        }
    }
}
</script>