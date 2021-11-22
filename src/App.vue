<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <div class="area-box">
      <div class="box">
        <div class="box-left">
          <img class="img" src="https://d3v0px0pttie1i.cloudfront.net/uploads/user/avatar/36305/9529ef09.jpeg" alt="luiz tanure">
          <h4 class="name">luiz tanure</h4>
          <h1 class="title">
            Interview call
          </h1>
          <p class="desc">
          </p>
          </div>
        <div class="box-right">
            <h1 class="title2">
            Duration
            </h1>
            <a class="btn" href="https://calendly.com/letanure/call-15-minutes">15 minutes</a>
            <a class="btn" href="https://calendly.com/letanure/call-30-minutes">30 minutes</a>
            <a class="btn" href="https://calendly.com/letanure/call-45-minutes">45 minutes</a>
            <a class="btn" href="https://calendly.com/letanure/call-60-minutes">60 minutes</a>
            <a class="btn" href="https://calendly.com/letanure/call-90-minutes">90 minutes</a>
        </div>
      </div>
    </div>
    
  </div>
</template>

<style>
*, *::before, *::after {
    box-sizing: inherit;
}
body {
    font-family: "Proxima Nova",sans-serif;
    font-size: 16px;
    line-height: 1.5;
    color: var(--text-color, #1A1A1A);
    word-break: break-word;
    overflow-wrap: break-word;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    margin: 0;
    background-color: #fbfcfd;
}
body>* {
    position: relative;
    z-index: 0;
}
.container {
  background-color: #fbfcfd;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
.area-box{
  flex: 1 1 auto;
  padding: 5px;
  margin-bottom: 30px;
  display: flex;
  justify-content: center;
}
@media (min-device-width: 480px) { 
  .area-box{
    padding: 0;
    margin-top: 66px;
  }
}

.box{
  border: 1px solid var(--text-color-level3, rgba(26, 26, 26, 0.1));
  border-radius: 8px;
  box-shadow: 0 1px 8px 0 rgb(0 0 0 / 8%);
  display: flex;
  max-width: 800px;
  background: #fff;
  flex-direction: column;
}
@media (min-device-width: 480px) { 
  .box{
    flex-direction: row;
  }
}
.box-left{
  display: flex;
  flex-direction: column;
  min-width: 300px;
  transition: all 0.22s ease-out;
  position: relative;
  padding: 14px;
}
@media (min-device-width: 480px) { 
  .box-left{
    width: 50%;
    border-right: 1px solid var(--text-color-level3, rgba(26, 26, 26, 0.1));
    padding: 28px;
  }
}
.img {
  width: 65px;
  height: 65px;
  margin-bottom: 10px;
  border-radius: 50%;
  border: 0;
  display: inline-block;
  margin: 0 auto;
}
@media (min-device-width: 480px) { 
  .img {
    margin: 0;
  }
}
.name {
    padding-right: 10px;
    margin: 0 0 3px;
    color: var(--text-color-level2, rgba(26, 26, 26, 0.6));
    font-weight: bold;
    font-size: 16px;
    line-height: 24px;
    text-align: center;
}
@media (min-device-width: 480px) { 
  .name {
    text-align: left;
  }
}
.title {
  padding-right: 10px;
    margin: 0;
    font-weight: bold;
    font-size: 28px;
    line-height: 32px;
    margin-bottom: 24px;
    text-align: center;
}
@media (min-device-width: 480px) { 
  .title {
    text-align: left;
  }
}
.title2{
  font-size: 20px;
}
.desc{
  margin: 0;
    padding: 0;
    font-size: 16px;
    font-family: 'Proxima Nova', sans-serif;
    line-height: 1.5;
}
.box-right{
  flex: 1 1 50%;
  transition: all 0.22s ease-out;
  display: flex;
  flex-direction: column;
  padding: 14px;
}
@media (min-device-width: 480px) { 
  .box-right{
    padding: 28px;
    width: 50%;
  }
}
.btn{
  background-color: transparent;
  border-radius: 4px;
  color: inherit;
  color: var(--primary-color, rgb(0, 107, 255));
  cursor: pointer;
  font: inherit;
  font-weight: bold;
  margin: 8px;
  padding: 0;
  position: relative;
  text-align: center;
  text-decoration: none;
  transition: all 0.1s ease;
  vertical-align: top;
  border: 1px solid var(--primary-color-level2, rgba(0, 107, 255, 0.5));
  padding: 8px;
}

.btn:hover{
  border-color: var(--primary-color, rgb(0, 107, 255));
  border-width: 2px;
  padding: 7px;
}

</style>
