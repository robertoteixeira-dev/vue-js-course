<template>
  <PrimeiroComponente/>
  <LifeCycle/>
  <PessoaComponente/>
  <FormComponente/>
</template>

<script>
import LifeCycle from './components/LifeCycle.vue'
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import PessoaComponente from './components/PessoaComponente.vue'
import FormComponente from './components/FormComponente.vue'


export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    PessoaComponente,
    FormComponente
  }
}
</script>




