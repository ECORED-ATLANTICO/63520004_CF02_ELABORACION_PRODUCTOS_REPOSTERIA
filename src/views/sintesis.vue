<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-3 Este componente formativo Técnicas de elaboración de productos de repostería y gestión administrativa ambiental articula el dominio técnico propio de la repostería con la planificación productiva, el control administrativo y la responsabilidad ambiental, comprendiendo que la calidad no es un resultado aislado del talento manual, sino la consecuencia de procesos estandarizados y gestionados de manera integral. Su estructura formativa parte de los fundamentos técnicos de las masas básicas —quebradas, batidas, hojaldradas, escaldadas y fermentadas— y avanza hacia la elaboración de cremas, jarabes, coberturas y preparaciones especializadas como natillas, <i>mousses</i>, <i>bavarois</i> y postres helados, integrando además principios de decoración y presentación que consolidan la experiencia sensorial del producto final.
    <br>
    p.mb-0 De forma paralela, el componente incorpora la gestión de costos como herramienta de sostenibilidad económica, abordando la diferenciación entre costos directos e indirectos, el cálculo de rendimientos y mermas, y la fijación estratégica de precios a partir de métodos técnicos de costeo. Asimismo, introduce el uso de formatos y registros de producción como instrumentos de control, estandarización y trazabilidad, fortaleciendo la organización del proceso productivo. Finalmente, integra el manejo y disposición adecuada de residuos conforme a la normativa ambiental colombiana, consolidando una visión profesional que vincula técnica, administración y sostenibilidad. Su apropiación constituye la base para un desempeño ético, competitivo y responsable en el campo de la repostería profesional.

    .row.justify-content-center
      .col-lg-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Este componente formativo “Técnicas de elaboración de productos de repostería y gestión administrativa ambiental”, organizado en bloques temáticos que integran la técnica repostera, el control de calidad, la gestión administrativa y la responsabilidad ambiental. La estructura inicia con la terminología técnica en repostería y la clasificación de las masas básicas (quebradas, batidas, hojaldradas, escaldadas y fermentadas) junto con sus principales aplicaciones. Continúa con la elaboración de jarabes, cremas, coberturas y salsas dulces, así como productos especializados como natillas, bavarois, mousses, soufflés y postres helados. El esquema incorpora además los fundamentos de decoración, el uso del círculo cromático, técnicas básicas de presentación y emplatado, y los parámetros de calidad e inocuidad en la elaboración, incluyendo aplicación de BPM, puntos críticos de control y normas de seguridad ocupacional. En el ámbito administrativo, aborda los costos de producción, diferenciación de costos directos e indirectos, cálculo de rendimientos y mermas, fijación de precios y diligenciamiento de formatos y registros. Finalmente, integra el manejo y disposición de residuos, su clasificación, técnicas de segregación y almacenamiento, y la legislación ambiental aplicable, consolidando una visión integral del proceso productivo en repostería profesional.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
