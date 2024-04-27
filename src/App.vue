<template>
  <main>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
      <div class="cards-container">
        <div class="card">
          <p class="main-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Consequuntur nostrum exercitationem omnis, minus nisi corporis!</p>
          <p class="date">May 15th 2024</p>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
main{
  height: 100vh;
  width: 100vw;
}
.container{
  max-width: 1000px;
  padding: 10px;
  margin: 0 auto;
  }
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
h1{
  font-weight: bold;
  margin-bottom: 25px;
  font-size: 75px;
}
button{
  border: none;
  padding: 10px;
  width: 50px;
  height: 50px;
  cursor: pointer;
  color: white;
  background: black;
  border-radius: 100%;
  font-size: 20px;
  }
  .card{
    width: 225px;
    height: 225px;
    background: rgb(237, 182, 44);
    padding: 10px;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-right: 20px;
    margin-bottom: 20px;
  }
  .date{
    font-size: 12.5px;
    font-weight: bold;
  }
</style>