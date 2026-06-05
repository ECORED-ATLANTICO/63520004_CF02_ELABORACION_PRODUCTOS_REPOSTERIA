<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema:
        'Identifica y marca la diferencia: evaluando conocimientos en repostería, gestión e inocuidad',
      titulo: 'Identifica y marca la diferencia',
      introduccion:
        '<b>Objetivo:</b> evaluar y reforzar la comprensión del aprendiz sobre técnicas de elaboración en repostería, control de calidad e inocuidad, gestión de costos de producción, manejo de formatos y disposición adecuada de residuos, mediante la identificación de afirmaciones correctas e incorrectas relacionadas con el componente formativo.',
      barajarPreguntas: true,
      titulo_aprobado: '¡EXCELENTE!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto: '¿A qué se refiere el término <i>mise en place</i>?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Únicamente a la decoración final del producto.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'A un tipo de masa fermentada.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'A organizar previamente ingredientes, utensilios y equipos antes de iniciar la preparación.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'A un método de fijación de precios.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Correcto. La <i>mise en place</i> significa “poner en su lugar” y consiste en organizar previamente ingredientes, utensilios y equipos antes de iniciar la preparación.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 2,
          texto:
            '¿Por qué el exceso de amasado es perjudicial en las masas quebradas?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Porque desarrolla el gluten y la masa pierde su textura friable y arenosa.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Porque los ingredientes se separan y la masa se corta.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Porque la mantequilla se derrite y quema la masa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Porque impide que el azúcar se disuelva.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Muy bien, el exceso de amasado desarrolla el gluten y vuelve la masa más elástica, perdiendo su característica textura friable y arenosa.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 3,
          texto: '¿En qué consiste el método de elaboración Genovés?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'En cremar mantequilla con azúcar y luego agregar los huevos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'En batir huevos y azúcar al baño María hasta que tripliquen su volumen.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'En montar las claras por separado e incorporarlas al final.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'En utilizar levadura fresca y realizar múltiples pliegues.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Así es, en este método los huevos se calientan a 40–45°C y luego se baten hasta lograr el “punto de cinta”.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 4,
          texto: '¿Por qué se eleva el hojaldre durante el horneado?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Principalmente por la acción de la levadura biológica.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Por la reacción del bicarbonato con un ácido.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Por el vapor generado entre las capas de masa y mantequilla.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Por el batido intenso de los huevos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Exacto, el hojaldre se eleva por el vapor generado entre las capas de masa y mantequilla durante el horneado.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 5,
          texto: '¿Cuál es la estructura característica de la pasta choux?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Forma una estructura con múltiples capas finas y crujientes.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Forma una estructura hueca en su interior gracias al vapor.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Forma una estructura quebradiza y arenosa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Forma una estructura densa y pesada, similar al pan.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Correcto, el vapor actúa como agente leudante, inflando la masa mientras la estructura de huevo y gluten la sostiene.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 6,
          texto:
            '¿Cómo debe cocinarse correctamente la crema pastelera para garantizar su inocuidad?',
          imagen: require('@/assets/actividad/imagen6.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Debe hervir vigorosamente durante 10 minutos',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Se cocina a fuego lento sin superar los 60°C.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'No requiere cocción, solo mezclar ingredientes fríos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Se cocina entre 85-90°C sin llegar a hervir para evitar que se corte.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Muy bien, no debe hervir. Se cocina entre 85–90°C para evitar que se corte o coagule excesivamente.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 7,
          texto: '¿Cuál es la función del azúcar invertido en repostería?',
          imagen: require('@/assets/actividad/imagen7.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Es el principal agente leudante.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Es un edulcorante bajo en calorías.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Ayuda a evitar la cristalización y mantiene la humedad en los productos.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Se utiliza exclusivamente para dar color dorado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Correcto, al hidrolizarse en glucosa y fructosa, mejora la textura y prolonga la vida útil.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 8,
          texto: '¿Por qué se espesan las natillas?',
          imagen: require('@/assets/actividad/imagen8.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Por la gelatinización del almidón.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Por la evaporación del agua.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Por la adición de gelatina.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Principalmente por la coagulación de las yemas de huevo.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Muy bien, se espesan principalmente por coagulación de las yemas, no por almidón.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 9,
          texto:
            '¿Qué significa que un producto tenga una actividad de agua (aw) mayor a 0.85?',
          imagen: require('@/assets/actividad/imagen9.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Que el producto es de alta calidad.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Que tiene una vida útil extremadamente larga.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Que es un ambiente favorable para el crecimiento bacteriano.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Que debe conservarse exclusivamente en congelación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Correcto, la mayoría de las bacterias requieren aw superior a 0.85 para desarrollarse.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es la temperatura de conservación para alimentos fríos según las BPM?',
          imagen: require('@/assets/actividad/imagen10.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Temperaturas iguales o menores a 10°C.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Temperaturas iguales o menores a 4°C.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Temperaturas entre 5°C y 15°C.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Temperaturas bajo cero (-5°C).',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Muy bien, esta temperatura limita la proliferación microbiana.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 11,
          texto:
            '¿Cuál es el tiempo máximo permitido para enfriar una preparación caliente de 60 °C a 21 °C?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: '2 horas.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: '4 horas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: '6 horas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: '12 horas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Así es. Debe pasar de 60 °C a 21 °C en máximo 2 horas, y luego a 4 °C en máximo 4 horas adicionales.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 12,
          texto: '¿Cuál de los siguientes es un ejemplo de costo indirecto?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La harina utilizada en una receta de bizcocho.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El chocolate para la cobertura de una torta.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Los huevos para una crema pastelera.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Los servicios públicos (luz, agua, gas) y el arriendo del local.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Correcto, esos son costos indirectos; los costos directos corresponden a materias primas y elementos identificables en cada producto.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 13,
          texto: '¿Cómo se calcula el porcentaje de rendimiento?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                '(Peso inicial de la materia prima / Peso final del producto) x 100.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: '(Costo total / Número de porciones) x 100.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: '(Peso de la merma / Peso final) x 100.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                '(Peso final del producto / Peso inicial de la materia prima) x 100.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Muy bien, esta fórmula permite determinar el porcentaje de aprovechamiento.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 14,
          texto: '¿Qué es la merma técnica?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La que ocurre por errores del manipulador, como un derrame.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El desperdicio de producto terminado por falta de ventas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'La diferencia entre el precio de venta y el costo de producción.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'La pérdida de materia prima que es inevitable (evaporación, cáscaras).',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Exacto, la merma técnica es inevitable (evaporación, cáscaras, etc.). La causada por errores es merma evitable.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 15,
          texto:
            '¿En qué consiste el método del factor para fijar precios de venta?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Sumar todos los costos del producto y dividirlos entre las unidades producidas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Multiplicar el costo de la materia prima por un número que cubre costos y utilidad.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Comparar el precio con la competencia y fijar uno similar.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Agregar un impuesto fijo al costo de producción.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Así es, en repostería suele usarse un factor entre 3 y 5.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 16,
          texto:
            'Según la Resolución 2184 de 2019, ¿cuál es el código de colores para residuos aprovechables como plástico, vidrio y papel?',
          imagen: require('@/assets/actividad/imagen6.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verde.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Blanco.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Negro.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Azul.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Correcto, así lo establece la Resolución 2184 de 2019.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 17,
          texto:
            '¿Los guantes de manipulación reemplazan completamente el lavado de manos?',
          imagen: require('@/assets/actividad/imagen7.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Sí, siempre que sean de un solo uso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Sí, siempre que sean de un solo uso.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Sí, siempre que sean de látex.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'No, los guantes no sustituyen el lavado de manos; deben cambiarse con frecuencia.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Correcto, los guantes no sustituyen el lavado de manos; deben cambiarse con frecuencia.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 18,
          texto: '¿Cómo influye el pH en los productos de repostería?',
          imagen: require('@/assets/actividad/imagen8.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Solo influye en el color, no en la conservación.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Influye en el sabor y en la conservación (valores ácidos inhiben el crecimiento microbiano).',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Solo es relevante para calcular los costos de producción.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'No tiene ningún efecto en los productos de repostería.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Así es, valores más ácidos pueden inhibir el crecimiento microbiano.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 19,
          texto:
            '¿Cuál es un factor clave para lograr un buen volumen al montar crema chantilly?',
          imagen: require('@/assets/actividad/imagen9.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Usar todos los utensilios y la crema muy fríos.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Usar leche desnatada en lugar de crema de leche.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Batir a temperatura ambiente para que la grasa se ablande.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Añadir el azúcar al inicio y batir lentamente.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Exacto, el frío favorece la estabilidad de la grasa y la incorporación de aire.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 20,
          texto:
            '¿En qué consiste la estrategia recomendada por el "precio psicológico"?',
          imagen: require('@/assets/actividad/imagen10.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Describir los precios con cifras abiertas, ejemplo:  $ 19.900.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Calcular el precio sumando un impuesto fijo del 30 % al costo total de la materia prima.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Fijar siempre el precio más bajo del mercado sin importar los costos de producción, para captar rápidamente clientes.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Redondear el precio con cifras cerradas, ejemplo:  $ 19.000.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Perfecto, el precio psicológico suele terminar en 9 o 5 porque genera mayor percepción de economía.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
      ],
      mensaje_final_aprobado:
        '¡Excelente!, ha superado la actividad y demuestra sólidos conocimientos sobre el componente formativo.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
