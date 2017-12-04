<template>
  	<div>
    	<itemContainer father-component="item"></itemContainer>
  	</div>
</template>

<script>
import itemContainer from '../../components/itemContainer'

export default {
	name: 'item',
  	components: {
      itemContainer
  	},
  	created(){
      //进入题目页面，开始计时
  		this.$store.commit('REMBER_TIME');
  	}
}

</script>

<style lang="less">


</style>
