<template>
  <div class="page">
    <div class="location-box">
      <h2>Permiteți ca aplicația să utilizeze locația dumneavoastră?</h2>
      <div class="buttons">
        <button class="btn allow">Permite</button>
        <button class="btn deny">Nu permite</button>
      </div>
    </div>
  </div>
</template>
<style >
div#app {
  margin-left: 530px;
  padding: 0;
}
html, body{
  margin: 0;
  padding: 0;
  height: 100%;
  background-color: rgb(62, 89, 73);
 
}
.location-box {
  background-color: rgb(49, 144, 48);
  padding: 40px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(60, 249, 60, 0.341);
  text-align: center;
  max-width: 400px;
  width: 100%;
}
h2 {
  color: #f7f6f6;
  font-family: Arial, sans-serif;
  margin-bottom: 20px;
  font-size: 20px;
}
.buttons {
  display: flex;
  flex-direction: column;
}
.btn {
  padding: 10px;
  margin: 5px 0;
  font-size: 16px;
  cursor: pointer;
  border: none;
  border-radius: 5px;
  transition: background-color 0.3s;
}
.btn.allow {
  background-color: #296d18;
  color: white;
}
.btn.allow:hover {
  background-color: #76a84b;
}

.btn.deny {
  background-color: #296d18;
  color: white;
}
.btn.deny:hover {
  background-color: #76a84b;
}








</style>

