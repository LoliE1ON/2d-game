<template>
  <div>
    <div class="card-body">
      <input type="text" value="Your name">
      <button class="start">Start</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style>
  .card-body {
    max-width: 400px;
    margin: 0 auto;
    margin-top: 200px;
  }
  input[type="text"] {
    background: transparent;
    padding: 15px;
    border-radius: 5px;
    border: 3px solid white;
    color: white;
    font-size: 30px;
    text-align: center;
    max-width: 400px;
  }
  .start {
    background: #005aff;
    padding: 6px;
    border-radius: 5px;
    border: 3px solid #005aff;
    color: #ffffff;
    font-size: 35px;
    text-align: center;
    width: 100%;
    margin-top: 10px;
    cursor: pointer;
  }
</style>
