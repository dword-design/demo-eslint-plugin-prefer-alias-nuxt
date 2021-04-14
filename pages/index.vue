<template>
  <div>{{ foo }}</div>
</template>

<script>
import foo from '../model/foo'

export default {
  computed: {
    foo: () => foo,
  }
}
</script>
