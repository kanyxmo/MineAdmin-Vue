<!--
 - MineAdmin is committed to providing solutions for quickly building web applications
 - Please view the LICENSE file that was distributed with this source code,
 - For the full copyright and license information.
 - Thank you very much for using MineAdmin.
 -
 - @Author X.Mo<root@imoi.cn>
 - @Link   https://gitee.com/xmo/mineadmin-vue
-->
<template>

  <st-welcome />
  <st-count />
  <st-login-chart />

  <div class="block lg:flex">
    <st-announced />
    <st-mineadmin />
  </div>
</template>

<script setup>
  import stCount from './components/st-count.vue'
  import stWelcome from './components/st-welcome.vue'
  import stLoginChart from './components/st-loginChart.vue'
  import stMineadmin from './components/st-mineadmin.vue'
  import stAnnounced from './components/st-announced.vue'
</script>

