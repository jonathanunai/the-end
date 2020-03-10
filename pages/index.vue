<template>
  <div class="page-wrapper">
    <div class="top-banner">
      De los creadores de <span>Asómate</span> y el colectivo
      <span>Limpia tu río</span>
    </div>
    <div class="presentan">Llega</div>
    <h1 class="title">The End</h1>
    <h2 class="subtitle ">Evento gastro-musical en Carcaboso</h2>
    <div class="date yellow">2 de Mayo 2020</div>
    <div class="colaboran">
      <h4 class="">Con la colaboración de:</h4>
      <ul>
        <li>ATTG - Rock band (desde Madrid)</li>
        <li>The Holy Crabs (desde Murcia</li>
        <li>Grupo local (en construcción)</li>
        <li>Y otros artistas por confirmar</li>
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
    <div class="footer">
      Si estás interesado en esta película contacta con nostros en
      www.carcaboso.com <br />
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
}

.top-banner {
  text-align: center;
  font-family: 'Courgette', cursive;
  font-size: 0.9rem;
}
.presentan {
  font-size: 1.5rem;
  padding: 24px;
}
.title {
  font-size: 5rem;
  padding: 24px;
  padding-bottom: 0;
}
.subtitle {
  font-size: 2rem;
  padding: 12px;
}
.date {
  font-size: 1rem;
  padding: 0;
}
.top-banner span {
  font-weight: 700;
}
.yellow {
  color: #ffde22;
}
.colaboran {
  padding: 24px;
}
.colaboran ul li {
  padding: 8px;
  list-style: none;
}
</style>
