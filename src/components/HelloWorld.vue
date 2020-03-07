<template>
  <div>
    <b-tabs position="is-centered" class="block">
      <b-tab-item label="Pictures"></b-tab-item>
      <b-tab-item label="Music"></b-tab-item>
      <b-tab-item label="Videos"></b-tab-item>
    </b-tabs>

    <b-field label="Select timepicker">
        <b-timepicker
            placeholder="Type or select a date..."
            icon="clock"
            editable>
        </b-timepicker>
    </b-field>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },data() {
    return {
      text:''
    }
  },
  methods: {
    
    
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
