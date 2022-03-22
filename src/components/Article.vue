<script>
export default {
  props: [
    'title',
    'author'
  ]
}
</script>

<template>
<div>
  <h2>{{ title }}</h2>
  <h3>{{ author }}</h3>
</div>
</template>