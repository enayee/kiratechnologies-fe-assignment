<template>
  <nav class="navbar">
    <img class="logo" src="@/assets/Logo.png" />
    <ul class="nav-links">
      <li>
        <a><img class="menu-icon" src="@/assets/notifications.svg" /></a>
      </li>
      <li>
        <a><img class="menu-icon" src="@/assets/settings.svg" /></a>
      </li>
      <li>
        <a><img class="menu-icon" src="@/assets/logout.svg" /></a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "AppNavbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  max-width: 1280px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 17px;
  height: 90px;
  box-sizing: border-box;
  .logo {
    width: 170px;
  }
  .nav-links {
    list-style: none;
    display: flex;
    li {
      margin: 0 10px;
      .menu-icon {
        width: 42px;
      }
    }
  }
}
</style>
