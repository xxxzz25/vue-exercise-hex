<template>
  <div>
    <a href="#" @click.prevent="signout">登出</a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  methods:{
    signout(){
      const api = " https://vue-course-api.hexschool.io/logout";
      const vm = this;
      this.$http.post(api).then(response => {
        console.log(response.data);
        if(response.data.success){
          vm.$router.push('/login');
        }
      });
    },
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
