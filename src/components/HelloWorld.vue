<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>在dev分支上进行开发
      <span>我第二次修改了代码</span>
    </p>
    <h1>master上的代码————————————————————————</h1>
    <h2>dev分支添加代码</h2>
  <div>李易峰最棒！！！</div>
<!-- 正常情况下的合并  添加dev分支时/切换分支时 跟master一样，再次添加别的内容时   不冲突 -->
   <h3>master分支开发结束，准备在dev上进行开发</h3>
   <p>dev分支开发</p>
   <p>dev分支开发</p>
   <p>dev分支开发</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
