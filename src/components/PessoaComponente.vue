<template>
    <div>
        <h2>Esta é a descrição do {{ nome }}</h2>
        <InfoComponente />
    </div>
    
</template>

<script>
import InfoComponente from './InfoComponente.vue'
export default {
    name: 'PessoaComponente',
    data() {
        return {
            nome: "Roberto"
        }
    },
    components: {
        InfoComponente
    }
}
</script>