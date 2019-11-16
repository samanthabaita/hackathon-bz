<template>
  <div>
    <section class="hero is-large" :style="`backgroundImage: url('/img/5.jpg')`" style="background-repeat: no-repeat; background-size: cover; background-position: center bottom;">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title is-1 has-text-white">Come visit us</h1>
          <button class="button is-dark is-inverted is-outlined" style="font-weight: 600;">
            Book your holidays
          </button>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <h2 class="title" style="margin-bottom: 3rem;">Contact Info</h2>
        <p class="subtitle" style="margin-bottom: 5rem;">Here are our contacts</p>
        <nav class="level">
          <div class="level-item has-text-centered">
            <div>
              <p class="heading">Address</p>
              <p class="title is-6">Corso della Libertà 117, 39100 <br> Bolzano BZ</p>
            </div>
          </div>
          <div class="level-item has-text-centered">
            <div>
              <p class="heading">Phone</p>
              <p class="title is-6">0472 123456</p>
            </div>
          </div>
          <div class="level-item has-text-centered">
            <div>
              <p class="heading">Email</p>
              <p class="title is-6">
                <a href="mailto:email@example.org">email@example.org</a>
              </p>
            </div>
          </div>
        </nav>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <h2 class="title" style="margin-bottom: 3rem;">How to reach us </h2>
        <p class="subtitle">There are several means of transport that you can use to come visit use:</p>
        <div class="content">
          <ul>
            <li>Train</li>
            <li>Car</li>
            <li>Buses</li>
          </ul>
        </div>
        <p class="subtitle">
          <strong>Do you want to be more sustainable?</strong> Use public transport to reach Bolzano and then use bikesharing and carsharing to travel around South Tyrol.
          <br>
          Here's a map you can use to find the nearest cars and bike stations:
        </p>
        <img src="/webcomponent.png" alt="Prototype of a web component">
      </div>
    </section>
  </div>
</template>
