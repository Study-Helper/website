# Group Members

<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 20px;
}

@media (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  border-radius: 10px;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #159957;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #0c5a33;
}

</style>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="assets/VeilLight.jpeg" style="width:100%">
      <div class="container">
        <h2>António Ferreira</h2>
        <p class="title">Developer</p>
        <p>Student nº45356</p>
        <p><button class="button" href="https://github.com/VeilLight">github@VeilLight</button></p>
      </div>
	 </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="assets/ImXico.jpeg" style="width:100%">
      <div class="container">
        <h2>Francisco Cunha</h2>
        <p class="title">Developer</p>
        <p>Student nº45412</p>
        <p><button class="button" href="https://github.com/ImXico">github@ImXico</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="assets/luis5566.png" style="width:100%">
      <div class="container">
        <h2>Luís Martins</h2>
        <p class="title">Developer</p>
        <p>Student nº45640</p>
        <p><button class="button" href="https://github.com/luis5566">github@luis5566</button></p>
      </div>
    </div>
  </div>
</div>