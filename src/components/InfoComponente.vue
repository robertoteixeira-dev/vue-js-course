<template>
    <div>
        <p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
        <p v-else>Não em busca de novas oportunidades</p>
        <p>Eu utilizo as seguintes tecnologias:</p>
        <ul>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>VueJS</li>
        </ul>
        <p v-show="mostrar_email">Mande uma mensagem para: {{ email }}</p>
    </div>
</template>

<script>
export default {
    name: 'InfoComponente',
    data() {
        return {
            esta_trabalhando: true,
            mostrar_email: true,
            email: "learning@gmail.com"
        }
    }
}
</script>