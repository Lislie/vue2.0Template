<template>
  <div class="header">
    <div class="content-warpper">
      <div class="avatar">
        <img :src="seller.avatar"width="64" height="64 ">
      </div>
      <div class="content">
        <div class="title">
          <span class="brand"></span>
        </div>
      </div>
    </div>
    <div class="bullentin-wrapper"></div>
  </div>

</template>

<script type="text/ecmascript-6">

  export default {
    props: {
      seller: {

      }
    }

  }

</script>

<style lang="stylus" rel="stylesheet/stylus">

</style>
