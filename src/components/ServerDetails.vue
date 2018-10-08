<template>
  <div>
    <p>Server Details: {{ status}}</p>
    <button @click = "changeStatus">Change Status</button>

  </div>
</template>

<script>
export default {
  name: 'ServerDetails',
  data: function () {
    return {
      status: 'critical'
    }
  },
  methods: {
    changeStatus() {
      this.status = 'Normal';
    }
  }
}

</script>

<style scoped>
div{
  display: flex;
  flex-direction: column;
  margin: 0 .5rem .5rem .5rem;
}
p{
  width: 50%;
  text-align: left;
  margin: 0 .5rem .5rem .5rem;
}
button{
  background-color: #8f8f8f;
  color: #ffffff;
  margin: .5rem .5rem;
}
button:hover {
  background-color: #6b6b6b;
}
</style>
