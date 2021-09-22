<template>
  <div id="app">
    <header>
      <container>
          <img class="logo" src="./assets/logo.jpg" alt="logo-blinguage">
              <ul>
                  <li>Courses</li>
                  <li>Why Us</li>
                  <li>Support</li>
                  <li><div class="btn btn--transparent">Get Started</div></li>
              </ul>
      </container>
    </header>
      <main>
          <h2>Learn<br>Japanese</h2>
              <p>Visiting the temples in Kyoto, getting a <br>new jobb, or making a personal connection <br>-no matter why you want to learn, we<br> have the right course for you.</p>
                  <div class="btn btn--purple">Get Started</div>
                      <div class="items">
                          <img src="./assets/book.png" alt="japanese-book" class="icone icone--book">
                          <img src="./assets/headset.png" alt="headset" class="icone icone--headset">
                          <img src="./assets/loop.png" alt="loop" class="icone icone--loop">
                      </div>
                      <div class="items-text">
                          <p><strong>Detailed lessons</strong> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Odit sunt illum culpa rem incidunt! Delectus voluptates exercitationem et mollitia pariatur quidem temporibus eveniet aperiam dolorem aut. Deleniti non nihil dignissimos!</p>
                          <p><strong>Engaging audio</strong> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maxime velit quas minus tenetur facere voluptates ea perspiciatis assumenda laborum praesentium odit minima cumque, suscipit perferendis animi corporis unde ipsum omnis?</p>
                          <p><strong>Flexible subscription options</strong> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, eaque recusandae? Mollitia eum dolorum ullam voluptatum cumque, incidunt pariatur repellendus, sit ab quaerat aspernatur quae necessitatibus, explicabo consectetur nostrum facilis!</p>
                      </div>

      </main>
  </div>
</template>

<script>


</script>

<style lang="scss">

* {
    margin: 0;
    padding: 0;
}

body {
    font-family: "Helvetica";
    display: block;
    background-image: url("./assets/bg.jpg");
    background-size: 60%;
    background-repeat: no-repeat;
    background-position: right top;
    margin: 0 300px 0 300px;   
}

.logo {
  max-height: 40px;
}

ul {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    font-weight: bold;
}

li {
  margin-right: 80px;
}

.btn {
    height: 20px;
    padding: 10px 15px;
    border-radius: 10px;
    border: 2px solid transparent;
    font-weight: bold;
    display: inline-flex;
    align-items: center;
    justify-content: center;
}

.btn--transparent {
    color: black;
    border-color: black;
}

.btn--purple {
  color: #FBF3CD;
  background-color: #372F7F;

}

container {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
}

h2 {
  margin-top: 100px;
  margin-bottom: 30px;
  font-size: 4em;
}

p {
  font-size: 20px;
  margin-bottom: 50px;
  line-height: 150%;
}

.icone {
  width: 50px;
  margin: 250px 0 40px 0;
}

.items, .items-text {
  display: grid;
  width: 400px;
  grid-template-columns: 300px 300px 300px;
  align-items: start;
  justify-content: space-between;
  gap: 10px 10em;
}

</style>
