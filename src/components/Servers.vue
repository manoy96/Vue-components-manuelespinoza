<template>
  <ul>
    <li><v-icon>dns</v-icon><span>Server #1</span></li>
    <li><v-icon>dns</v-icon><span>Server #2</span></li>
    <li><v-icon>dns</v-icon><span>Server #3</span></li>
    <li><v-icon>dns</v-icon><span>Server #4</span></li>
    <li><v-icon>dns</v-icon><span>Server #5</span></li>
  </ul>
</template>

<script>
export default {
  name: 'Servers'
}
</script>

<style scoped>
  ul{
    display: flex;
    flex-direction: column;
    width: 50%;
    
  }
  ul li {
    list-style-type: none;
    border: solid #000 1px;
    text-align: left;
    padding: .5rem .5rem;
  }
  ul li:hover {
    background-color: #e0dfdf;
  }
  span{
    margin: .25rem 1rem;
  }
</style>

