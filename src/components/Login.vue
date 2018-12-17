<template>
  <div class="mdl-grid">
    <div class="mdl-layout-spacer"></div>
    <div class="mdl-card mdl-shadow--2dp">
      <div class="mdl-card__title mdl-color--primary">
        <h2 class="mdl-card__title-text mdl-color-text--white">login</h2>
      </div>
      <div class="mdl-card__supporting-text">
        <div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label">
          <label for="username" class="mdl-textfield__label">username</label>
          <input name="username" id="username" class="mdl-textfield__input" type="text">
        </div>
        <div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label">
          <label for="password" class="mdl-textfield__label">password</label>
          <input name="password" id="password" class="mdl-textfield__input" type="password">
        </div>
      </div>
      <div class="mdl-card__actions">
        <button class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect mdl-button--accent">Login</button>
      </div>
    </div>
    <div class="mdl-layout-spacer"></div>
  </div>
</template>
<script>
export default {
  name: "login",
  data() {
    return {
      SubTitle: "UPP INVENTORY SYSTEM"
    };
  }
};
</script>
<style scoped>
br {
  display: block;
  margin: 10px 0;
}
</style>


