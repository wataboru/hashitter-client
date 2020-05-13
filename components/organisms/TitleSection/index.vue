<template>
  <div class="title-section">
    <div class="title-section__title">hashitter</div>
    <div class="title-section__note">
      hashitter(はしったー)を使って<br />
      twitterにランニング記録を残そう。
    </div>
  </div>
</template>

<style lang="scss" scoped>
.title-section {
  height: 567px;
  background-image: url('~@/assets/images/main_visual.jpg');
  background-position: center;
  position: relative;
  display: flex;
  justify-content: center;
  flex-direction: column;

  &:before {
    content: '';
    background-color: rgba(0, 0, 0, 0.5);
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
  }

  text-align: center;
  color: #fff;

  &__title {
    position: relative;
    font-size: 40px;
    font-family: signo, sans-serif;
    font-style: normal;
    font-weight: 500;
  }

  &__note {
    position: relative;
    margin-top: 60px;
  }
}
</style>
