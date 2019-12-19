<template>
  <header>
    <div class="header-left">
      Your scope
      <div class="scope">0</div>
    </div>
    <div class="header-right">
      <span class="username margin">Your name</span>
      <button class="header-button">
        How to play
      </button>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
  header {
    display: flex;
    padding: 40px;
    text-transform: uppercase;
    color: #fff;
    font-size: 25px;
  }
  .header-left {
    margin-right: auto;
  }
  .header-right {
    margin-left: auto;
  }
  .header-button {
    padding: 7px;
    border: 2px solid white;
    background: transparent;
    border-radius: 3px;
    color: white;
    font-size: 20px;
    cursor: pointer;
  }
  .scope {
    display: inline-block;
    background: transparent;
    padding: 2px 10px 2px 10px;
    color: white;
    font-weight: bold;
    font-size: 27px;
    border-radius: 3px;
    letter-spacing: -0.03em;
  }
  .username {
    padding: 10px;
    letter-spacing: -0.03em;
  }
  .margin {
    margin: 20px;
  }
</style>
