<template>
  <div :class="['c-icon', {
    [`c-icon${name}`] : name.length
  }]"></div>
</template>
<script>
export default {
  props: {
    name: {
      type: String
    }
  }
}
</script>