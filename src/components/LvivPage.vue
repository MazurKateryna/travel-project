<template>
  <div class="lviv">
    <h2>Львов</h2>
    <div class="description">
      <h3>7 интересных фактов об этом волшебном городе</h3>
      <ul>
        <li class="item">
          <div class="img-block">
            <img src="../assets/lviv/Lviv_train_station.jpg" alt="">
            <img src="../assets/lviv/hotel-lviv.jpg" alt="">
            <img src="../assets/lviv/school.jpg" alt="">
            <img src="../assets/lviv/airboll-lviv.jpg" alt="">
            <img src="../assets/lviv/lampa-lviv.jpg" alt="">
          </div>
          <div>
            <p class="title">Город изобретений</p>
            <p class="text">В течение всей своей истории Львов уверенно оставался первым среди первых. 
              Здесь появилась первая украинская железная дорога. Первый поезд прибыл во Львов из Вены 4 ноября 1861 года. 
              Здесь же появился первый украинский отель, первая школа и профессиональный театр. 
              Местные изобретатели впервые запустили воздушный шар и создали керосиновую лампу.</p>
          </div>
        </li>
        <li class="item">
          <div class="img-block">
            <img src="../assets/lviv/fest-1.jpg" alt="">
            <img src="../assets/lviv/fest-2.jpg" alt="">
            <img src="../assets/lviv/fest-3.jpg" alt="">
            <img src="../assets/lviv/fest-4.jpg" alt="">
            <img src="../assets/lviv/fest-5.jpg" alt="">
          </div>
          <div>
            <p class="title">Фестивальный центр</p>
            <p class="text">В течение года в городе проводится более 100 всевозможных фестивалей: 
              праздничных, музыкальных, гастрономических, исторических. 
              В любое время года можно оказаться на празднике уличного театра, шоколада или классической музыки.</p>
          </div>
        </li>
        <li class="item">
           <div class="img-block">
            <img src="../assets/lviv/museum-1.jpg" alt="">
            <img src="../assets/lviv/museum-2.jpg" alt="">
            <img src="../assets/lviv/museum-3.jpg" alt="">
            <img src="../assets/lviv/museum-4.jpg" alt="">
            <img src="../assets/lviv/museum-5.jpg" alt="">
          </div>
          <div> 
            <p class="title">Музейная столица</p>
            <p class="text">Именно во Львове самая большая концентрация музеев на площади. 
              И это во всей Украине! Всего их насчитывается более 60.</p>
          </div>
        </li>
        <li class="item">
          <div class="img-block">
            <img src="../assets/lviv/Lviv-sobor.jpg" alt="">
            <img src="../assets/lviv/sobor-5.jpg" alt="">
            <img src="../assets/lviv/Sobor-3.jpg" alt="">
            <img src="../assets/lviv/sobor-2.jpg" alt="">
            <img src="../assets/lviv/sobor-Lviv.jpg" alt="">
          </div>
          <div>
            <p class="title">Религиозный центр</p>
            <p class="text">Колоссальное культурно-историческое наследие напрямую связано с наследием религиозным. 
              В городе представлены все конфессии и функционирует 104 храма. 
              Многие из них – важнейшие достопримечательности национального значения.</p>
          </div>
        </li>
        <li class="item">
          <div class="img-block">
            <img src="../assets/lviv/footmatch.jpg" alt="">
            <img src="../assets/lviv/footboll-team.jpg" alt="">
            <img src="../assets/lviv/Arena-Lviv.jpg" alt="">
            <img src="../assets/lviv/match-2.jpeg" alt="">
            <img src="../assets/lviv/footpark.jpg" alt="">
          </div>
          <div>
            <p class="title">Первый футбольный матч</p>
            <p class="text">В июле 1894 года во Львове состоялся первый футбольный матч Украина-Польша. 
              Игра прошла на территории Стрыйского парка, и львовская команда одержала уверенную победу.</p>
          </div>
        </li>
        <li class="item">
           <div class="img-block">
            <img src="../assets/lviv/road-1.jpg" alt="">
            <img src="../assets/lviv/road-2.png" alt="">
            <img src="../assets/lviv/road-3.jpg" alt="">
            <img src="../assets/lviv/road-4.jpg" alt="">
            <img src="../assets/lviv/road-5.jpg" alt="">
          </div>
          <div>
            <p class="title">Комфортная транспортная развязка</p>
            <p class="text">Помимо наземного транспорта, Львов примечателен аэропортом. 
              Аэропорт имени короля Даниила Галицкого находится всего в 6 км от центра города и пропускает 
              около 2 тысяч пассажиров ежечасно. 
              Он – один из крупнейших во всей Восточной Европе.</p>
          </div>
        </li>
        <li class="item">
           <div class="img-block">
            <img src="../assets/lviv/lvov_plosha.jpg" alt="">
            <img src="../assets/lviv/plosha-lviv.jpg" alt="">
            <img src="../assets/lviv/opera.jpeg" alt="">
            <img src="../assets/lviv/wine.jpg" alt="">
            <img src="../assets/lviv/panorama.jpg" alt="">
          </div>
          <div>
            <p class="title">Туристическая Мекка</p>
            <p class="text">Львов находится всего в 50 км от границы с ЕС. 
              Отсюда легко добраться до Киева, Варшавы и Будапешта. 
              Ежегодно в городе бывает около миллиона туристов, и это количество только растет с каждым годом. 
              В их числе – гости из Франции, Великобритании, США, Канады и Японии.</p>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: "Lviv",
}
</script>
<style scoped lang="scss">
h2 {
  margin: 0;
}
img {
  width: 200px;
  height: auto;
}
img:hover {
  animation: pulsing 2s ease-out;
}
@keyframes pulsing {
  0% {
    transform: scale(1.0, 1.0)
  }
  100% {
    transform: scale(1.5, 1.5);
  }
}
.item {
  list-style: none;
  margin-bottom: 80px;
  width: 80%;
  margin: 0 auto;
}
.img-block {
  display: flex;
  justify-content: space-between;
}
.title {
  font-weight: bold;
}
</style>