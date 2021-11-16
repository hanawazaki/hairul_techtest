<template>
  <header>
    <div class="logo">
      <img src="../assets/logo.png" alt="logo" />
    </div>
    <div>
      <ul class="menu">
        <li>
          <a href="#" class="link active">Home</a>
        </li>
        <li>
          <a href="#" class="link">Discover</a>
        </li>
        <li>
          <a href="#" class="register">Register</a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/search.png" alt="search" style="width: 20px" />
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="sass" scoped>
header
  display: flex
  justify-content: space-between
  padding: 0 16px
  background-color: #F7F9F9
  .logo
    padding: 10px 0px
    img
      width: 48px

  .menu
    display: flex
    flex-direction: row
    li
      list-style: none
      margin: 0 20px
      padding: 10px 0px
      a
        text-decoration: none
        color: #000
        &.active
          background-color: #E0E2E2
          border-radius: 30px
          padding: 10px 40px
    .register
      margin-left: 30px
</style>