<script>
  export default {
  
  }
</script>

<template>
  <div class="container">
    <div class="searchCity">
      <label for="inputCity">Найти город</label>
      <br>
      <input type="text" id="inputCity" placeholder="Введите название города"> <button>Найти</button>
    </div>
    
  </div>

</template>

<style scoped>
  .container {
    border: 2px solid red;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    width: 30em;
    height: 85vh;
  }

  .searchCity > label {
    font-size: 35px;
  }

  .searchCity > input {
    width: 20em;
    height: 2.2em;
    border: unset;
  }

  .searchCity > button {
    width: 7em;
    height: 2.2em;
    border: unset;
    cursor: pointer;
    margin-left: .5em;
  }

  .searchCity > button:hover {
    background-color: #ede6e6;
  }

</style>
