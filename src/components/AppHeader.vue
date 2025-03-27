<template>
  <div class="background">
    <div class="header-container">
      <div class="avatar-container">
        <img src="@/assets/Avatar.png" />
      </div>
      <div class="name-container">
        <div class="name">John Doe</div>
        <div class="online-time">Last online: 2 days ago</div>
      </div>
      <div class="button-container">
        <button class="action-button white">
          <img class="icon" src="@/assets/message.svg" />Send Message
        </button>
        <button class="action-button blue">
          <img class="icon" src="@/assets/add.svg" />Add Friend
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style lang="scss" scoped>
.background {
  background: #35bad8;
  height: 154px;
  .header-container {
    max-width: 1280px;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }
  .avatar-container {
    width: 148px;
    margin-right: 34px;
    margin-top: 40px;
    img {
      width: 100%;
    }
  }
  .name-container {
    color: #ffffff;
    text-align: left;
    margin-right: 28px;
    .name {
      font-size: 40px;
      font-weight: 700;
      margin-bottom: 6px;
    }
    .online-time {
      font-weight: 400;
      font-size: 14px;
      line-height: 130%;
    }
  }
  .button-container {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .action-button {
    background: none;
    border: none;
    padding: 0;
    outline: inherit;
    font-size: 14px;
    line-height: 130%;
    font-weight: 600;
    cursor: pointer;
    border-radius: 5px;
    padding: 16px 20px;
    width: 169px;
    height: 50px;
    .icon {
      margin-right: 10px;
    }
    &.white {
      background: #ffffff;
      color: #35bad8;
      border: 1px solid #ffffff;
      &:hover {
        color: #ffffff;
        background: #35bad8;
      }
    }
    &.blue {
      background: #35bad8;
      color: #ffffff;
      border: 1px solid #ffffff;
      &:hover {
        color: #35bad8;
        background: #ffffff;
      }
    }
  }
}
</style>
