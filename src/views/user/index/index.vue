<template>
	<div id="app">
		user 
	</div>
</template>
<script>
export default {
  data() {
    return {
    	webname:5464,
		'list':[{
			'id':0,
			'name':'alert弹窗',
			'url':'../vuxDemo/alert.html'
		},{
			'id':1,
			'name':'Calendar时间选择',
			'url':'../vuxDemo/calendar.html'
		},{
			'id':2,
			'name':'button按钮',
			'url':'../vuxDemo/button.html'
		}]
    }
  },
  //实例初始化最之前，无法获取到data里的数据
  beforeCreate(){
  	
  	
  },  
  //在挂载开始之前被调用
  beforeMount(){
  	
  
  }, 
  //已成功挂载，相当ready()
  mounted(){
  
  
	
  },
  //相关操作事件
  methods: {
      
  }
}
</script>

<style>

</style>
