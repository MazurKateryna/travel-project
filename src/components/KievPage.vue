<template>
  <div class="kiev">
    <h2>Киев</h2>
    <div class="description">
      <h3>9 интересных фактов о Киеве</h3>
      <ul class="description__list">
        <li class="description__item">
          <img src="../assets/kiev/andr.png" alt="">
          <div class="descriprion__text">
          <p class="description__title">Андреевская церковь</p>
          <p>В этой церкви нет колоколов. По легенде, в древние времена на этом месте протекали подземные реки.
             Они ушли, когда на холме святой Андрей поставил крест. 
             Он предсказал появление великого города и церкви в этом месте.
             Когда местные жители построили Андреевскую церковь, колокола водружать не стали: они верили, 
             что от перезвона подземные воды могут вернуться. 
             В начале ХХ века купола церкви заменили другими.
             Но они выглядели неважно, поэтому после скандала храму вернули прежние купола.</p></div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/maydan.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Майдан</p>
            <p>До Х века эту местность, бывшую лесными дебрями, называли Перевесищем (впервые название упоминается в 945 году). 
            Происхождение названия связано со способом охоты. 
            Охотники «перевешивали» сетями места в лесу и загоняли в них дичь. 
            За всё время на Майдане стояло 6 памятников, 3 фонтана и одна виселица.</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/askold.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Аскольдова могила</p>
            <p>Во времена Великой Отечественной войны здесь было кладбище и место захоронения немецких солдат. 
            Его ликвидировали после 1944 года, уже в освобожденном от оккупантов городе. 
            Это же место стали использовать как кладбище солдат, погибших во время оккупации Киева. 
            Однако после пятидесятых годов прах и тела умерших были перенесены в Парк Вечной Славы на Арсенальной.</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/arsenalna.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Станция метро «Арсенальная»</p>
            <p>Это самая глубокая станция метро не только в Киеве, но и во всём мире. 
            Она находится на глубине 105 метров. 
            Ходят слухи, что в туннелях недалеко от станции построены тайные убежища для членов правящей верхушки, 
            а некоторые туннели ведут в подвалы завода «Арсенал».</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/lavra.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Киево-Печерская Лавра</p>
            <p>Пальму первенства по посещаемости среди киевских музеев прочно держит Киево-Печерская Лавра, 
            в которой бывает около миллиона туристов в год. 
            На её территории расположены пещеры с мощами святых и Музей миниатюр, в котором хранится подкованная блоха.</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/dvorik.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Сказочный дворик</p>
            <p>В столице живут мастера-кудесники, способные превратить обычную клумбу в сказку. 
            Убедиться в этом (и перенять опыт) можно, посетив «сказочный дворик» на Виноградаре.</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/tresh.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Памятник мусоровозу</p>
            <p>Киевский памятник мусоровозу — единственный в мире, поэтому по праву может считаться самым уникальным памятником. 
            Его установил в 2004 году Киевспецтранс в благодарность работникам санитарной очистки Украины за трудовые заслуги. 
            Говорят, машина приехала к постаменту самостоятельно и до сих пор в рабочем состоянии.</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/chocolate-house.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Шоколадный дом</p>
            <p>Сладкое название дому дали горожане — за его характерный цвет. В советские времена здесь был ЗАГС. 
            В доме сохранилось огромное зеркало, и говорят, что если в него посмотрятся молодожёны — непременно будут счастливы.</p>
          </div>
        </li>
        <li class="description__item">
          <img src="../assets/kiev/spusk.jpg" alt="">
          <div class="descriprion__text">
            <p class="description__title">Смородинский спуск</p>
            <p>Всего в Киеве 13 спусков. Смородинский спуск соединяет Татарку и Куренёвку и 
            располагается в русле Смородинского ручья, который многие ошибочно отождествляют с былинной речкой Смородиной. 
            На самом деле название связано с располагавшейся неподалёку усадьбой купцов Смородиновых. 
            Прежние названия спуска — Литовский, Дикий.</p>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Kiev",
};
</script>

<style scoped lang="scss">
h2 {
  margin: 0;
}
.description {
  display: block;

  &__list {
    display: block;
  }
  &__item {
    display: flex;
    margin-top: 20px;
    margin-right: 100px;
  }
  &__title {
    font-weight: bold;;
  }
}
img {
  max-width: 300px;
  height: auto;
  border-radius: 8%;
  animation: pulsing 10s infinite;
}
@keyframes pulsing {
  0% {
    transform: scale(0.5, 0.5)
  }
  50% {
    transform: scale(1.0, 1.0);
  }
  100% {
    transform: scale(0.5, 0.5);
  }
}
p {
  text-align: left;
  margin-left: 10px;
}
</style>