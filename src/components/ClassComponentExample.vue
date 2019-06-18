<template>
  <div>reached</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      thing: 'test'
    };
  },
  beforeCreate() {
    console.log('I am beforecreated!');
  },
  created() {
    console.log('I am created!');
  },
  beforeMount() {
    console.log('right before the mount happens');
  },
  mounted() {
    console.log('I am now mounted!');
  },
  beforeDestroy() {
    console.log('before the component is destroyed');
  },
  destroyed() {
    console.log('the components gone.');
  }
}
</script>
