<template>
  <div class="page-wrapper">
    <div class="header">
      <div class="top-banner">
        De los creadores de <span>Asómate</span> y
        <span> Limpia tu río</span>
      </div>
      <div class="header-image"></div>
    </div>

    <h1 class="title">The End</h1>
    <h2 class="subtitle ">Evento gastro-musical en Carcaboso</h2>
    <div class="date yellow">2 de Mayo 2020</div>
    <div class="colaboran">
      <h4 class="">Con la colaboración de:</h4>
      <ul>
        <li>ATTG - Rock band (desde Madrid)</li>
        <li>The Holy Crabs (desde Murcia)</li>
        <li>Grupo local (en construcción)</li>
        <li>...Y otros artistas por confirmar</li>
      </ul>
    </div>
    <div class="trama">
      <div class="parte">
        <div class="numero-parte">1a Parte e introducción</div>
        <div class="desc">El Tour por la Exposición</div>
      </div>
      <div class="parte">
        <div class="numero-parte">2a Parte</div>
        <div class="desc">El Taller ecológico para niñ@s</div>
      </div>
      <div class="parte">
        <div class="numero-parte">3a Parte</div>
        <div class="desc">La comida compartida</div>
      </div>
      <div class="parte">
        <div class="numero-parte">4a Parte y desenlace</div>
        <div class="desc">Los conciertos</div>
      </div>
    </div>
    <div class="pre-footer">
      <div class="logo">
        <img src="/img/logo-attg.jpg" alt="" />
      </div>
      <div class="logo">
        <img src="/img/holy-crabs.jpg" alt="" />
      </div>
    </div>
    <div class="footer">
      Si estás interesado en esta película contacta con nostros en
      <a href="http://www.carcaboso.com">www.carcaboso.com</a> <br />
      - Seguiremos informando -
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {}
  }
}
</script>

<style>
.page-wrapper {
  text-align: center;
  height: 100vh;
}
.header {
  height: 75%;
  min-height: 75%;
}
.top-banner {
  text-align: center;
  font-family: 'Courgette', cursive;
  font-size: 0.9rem;
  height: 40px;
  color: #eab018;
  background: #eab018;
  color: #3f0200;
  display: flex;
  justify-content: center;
  align-items: center;
}
.top-banner span {
  padding: 0 4px;
  color: #f2f2f2;
}

.header-image {
  height: calc(100% - 40px);
  min-height: calc(100% - 40px);
  background: url('/img/fondo-the-end-chaplin.jpg');
  background-size: cover;
  background-position-x: center;
  background-position-y: 35%;
}
.header-image::after {
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.24) 0, transparent 50%);
  height: 69.6%;
  min-height: 69.6%;
  content: '';
  left: 0;
  position: absolute;
  width: 100%;
}
.title {
  font-family: 'Lobster', cursive;

  font-size: 5rem;
  padding: 32px;
  margin: 0;
}
.subtitle {
  font-size: 1.6rem;
  padding: 24px;
  background: #eab018;
  color: #3f0200;
  margin: 0;
}
.date {
  font-size: 1.6rem;
  padding: 24px;
}
.yellow {
  color: #ffde22;
}
.colaboran {
  padding: 24px;
  margin: 0;
  width: 100%;
  background: #3e3e40;
  color: #fff;
}
.colaboran h4 {
  margin: 0;
  padding: 24px;
}

.colaboran ul {
  margin: 0;
  padding: 0;
  padding-bottom: 24px;
}
.colaboran ul li {
  padding: 6px;
  list-style: none;
  margin: 0;
}
.parte {
  padding: 24px;
}
.numero-parte {
  color: #eab018;
}
.pre-footer {
  display: flex;
  background: #fff;
  padding: 24px;
  justify-content: space-around;
}
.pre-footer > div {
  flex-grow: 1;
  max-width: 200px;
}
.pre-footer img {
  width: 100%;
}
.footer {
  background: #3e3e40;
  padding: 24px;
}
</style>
