<template>
  <div>
    <t-header />
    <t-body />
    <t-footer />
  </div>
</template>

<script>
import THeader from '~/components/THeader.vue'
import TBody from '~/components/TBody.vue'
import TFooter from '~/components/TFooter.vue'

export default {
  components: {
    THeader,
    TBody,
    TFooter
  }
}
</script>

<style>

</style>
