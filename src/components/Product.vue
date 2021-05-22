<template>
    <div>
  <b-card
    title="Card Title"
    v-bind:img-src="imgsrc"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      {{ text }}
      {{ imgsrc }}
    </b-card-text>

    <b-button href="#" variant="primary">放入購物車</b-button>
  </b-card>
</div>
</template>

<script>
export default {
  name: 'Product',
  props: {
    msg: String,
    text: String,
    imgsrc : String
  }
}
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
</style>

<!-- 註：v-bind:class="{'class 名稱' : vue 屬性名稱}"參考書p.4-28，指定被綁定時的處理動作-->
<!-- 註：props目的在傳遞資料值 用陣列取值 參考書p.4-39-->