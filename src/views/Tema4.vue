<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Productos de repostería: técnicas especializadas

    img(src="@/assets/curso/tema4/img01.png", alt="")
    
    .row.justify-content-center.align-items-center.z-2.mb-5
      .col-lg-10(data-aos="fade-up")
        p.banner-text La elaboración de productos de repostería más complejos implica la aplicación de técnicas específicas que combinan diferentes preparaciones base. Estas técnicas especializadas, como las empleadas en natillas, <i>mousses</i> o postres helados requieren un conocimiento profundo de los fenómenos físicos y químicos que ocurren durante su proceso, así como un manejo cuidadoso de los ingredientes y las temperaturas.

    separador
    
    .bg-full-width.bg-fondo-1
      #t_4_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 4.1 Budines y natillas


      .row.align-items-stretch.justify-content-center.mb-5
        .col-md-6.col-lg-6.mb-4(data-aos="fade-down")
          .tarjeta.bg-color-5.p-4.rounded-4.tarjeta-label.border-color-1.ms-md-5.h-100
            .tarjeta-label__img-wrapper
              img(src='@/assets/curso/tema4/img02.png' alt='Fondant cubierta')
            .ms-lg-5.ms-0.ps-md-3
              p.mb-2 <b>Budines</b>: postres horneados al baño maría, de textura firme pero suave. Pueden ser de diversos sabores (coco, pan, queso, dulce de leche). El flan y el pudín son ejemplos representativos.
              
              
        .col-md-6.col-lg-6.mb-4(data-aos="fade-up")
          .tarjeta.bg-color-5.p-4.rounded-4.tarjeta-label.border-color-1.ms-md-5.h-100
            .tarjeta-label__img-wrapper
              img(src="@/assets/curso/tema4/img03.png", alt="Fondant modelable")
            .ms-lg-5.ms-0.ps-md-3
              p.mb-2 <b>Natillas</b>: preparación a base de leche, yemas, azúcar y aromatizantes (vainilla, canela, limón). Se espesan por coagulación de las yemas, alcanzando una temperatura de 82 – 85 °C. Se sirven frías, tradicionalmente acompañadas de galleta.
              
      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
        .col-lg-10          
          .titulo-sexto.mb-4.color-acento-contenido
            h5 
              b Figura 6. 
              span Técnica de elaboración de natillas
          figure.mb-2
            img.d-none.d-lg-block(src='@/assets/curso/tema4/img12.png', alt='La figura muestra la técnica de elaboración de una masa quebrada por medio del método de arenado. Explicación debajo de la imagen. 1. Todos los ingredientes (harina, mantequilla, huevos, agua) deben estar fríos. 2. Tamizar la harina sobre la superficie de trabajo o en un bol amplio. 3. Agregar la mantequilla fría cortada en cubos pequeños. 4. Con las yemas de los dedos, frotar la mantequilla con la harina hasta obtener una textura arenosa, con grumos del tamaño de arvejas. Este proceso debe ser rápido para evitar que el calor de las manos funda la mantequilla. 5. Formar un volcán con la mezcla arenosa y agregar en el centro los líquidos (huevos batidos, agua) y el azúcar (si aplica). 6. Incorporar los líquidos con movimientos suaves, desde el centro hacia los bordes, solo hasta que la masa se una. No amasar. 7. Formar un disco, envolver en film plástico y refrigerar mínimo 30 minutos (idealmente 1-2 horas) antes de estirar y hornear.').mx-auto
            img.d-block.d-lg-none(src='@/assets/curso/tema4/img13.png', alt='La figura muestra la técnica de elaboración de una masa quebrada por medio del método de arenado. Explicación debajo de la imagen. 1. Todos los ingredientes (harina, mantequilla, huevos, agua) deben estar fríos. 2. Tamizar la harina sobre la superficie de trabajo o en un bol amplio. 3. Agregar la mantequilla fría cortada en cubos pequeños. 4. Con las yemas de los dedos, frotar la mantequilla con la harina hasta obtener una textura arenosa, con grumos del tamaño de arvejas. Este proceso debe ser rápido para evitar que el calor de las manos funda la mantequilla. 5. Formar un volcán con la mezcla arenosa y agregar en el centro los líquidos (huevos batidos, agua) y el azúcar (si aplica). 6. Incorporar los líquidos con movimientos suaves, desde el centro hacia los bordes, solo hasta que la masa se una. No amasar. 7. Formar un disco, envolver en film plástico y refrigerar mínimo 30 minutos (idealmente 1-2 horas) antes de estirar y hornear.').mx-auto

          figcaption 
            b Nota. 
            | SENA, (2026).

    separador
    
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 4.2 <i>Bavarois</i>, <i>mousses</i> y <i>soufflés</i>

    .bloque-texto-g.bg-color-7.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/img04.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-3 Los <i>bavarois</i>, <i>mousses</i> y <i>soufflés</i> son preparaciones clásicas de la repostería que se caracterizan por su textura ligera, suave y aireada. Estos postres se elaboran a partir de diferentes técnicas que permiten incorporar aire a las mezclas, logrando consistencias delicadas y agradables al paladar.
        <br>
        p.mb-0 Cada una de estas preparaciones presenta características particulares: el <i>bavarois</i> combina una base cremosa con gelatina para obtener una textura firme y suave; la <i>mousse</i> se distingue por su ligereza y cremosidad; y el <i>soufflé</i> se caracteriza por su volumen y esponjosidad al ser horneado. Estas elaboraciones permiten diversificar la oferta de postres y aportar variedad de sabores y presentaciones en la repostería.

    .row.align-items-stretch.justify-content-center.mb-5
      .col-md-6.col-lg-6.col-xl-4.mb-4(data-aos="fade-down")
        .tarjeta.bg-color-5.p-4.rounded-4.tarjeta-label.border-color-1.ms-md-5.h-100
          .tarjeta-label__img-wrapper
            img(src='@/assets/curso/tema4/img05.png' alt='Bavarois')
          .ms-lg-5.ms-0.ps-md-3
            p.mb-2 <b><i>Bavarois</i> (<i>bavaroise</i>)</b>: postre moldeado de textura sedosa, a base de crema inglesa, gelatina y crema <i>chantilly</i> montada. Se refrigera hasta que cuaja. Puede aromatizarse con café, chocolate, frutas o licores.

      .col-md-6.col-lg-6.col-xl-4.mb-4(data-aos="fade-down")
        .tarjeta.bg-color-5.p-4.rounded-4.tarjeta-label.border-color-1.ms-md-5.h-100
          .tarjeta-label__img-wrapper
            img(src='@/assets/curso/tema4/img06.png' alt='Soufflé')
          .ms-lg-5.ms-0.ps-md-3
            p.mb-2 <b><i>Soufflé</i></b>: postre espectacular que se infla en el horno gracias a las claras montadas. Puede ser caliente (<i>soufflé</i> caliente) o frío (<i>soufflé</i> frío, que no se hornea). El <i>soufflé</i> caliente debe servirse inmediatamente salido del horno para disfrutar de su textura esponjosa.

      .col-md-6.col-lg-6.col-xl-4.mb-4(data-aos="fade-up")
        .tarjeta.bg-color-5.p-4.rounded-4.tarjeta-label.border-color-1.ms-md-5.h-100
          .tarjeta-label__img-wrapper
            img(src="@/assets/curso/tema4/img07.png", alt="Mousse")
          .ms-lg-5.ms-0.ps-md-3
            p.mb-2 <b><i>Mousse</i></b>: preparación aireada que puede ser dulce o salada. La aireación se logra mediante claras montadas o crema <i>chantilly</i>. Puede llevar gelatina para darle mayor firmeza. La <i>mousse</i> de chocolate es la más conocida.
            
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-10          
        .titulo-sexto.mb-4.color-acento-contenido
          h5 
            b Figura 7. 
            span Técnica de elaboración de <i>mousse</i>
        figure.mb-2
          img.d-none.d-lg-block(src='@/assets/curso/tema4/img14.png', alt='La figura muestra el paso a paso de la técnica de la elaboración del mousse. 1.Fundir chocolate con un poco de crema de leche al baño maría o microondas. 2.Montar crema de leche a medio punto (chantilly). 3.Separar las yemas (opcional) y montar claras a punto de nieve con una pizca de azúcar. 4.Incorporar la crema montada al chocolate fundido con movimientos envolventes. 5.Incorporar las claras montadas suavemente, en dos o tres veces, cuidando de no perder el aire. 6.Dividir la mousse en cuencos individuales. 7.Refrigerar mínimo 4 horas antes de servir. 8.Servir frío y disfrutar con adiciones opcionales (frutas, virutas).').mx-auto
          img.d-block.d-lg-none(src='@/assets/curso/tema4/img15.png', alt='La figura muestra el paso a paso de la técnica de la elaboración del mousse. 1.Fundir chocolate con un poco de crema de leche al baño maría o microondas. 2.Montar crema de leche a medio punto (chantilly). 3.Separar las yemas (opcional) y montar claras a punto de nieve con una pizca de azúcar. 4.Incorporar la crema montada al chocolate fundido con movimientos envolventes. 5.Incorporar las claras montadas suavemente, en dos o tres veces, cuidando de no perder el aire. 6.Dividir la mousse en cuencos individuales. 7.Refrigerar mínimo 4 horas antes de servir. 8.Servir frío y disfrutar con adiciones opcionales (frutas, virutas).').mx-auto

        figcaption  Nota.  SENA, (2026).

    separador
    
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 4.3 Postres helados (semifríos, helados, sorbetes)

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-12
        p.mb-3 Los postres helados son preparaciones de repostería que se caracterizan por servirse a bajas temperaturas, ofreciendo una textura refrescante y agradable al paladar. Estos postres se elaboran a partir de diferentes ingredientes y técnicas que permiten obtener mezclas cremosas o ligeras, ideales para diversas ocasiones.
        p.mb-0 Dentro de esta categoría se encuentran los semifríos, los helados y los sorbetes, cada uno con características particulares en su preparación y textura. Mientras algunos incorporan lácteos para lograr mayor cremosidad, otros se elaboran principalmente con frutas y agua, lo que permite ofrecer una variedad de sabores y opciones dentro de la repostería fría.

    .row.justify-content-center.align-items-center.mb-0(data-aos="fade-right")
      .col-lg-4.col-md-8.mb-3.mb-lg-0
        figure
          img(src='@/assets/curso/tema4/img08.png', alt='')
      .col-lg-8
        SlyderF(columnas="col-md-12 col-lg-6")
          .tarjeta.bg-color-7.h-100
            img(src='@/assets/curso/tema4/img09.png' alt='Helado')
            .p-4
              h4.text-center Helado (<i>ice cream</i>)
              p.text-center Mezcla de leche, crema, azúcar y aromas, que se bate durante el congelamiento para incorporar aire (crecimiento) y evitar la formación de cristales grandes de hielo.

          .tarjeta.bg-color-7.h-100
            img(src='@/assets/curso/tema4/img10.png' alt='Sorbete')
            .p-4
              h4.text-center Sorbete (<i>sorbet</i>)
              p.text-center Similar al helado, pero sin lácteos, a base de agua, azúcar y pulpa de fruta. Textura más ligera y refrescante.

          .tarjeta.bg-color-7.h-100
            img(src='@/assets/curso/tema4/img11.png' alt='Semifrío')
            .p-4
              h4.text-center Semifrío (<i>semifreddo</i>)
              p.text-center Postre congelado que no requiere máquina de helados. Se basa en una <i>mousse</i> o crema (yemas, azúcar, crema montada, claras montadas) que se congela en molde.




</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
