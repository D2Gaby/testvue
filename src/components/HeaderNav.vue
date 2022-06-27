<template>
  <div class="HeaderNav">
    <h1>je suis un titre</h1>
    <ul>
        <li>
            <a href="">testp1</a>
        </li>
        <li>
            <a href="">testp2</a>
        </li>
        <li>
            <a href="">1test</a>
        </li>
        <li>
            <a href="">2tests</a>
        </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HeaderNav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.HeaderNav{
    background-color: blue;
    padding: 20px;
}
h1 {
  margin: 40px 0 0;
  
}
ul {
    display: flex;
  align-items: center;
  text-align: center;
  align-content: center;
  justify-content: center;
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
    text-align: center;
  background-color: lime;
  padding: 5px;
}
a {
  color: #c30000;
}
</style>
