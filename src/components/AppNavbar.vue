<template>
  <nav class="navbar">
    <img class="logo" src="@/assets/Logo.png" />
    <ul class="nav-links">
      <li>
        <a href="#notifications"
          ><img class="menu-icon" src="@/assets/notifications.svg"
        /></a>
      </li>
      <li>
        <a href="#settings"
          ><img class="menu-icon" src="@/assets/settings.svg"
        /></a>
      </li>
      <li>
        <a href="#logout"
          ><img class="menu-icon" src="@/assets/logout.svg"
        /></a>
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
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 17px;
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