Aquí está la traducción al español del artículo:

---

# Estudio sobre las vías de reducción de carbono en el transporte urbano de pasajeros basado en dinámica de sistemas

**Ranqi Liu y Ning Liu**

---

## Resumen

El control de las emisiones de carbono en el transporte de pasajeros se reconoce como un componente crítico para alcanzar los objetivos de doble carbono en medio de la acelerada urbanización. Se ha desarrollado un modelo de dinámica de sistemas que incorpora factores poblacionales y económicos, consumo energético, operación del tráfico y control de emisiones de carbono. Mediante la identificación de límites y la validación de las relaciones entre variables, se estableció un modelo de simulación. Las simulaciones de escenarios revelaron que, entre las intervenciones de política única, la optimización del transporte público y las mejoras en tecnología energética demostraron mayor efectividad que la gestión de la demanda de viajes. Las combinaciones de doble política mejoraron significativamente la eficiencia en la reducción de emisiones, con una efectividad clasificada de la siguiente manera: políticas de transporte público y tecnología energética (11,32%), políticas de transporte público y demanda de viajes (10,58%), y políticas de tecnología energética y demanda de viajes (8,94%). Los hallazgos sugieren que las medidas individuales son insuficientes para alcanzar los objetivos de reducción de emisiones. En cambio, una sinergia de políticas multidimensional —que integre mejoras tecnológicas, optimización estructural y orientación conductual— es esencial para proporcionar una vía sistemática de reducción de carbono para el desarrollo del transporte urbano.

**Palabras clave:** Transporte de pasajeros, Dinámica de sistemas, Análisis de escenarios, Vía de reducción de emisiones

---

## Introducción

El "Pico de Carbono" y la "Neutralidad de Carbono", conocidos comúnmente como los "Objetivos de Doble Carbono" de China, constituyen una estrategia nacional clave que busca alcanzar el pico de emisiones de dióxido de carbono para 2030 y lograr la neutralidad de carbono (emisiones netas cero de CO₂) para 2060. Este compromiso representa la significativa contribución de China a la acción climática global. Con el continuo avance de la urbanización mundial, las demandas de viaje de los residentes urbanos se han vuelto cada vez más diversas, personalizadas y frecuentes. Como infraestructura crítica que sostiene las operaciones urbanas y la vida cotidiana, el sistema de transporte urbano se reconoce como un indicador clave en la evaluación del desarrollo urbano sostenible. Sin embargo, los modelos de transporte tradicionales se caracterizan por desequilibrios estructurales, congestión de tráfico severa y baja eficiencia energética, lo que contribuye al crecimiento continuo de las emisiones de carbono de los sistemas de transporte y ejerce una presión significativa sobre los ecosistemas urbanos y la calidad de vida de los residentes. Los estudios indican que el sector del transporte representa aproximadamente el 24% de las emisiones globales de carbono, siendo el transporte urbano de pasajeros uno de los principales contribuyentes. En China, en particular, el rápido aumento en la posesión de vehículos y el aumento persistente de la densidad de población urbana han resultado en un incremento anual de aproximadamente el 1,7% en las emisiones de carbono relacionadas con el transporte. Esta tendencia ha sido aún más pronunciada en los países en desarrollo, planteando un desafío significativo para el logro de los objetivos de "pico de carbono" y "neutralidad de carbono".

En este contexto, lograr una transición baja en carbono en los sistemas de transporte urbano de pasajeros y explorar vías sostenibles de reducción de emisiones han surgido como preocupaciones centrales para investigadores y responsables de políticas a nivel mundial. La investigación principal se ha concentrado principalmente en tres dimensiones: innovación tecnológica, optimización estructural y regulación conductual. La adopción y promoción de nuevas tecnologías energéticas se reconocen como enfoques tecnológicos clave para mejorar la eficiencia en la reducción de emisiones. Los ajustes en la estructura del transporte —como aumentar la participación del transporte público y optimizar el diseño del tránsito ferroviario— constituyen la base estructural para la reducción sistémica de emisiones. Mientras tanto, fomentar comportamientos de viaje sostenibles —como el ciclismo, caminar o usar el transporte público— se considera un mecanismo social vital para alcanzar los objetivos de reducción de carbono urbano.

Sin embargo, el sistema de transporte urbano es inherentemente complejo, caracterizado por interacciones multivariables y robustos bucles de retroalimentación. Como resultado, las medidas de política única a menudo son insuficientes para lograr los resultados esperados. En consecuencia, los enfoques de modelado sistémico han ganado creciente atención académica. Entre ellos, el modelo de Dinámica de Sistemas (DS) se emplea ampliamente en el estudio de las emisiones de carbono del transporte urbano, dada su capacidad para analizar sistemas de retroalimentación complejos, simular efectos de políticas y pronosticar escenarios.

---

## Innovaciones

La creciente complejidad de la demanda de viaje urbano y la acelerada transformación estructural de los sistemas de transporte plantean desafíos cada vez más complejos y sistémicos para el control de las emisiones de carbono del transporte urbano de pasajeros. Aunque se ha logrado un progreso sustancial en la identificación de instrumentos de política, la exploración de vías técnicas y el análisis de escenarios, gran parte de la investigación actual sigue siendo predominantemente de enfoque macro. Se ha prestado limitada atención académica a los mecanismos de acoplamiento dinámico entre los diversos subsistemas —como población y economía, consumo de energía, estructura vial, operaciones de tráfico y gobernanza del carbono— dentro del sistema de transporte urbano.

Por lo tanto, este estudio busca desarrollar un modelo de simulación basado en Dinámica de Sistemas para reducir las emisiones de carbono del transporte urbano de pasajeros mediante la incorporación de cinco subsistemas clave. Tomando a Beijing como caso de estudio y utilizando datos estadísticos de 2010 a 2024, el modelo integra datos de operación del transporte, información sobre la estructura energética y parámetros de gobernanza del carbono. Se emplean escenarios de política única y doble política para evaluar los efectos dinámicos de diversas configuraciones de políticas sobre las emisiones de carbono dentro del sistema de transporte urbano de pasajeros.

---

## Modelo de Dinámica de Sistemas para las Emisiones de Carbono del Transporte Urbano de Pasajeros

### Límite del sistema

La definición del límite del sistema sirvió como base fundamental para la construcción del modelo de Dinámica de Sistemas (DS), determinando la inclusión y exclusión de variables dentro del marco del modelo. Como sistema altamente complejo y dinámico, el modelo DS para las emisiones de carbono del transporte urbano de pasajeros está típicamente compuesto por múltiples subsistemas interrelacionados. En este estudio, el sistema comprende cinco subsistemas funcionales: población y economía, consumo de energía, infraestructura vial urbana, operación del tráfico y emisiones de carbono. Las interacciones entre estos subsistemas constituyen la base conceptual central para la evolución de las vías de reducción de carbono urbano dentro de los sistemas de transporte.

Basándose en las características de la estructura energética del transporte urbano de pasajeros —donde la gasolina, el diésel y la electricidad sirven como las principales fuentes de energía de uso final— y considerando la disponibilidad de datos reales, el límite del sistema y la distribución de la estructura energética correspondiente definidos en este estudio se ilustran en la Figura 1.

### Diagrama de bucle causal del sistema

Utilizando el software Vensim PLE, las relaciones causales entre las variables relevantes dentro del sistema de emisiones de carbono del transporte urbano de pasajeros fueron visualizadas y modeladas. Se construyó un diagrama de retroalimentación causal para ilustrar las interacciones entre variables (Figura 2).

*(La parte roja representa el Subsistema de Población y Economía; las partes naranjas representan el Subsistema de Operación del Tráfico; la parte verde representa el Subsistema de Control de Emisiones de Carbono; las partes moradas representan el Subsistema de Consumo de Energía; la parte azul representa el Subsistema de Vialidad Urbana)*

Se pueden observar que las relaciones causales entre los diversos elementos involucrados en la mejora de las vías de reducción de carbono del transporte urbano de pasajeros son complejas y mutuamente restrictivas. En total, se establecieron 15 bucles de retroalimentación específicos en este artículo; sin embargo, debido a limitaciones de espacio, solo se presentan los principales.

**Bucle 1:** Emisiones de Carbono del Transporte de Pasajeros → (+) Contaminación por CO₂ → (+) Pérdida por Contaminación Ambiental → (+) Retraso de Pérdida → (–) PIB Urbano → (+) Producción de la Industria Primaria → (+) Demanda de Transporte Urbano de Pasajeros → (+) Oferta de Transporte Urbano de Pasajeros → (+) Volumen de Pasajeros de Taxis Urbanos → (+) Viajes de Pasajeros en Taxi (Eléctrico) → (+) Consumo de Electricidad de los Taxis.

**Bucle 2:** Emisiones de Carbono del Transporte de Pasajeros → (+) Contaminación por CO₂ → (+) Pérdida por Contaminación Ambiental → (+) Retraso de Pérdida → (–) PIB Urbano → (+) Producción de la Industria Primaria → (+) Demanda de Transporte Urbano de Pasajeros → (+) Oferta de Transporte Urbano de Pasajeros → (+) Volumen de Pasajeros de Autobuses Públicos (Trolebús Eléctrico) → (+) Volumen de Pasajeros en Trolebús Eléctrico Público → (+) Consumo de Energía de los Trolebuses Públicos.

**Bucle 3:** Emisiones de Carbono del Transporte de Pasajeros → (+) Contaminación por CO₂ → (+) Pérdida por Contaminación Ambiental → (+) Retraso de Pérdida → (–) PIB Urbano → (+) Inversión en Activos Fijos → (+) Kilometraje de Tránsito Ferroviario → (+) Capacidad de Pasajeros del Tránsito Ferroviario Urbano → (+) Volumen de Pasajeros del Tránsito Ferroviario Urbano → (+) Volumen de Pasajeros del Metro → (+) Consumo de Electricidad del Metro.

### Supuestos del modelo

1. Se asumió que el proceso de influencia de las vías de reducción de carbono del transporte urbano de pasajeros es continuo y estable, sin considerar el impacto de cambios ambientales repentinos u otros factores imprevistos.
2. El modelo del sistema construido fue tratado como un sistema cerrado, excluyendo las perturbaciones externas.
3. La investigación incluyó cuatro subsistemas: el subsistema población-economía, el subsistema de consumo de energía, el subsistema de vialidad urbana y el subsistema de transporte-emisiones de carbono; otros aspectos no fueron considerados.
4. Se asumió que la vía de reducción de carbono del transporte urbano de pasajeros tiene efectos recíprocos en cada uno de los subsistemas del modelo.
5. Este estudio se centró exclusivamente en la vía de reducción de carbono del transporte urbano de pasajeros, sin considerar la influencia de otros sectores o dominios.

### Diagrama de flujo y stock del sistema

Tras completar el análisis del bucle causal, se construyó un modelo de dinámica de sistemas utilizando el software Vensim PLE. El modelo se dividió en cinco módulos funcionales: Subsistema de Población y Economía, Subsistema de Consumo de Energía, Subsistema de Vialidad Urbana, Subsistema de Operación del Tráfico y Subsistema de Control de Emisiones de Carbono.

El subsistema de población y economía está centrado en dos variables de stock principales: la población urbana y el PIB urbano. El componente poblacional se ajusta dinámicamente a través de las tasas de natalidad, mortalidad y migración, esta última influenciada por el PIB per cápita. El crecimiento económico está impulsado por la producción combinada de las industrias primaria, secundaria y terciaria.

El subsistema de operación del tráfico ilustra visualmente las relaciones dinámicas entre la demanda de transporte urbano de pasajeros y los componentes operativos. Los módulos principales incluyen tres categorías principales de transporte: tránsito ferroviario urbano, autobuses públicos y automóviles privados.

El subsistema de control de emisiones de carbono comienza con los coeficientes de emisión para vehículos de nueva energía, vehículos de gasolina y locomotoras eléctricas, y forma una estructura de equilibrio dinámico junto con las emisiones totales de CO₂, las reducciones de emisiones y los niveles de contaminación.

El subsistema de vialidad urbana está estructurado en torno a la longitud de las vías urbanas como variable de stock principal. Los impulsores clave incluyen el impacto del crecimiento del PIB per cápita en el aumento de la inversión en activos fijos, lo que a su vez promueve la expansión de la infraestructura urbana y el kilometraje ferroviario.

El subsistema de consumo de energía adopta una estructura de concentrador y radio para representar claramente las relaciones de flujo de energía, centrado en el "volumen de consumo de energía", con ramas que se extienden a diferentes modos de transporte —autobuses públicos, taxis, automóviles privados y metros.

### Variables del sistema y ecuaciones clave

En el proceso de modelado del sistema, las variables involucradas se clasificaron en: 5 variables de stock, 10 variables de tasa, 32 variables auxiliares y 19 constantes. Las ecuaciones principales incluyen (entre otras):

- PIB Urbano = INTEG(Aumento del PIB – Disminución del PIB, 14.114,3)
- Población Urbana = INTEG(Entrada de Población + Nacimientos – Salida de Población – Defunciones, 2.154)
- Reducción de CO₂ = Emisiones de Carbono del Transporte de Pasajeros × Eficiencia de Gobernanza del Carbono
- Inversión en Activos Fijos = PIB Urbano × Participación de la Inversión en Tránsito Ferroviario
- Consumo de Energía del Trolebús Eléctrico = Consumo Unitario de Nuevos Vehículos de Energía × Volumen de Pasajeros del Trolebús Eléctrico

---

## Validación del modelo

Se realizó una validación completa del modelo mediante tres métodos: prueba de consistencia estructural, análisis de sensibilidad del paso temporal e ajuste de datos históricos. El modelo pasó satisfactoriamente todos los procedimientos de validación.

### Prueba de aplicabilidad

El software Vensim PLE devolvió el resultado *"El modelo está OK"*, confirmando que el modelo pasó la prueba de aplicabilidad y demostró solidez estructural e idoneidad para la simulación.

### Prueba de sensibilidad del paso temporal

Se seleccionó el PIB Urbano como indicador de referencia. El paso temporal de simulación se estableció en 0,25, 0,5 y 1, respectivamente. La comparación de las curvas de salida de la simulación reveló solo desviaciones mínimas, indicando que el modelo exhibió excelente consistencia y estabilidad.

### Validación histórica

Se realizó un ajuste de datos históricos utilizando datos de 2010 a 2024. La desviación entre los valores reales y simulados del PIB se mantuvo dentro del 5%, confirmando la validez del modelo. De igual manera, el error entre los valores reales y simulados del volumen de pasajeros del tránsito ferroviario urbano también se mantuvo dentro del 5%.

### Análisis de sensibilidad

Se seleccionó el PIB urbano como variable de referencia para el análisis de sensibilidad, utilizando la variable de relación de costos energéticos para realizar la prueba. Los resultados confirmaron la robustez del modelo.

---

## Simulación de escenarios de reducción de carbono en el transporte urbano de pasajeros

### Configuración de referencia

El período de simulación se estableció de 2010 a 2040, con un paso temporal de un año. Primero se simuló un escenario de referencia sin introducir ajustes de política, manteniendo constantes todas las condiciones iniciales del sistema. Luego se introdujeron múltiples variables de política secuencialmente para simular intervenciones de política única y combinaciones de doble política.

### Emisiones de carbono por modo de transporte

Los análisis de simulación se realizaron para las emisiones de carbono de autobuses públicos, taxis y tránsito ferroviario (Figura 11). Los resultados mostraron que las emisiones tanto de autobuses públicos como de taxis siguieron una tendencia decreciente, mientras que las emisiones del tránsito ferroviario exhibieron un aumento gradual. Estas tendencias fueron impulsadas principalmente por el crecimiento poblacional sostenido, la expansión de la demanda de transporte y el aumento de la frecuencia de viaje per cápita.

Durante la etapa inicial de simulación, los modos de transporte con combustibles fósiles tradicionales permanecieron dominantes. A medida que el sistema evolucionó, las emisiones de autobuses y taxis disminuyeron constantemente, mientras que las emisiones del tránsito ferroviario alcanzaron un pico. Esta fase marcó un punto de inflexión crítico en la transformación del sistema de transporte de alta emisión a operación eficiente y baja en carbono.

---

## Análisis de escenarios de política única

### Política de transporte público

Se diseñaron dos escenarios: aumento del 5% y 10% en el kilometraje total del tránsito ferroviario urbano respecto al nivel de referencia. Los resultados mostraron que las emisiones de carbono del transporte de pasajeros disminuyeron un **7,23% y 9,18%**, respectivamente. Las políticas de transporte público contribuyeron a optimizar la estructura energética del transporte y mejorar la eficiencia general de los viajes.

### Política de tecnología energética

Se diseñaron dos escenarios: reducción del 5% y 10% en el consumo unitario de energía de los vehículos de nueva energía (VNE). Las emisiones de carbono disminuyeron un **7,97% y 9,53%**, respectivamente. Mejorar la eficiencia energética de los VNE desempeñó un papel significativo en la reducción del consumo de energía y las emisiones de carbono.

### Política de comportamiento de viaje

Se diseñaron dos escenarios: reducción del 5% y 10% en el volumen total de pasajeros de vehículos privados. Las emisiones disminuyeron un **8,13% y 9,88%**, respectivamente. Limitar la frecuencia del uso del automóvil privado y orientar eficazmente a los residentes hacia alternativas de viaje bajas en carbono reduce la intensidad energética del sistema de transporte.

---

## Análisis de combinaciones de doble política

Se diseñaron tres tipos de combinaciones de doble política:
1. Transporte público + tecnología energética
2. Transporte público + comportamiento de viaje
3. Tecnología energética + comportamiento de viaje

Los resultados mostraron diferencias notables en el rendimiento de reducción de emisiones. La efectividad de la reducción de carbono de mayor a menor fue:

1. **Transporte público + tecnología energética: 11,32%**
2. **Transporte público + comportamiento de viaje: 10,58%**
3. **Tecnología energética + comportamiento de viaje: 8,94%**

La sinergia entre las políticas de transporte público y tecnología energética produjo el beneficio más significativo de reducción de emisiones. En comparación con las intervenciones de política única, las combinaciones de doble política demostraron mejoras más sustanciales, sugiriendo que diferentes variables de política pueden lograr una mayor complementariedad y efecto sinérgico bajo interacciones multifactoriales.

---

## Conclusiones

Este estudio estableció que el sistema de transporte urbano de pasajeros consta de cinco subsistemas principales: población y economía, consumo de energía, infraestructura vial urbana, operaciones de transporte y control de emisiones de carbono. Los hallazgos clave son:

1. **Análisis del escenario de referencia:** Las emisiones de carbono del transporte urbano de pasajeros exhiben tendencias variables según el modo de transporte.

2. **Análisis de impacto de política única:** Las tres políticas independientes contribuyeron a la reducción de carbono en distintos grados. Las políticas de transporte público y tecnología energética mostraron mayor efectividad comparativa.

3. **Evaluación de la sinergia de doble política:** La implementación de política dual resultó en mejores resultados de reducción de emisiones que las políticas individuales. La combinación de transporte público + tecnología energética produjo la reducción más sustancial.

En conclusión, los hallazgos subrayan que la vía de reducción de carbono del transporte urbano de pasajeros está influenciada por múltiples factores entrelazados. Depender de una sola estrategia de política es insuficiente para lograr resultados óptimos de reducción. Por lo tanto, la formulación futura de políticas y la gestión del transporte urbano deben adoptar un enfoque integrado, coordinando múltiples instrumentos de política para impulsar una transformación verde y baja en carbono del sistema de transporte urbano.

---

## Direcciones futuras de investigación

- **Estudios de acoplamiento multi-escala y multi-sistema:** Explorar los mecanismos de acoplamiento dinámico entre el sistema de transporte urbano de pasajeros y sistemas más amplios como la energía urbana, la planificación del uso del suelo y los modelos económicos regionales.

- **Simulación refinada y evaluación de equidad de carteras de políticas:** Cuantificar las relaciones costo-beneficio y los impactos de equidad social de diferentes combinaciones de políticas, incorporando las disparidades en la accesibilidad al transporte entre grupos de ingresos y regiones.

- **Optimización dinámica de vías tecnológicas e impacto de la innovación disruptiva:** Mejorar la integración del modelo con tecnologías emergentes —como la conducción autónoma, las plataformas de movilidad compartida y el transporte basado en hidrógeno— para simular sus vías de penetración a gran escala.

---

*Recibido: 14 de mayo de 2025; Aceptado: 20 de septiembre de 2025; Publicado en línea: 27 de octubre de 2025*
