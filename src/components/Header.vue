<template>
  <header>
    <div class="content">
      <!-- Left -->
      <ul class="left">
        <li>
          <img src="@/assets/img/logo.png" alt="logo" width="80" />
        </li>
      </ul>

      <!-- Right -->
      <ul class="right">
        <li>
          <router-link to="/">Movies</router-link>
        </li>
        <li>
          <router-link to="/tv">TV Shows</router-link>
        </li>
      </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #fff;
  color: #111;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 80px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 4%;
  z-index: 10;
  box-shadow: 4px 2px 16px rgba(0, 0, 0, 0.04);

  .content {
    display: flex;
    justify-content: space-between;
    align-items: center;

    /* Left */

    /* Right */
    .right {
      display: flex;

      li {
        margin-left: 16px;

        a {
          color: #111;
        }
      }
    }
  }
}
</style>
