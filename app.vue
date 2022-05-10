<template>
  <div class="container">
    <h1>Baby Name Generator</h1>
    <p>Choose your options annd click the "Find Names" button below</p>
    <div class="options-container">
      <div class="option-container">
        <h4>1. Choose the gender</h4>
        <div class="option-buttons">
          <button>Boy</button>
          <button>Girl</button>
          <button>Unisex</button>
        </div>
      </div>
      <div class="option-container">
        <h4>2. Choose the name's popularity</h4>
        <div class="option-buttons">
          <button>Trendy</button>
          <button>Unique</button>
        </div>
      </div>
      <div class="option-container">
        <h4>3. Choose name's length</h4>
        <div class="option-buttons">
          <button>Long</button>
          <button>Short</button>
          <button>All</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  font-family: Arial, Helvetica, sans-serif;
  color: #232323;
  max-width: 50rem;
  margin: 0 auto;
  text-align: center;
}
h1 {
  font-size: 3rem;
}
.options-container {
  background-color: rgb(255, 237, 236);
  border-radius: 2rem;
  padding: 1rem;
  width: 95%;
  margin: 0 auto;
  position: relative;
  margin-top: 4rem;
}
.option-container {
  margin-bottom: 2rem;
}
.option-container button {
  background: white;
  border: none;
  outline: 0.15rem solid rgb(249, 87, 89);
  padding: 0.75rem;
  width: 12rem;
  font-size: 1rem;
  color: #232323;
  cursor: pointer;
}
.option-container button:first-child{
  border-radius: 1rem 0 0 1rem;
}
.option-container button:last-child{
  border-radius: 0 1rem 1rem 0;
}

</style>