<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>테이블이다</h3>
    <table>
        <colgroup>
          <col width="25%"/>
          <col width="25%"/>
          <col width="25%"/>
          <col width="25%"/>
        </colgroup>
        <thead>
          <tr>
            <td>title</td>
            <td>name</td>
            <td>content</td>
            <td>date</td>
          </tr>
      </thead>
    </table>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
table{width:100%;}

</style>
