<template>
  <div>Child2</div>
</template>

<script>
import log from '../mixins/log.js'

export default {
  data() {
    return {
      name: 'child2'
    }
  },
  mixins: [log]
}
</script>