<template>
  <div id="dashboard">
    <section>
      <div class="col1">
        <p id="smart-title">slogan of the day</p>
        <p id="smart">Sometimes the questions are complicated, and the answers are simple</p>
      </div>
      <div class="col2">
        <div id="dash-items">
          <router-link to="/shopping"><div class="dash-item">Shopping List</div></router-link>
          <div class="dash-item">Cleaning Plan</div>
          <router-link to="/chat"><div class="dash-item">Chat</div></router-link>
        </div>
      </div>
    </section>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>

</style>