<template>
  <div class="footer">
      <div class="container">
        <p class="c">Copyright © {{new Date().getFullYear()}} · PNGCOOL</p>
        <!-- <div class="c">
            <a href="https://beian.miit.gov.cn/"><img src="@/assets/images/icp.png"><span></span></a>
        </div> -->
      </div>
  </div>
  
</template>

<script>
export default {
    name: "FootBox"
}
</script>

<style lang="less" scoped>
.footer{
  position: relative;
  text-align: center;
  .c {
    color: #fff;
    margin-top: 20px;
    font-size: 12px;
    letter-spacing: .1em;
    opacity: .8;
    a {
        color: #fff;
        display: flex;
        align-content: space-around;
        justify-content: center;
        img{height: 1rem; padding-right: 5px;}
    }
  }
}
</style>