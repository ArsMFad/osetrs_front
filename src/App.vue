<template>
  <v-app>
    <v-app-bar
      app
      color="green"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://wiki.fishingplanet.com/images/7/7c/Lake_Sturgeon.png"
          transition="scale-transition"
          width="70"
        />

        <v-title
          font="50"
        >База отдыха "У осетра"</v-title>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="login_kuda_nibud"
        target="_blank"
        text
      >
        <span class="mr-2">I-2EA-A90-F4-7D</span>
        <v-icon>mdi-phone</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <div class="v-mainn">
        <h1 class="mainh1">У ОСЕТРА</h1>
        <v-img
          class="justify-center"
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Dacha_-_panoramio_%281%29.jpg/1200px-Dacha_-_panoramio_%281%29.jpg"
          max-height="905"
          max-width="auto"
          align-center
        />
        <h2 class="mainh2">ЗВОНИ И БРОНИРУЙ I-2EA-A90-F4-7D</h2>
      </div>


      <div class="who_we_are">
        <div class="who_we_are_in">
          <div class="left_part">
            <h3>Почему мы?</h3>
            <ul>
              <li>Куча рыбы</li>
              <li>Качественное обслуживание</li>
              <li>Аренда оборудования</li>
              <li>Экскурсия по лесам Вьетнама</li>
            </ul>
          </div>
          <div class="right_part">
            <h3>Чем можно заняться</h3>
            <ul>
              <li>Порыбачить</li>
              <li>Поесть рыбы</li>
              <li>Сопровождение осетра на нерест</li>
              <li>УСТРОЙТЕ ЭТИМ АМЕРИКАНЦАМ ВЬЕТНАМ, ДЖОННИ ОНИ НА ДЕРЕВЬЯХ, ДЖОННИ Я НОГ НЕ ЧУВСТВУЮ ААААААА</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="udochki">
        <div class="cardd">
          <div class="cardd_img cimg1"></div>
          <h3>Удочка какая-нибудь</h3>
          <p>Купи ее и будет тебе счастье ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ</p>
          <div class="price"><p>450</p></div>
        </div>
        <div class="cardd">
          <div class="cardd_img cimg2"></div>
          <h3>Удочка какая-нибудь</h3>
          <p>Купи ее и будет тебе счастье ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ ТЕКСТ</p>
          <div class="price"><p>450</p></div>
        </div>
        <div class="cardd">
          <div class="cardd_img cimg3"></div>
          <h3>НАПАЛМ</h3>
          <p>Купи ее и будет тебе счастье ДЖОННИ У ТЕБЯ НЕТ НОГИ ДЖОННИ ААААААААААААА АААААААААА  ААААААААААААААААААА ААААА</p>
          <div class="price"><p>450</p></div>
        </div>
      </div>

      <div class="poimai_ribu">
        <div class="otziv">
          <div class="otziv_img"></div>
          <p></p>
        </div>
        <div class="otziv">
          <div class="otziv_img"></div>
          <p></p>
        </div>
        <div class="otziv">
          <div class="otziv_img"></div>
          <p></p>
        </div>
      </div>

    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
};
</script>


<style>
  .v-mainn {
    text-align: center;
  }

  .mainh1 {
    color: white;
    font-size: 350px;
    top: 250px;
    position: relative;
    line-height: 0;
    z-index: 12312312;
  }
  .mainh2 {
    color: white;
    font-size: 50px;
    top: -150px;
    position: relative;
    line-height: 0;
    z-index: 12312312;
  }


  .who_we_are {
    height: 995px;
    background-repeat: repeat;
    background-image: url("https://images.fineartamerica.com/images/artworkimages/mediumlarge/2/2-seamless-forest-pattern-mike-taylor.jpg");
  }


  .who_we_are_in {
    height: 700px;
    width: 1600px;
    position: relative;
    border: 5px inset green;
    top: 190px;
    background-color: white;
    border-radius: 5%;
    margin: auto;
    display: flex;
  }

  .left_part {
    position: relative;
    left: 50px;
    font-size: 40px;
    width: 600px;
    margin: auto;
  }

  .right_part {
    position: relative;
    left: 50px;
    font-size: 40px;
    width: 600px;
    margin: auto;
  }

  .udochki {
    width: 100%;
    height: 995px;
    background-image: url("https://www.prizyv.ru/wp-content/uploads/2018/11/15133428195a33c763880dd6.47511314.jpg");
    background-size: 100% 995px;
    display: flex;
  }

  .cardd {
    width: 450px;
    height: 760px;
    background-color: white;
    border-radius: 1%;
    margin: auto;
  }

  .cardd_img {
    width: 450px;
    height: 450px;
    background-color: red;
    background-size: 450px;
  }

  .price {
    width: 200px;
    height: 50px;
    background-color: grey;
    margin: auto;
    border-radius: 25%;
    text-align: center;
  }

  .cimg1 {
    background-image: url("https://www.teknistore.com/2639644-large_default/leo-transparent-solid-fiberglass-fishing-rod-1-35m-1-5m-1-65m-2-sections-sea-fishing-pole.jpg");
  }

  .cimg2 {
    background-image: url("https://www.kindpng.com/picc/m/160-1601195_angling-fishing-rod-real-fishing-rod-png-transparent.png");
  }

  .cimg3 {
    background-image: url("https://www.graycell.ru/picture/big/napalm.jpg");
  }

  .poimai_ribu {
    width: 100%;
    height: 995px;
    background-image: url("../public/osetr.jpg");
    background-size: 100% 995px;
    display: flex;
  }

  .otziv {
    margin: auto;
    width: 300px;
    height: 500px;
    background-color: red;
  }

  .otziv_img {
    margin: auto;
    width: 300px;
    height: 300px;
    border-radius: 50%;
    background-color: white;
  }
</style>
