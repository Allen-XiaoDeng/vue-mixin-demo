<template>
  <div>Child1</div>
</template>

<script>
import log from '../mixins/log.js'

export default {
  data() {
    return {
      name: 'Child1'
    }
  },
  created() {
    console.log('Child 1 的 created')
  },
  mixins: [log]
}
</script>
