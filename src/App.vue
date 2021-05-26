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
          <div class="otziv_img oimg1"></div>
          <p>РЫБААААААААААААААК</p>
        </div>
        <div class="otziv">
          <div class="otziv_img oimg2"></div>
          <p>ВСе понравилось, все нормально</p>
        </div>
        <div class="otziv">
          <div class="otziv_img oimg3"></div>
          <p>АААААААААААААААААААА АААААААААААААААААААААААААААА</p>
        </div>
      </div>



      <div class="where_are_we">
        
      </div>
    </v-main>

      <v-footer
    dark
    padless
  >
    <v-card
      flat
      tile
      class="green lighten-1 white--text text-center"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin. Vestibulum eu ipsum vel diam elementum tempor vel ut orci. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>У Осетра</strong>
      </v-card-text>
    </v-card>
  </v-footer>
  </v-app>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-telegram',
        'mdi-instagram',
        'mdi-vk',
      ],
    }),
  }
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
    background-color: rgba(255, 255, 255, 0.4);
  }

  .otziv_img {
    margin: auto;
    width: 300px;
    height: 300px;
    border-radius: 50%;
    background-size: 300px 300px;
  }

  .oimg1 {
    background-image: url("https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/4842f970-3380-488d-9b8f-f6c0c57d085d/d6seijy-76a3d242-860b-4fce-aa89-482923e4d4ac.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzQ4NDJmOTcwLTMzODAtNDg4ZC05YjhmLWY2YzBjNTdkMDg1ZFwvZDZzZWlqeS03NmEzZDI0Mi04NjBiLTRmY2UtYWE4OS00ODI5MjNlNGQ0YWMucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.uyVDhOOWleX6l7hqN2hzyPkdqZiAmmpm_C0f07aLI5w");
  }

  .oimg2 {
    background-image: url("https://cdn24.img.ria.ru/images/07e4/03/0b/1568445614_184:263:2315:1462_600x0_80_0_0_22714ab228feb8d09df8eff75ad30b8a.jpg");
  }

  .oimg3 {
    background-image: url("https://i.ytimg.com/vi/MnnbcUH6Y7k/maxresdefault.jpg");
  }

  .where_are_we {
    width: 100%;
    height: 995px;
    background-color: red;
  }
</style>
