Datos del caso2

## Análisis de los casos de  estudio suministrados.

## Estudio de otros casos (con juegos de datos reales): Falsos entendidos sobre el MTBF.

Existen ideas falsas sobre el concepto de MTBF (Mean Time Between Failures). Se tiene el concepto que representa el número esperado en horas de operación antes que el equipo presente una falla, ó ‘el tiempo de vida’ (en servicio).  Es común encontrar este tipo de interpretaciones, sin embargo, un sistema o equipo no podría estar en operación continua durante 100 o más años sin presentar una falla.  La razón que los valores de MTFB sean muy grandes (en años) se debe a que están basados en una estimación, índice (rate) de fallas  mientras se encuentra en el periodo de vida útil o en operación del producto, y se asume que podría seguir este ritmo de fallas constante de manera indefinida (es la etapa de vida del producto cuando su índice de fallas es más baja).  Durante la etapa de envejecimiento (desgaste) del producto, sus fallas son mucho más frecuentes que lo que representa el valor MTBF (ver la gráfica llamada ‘curva de la bañera’).  Es decir, no hay una relación directa entre la vida en servicio del equipo y el valor de MTBF.  Es posible encontrar un producto con un alto valor de MTBF pero con un bajo valor estimado en su vida útil de servicio.

<img src="https://ujurado.github.io/wikiprobabilidad/assets/images/grafica1.png" alt="Figura 1">

Veamos un ejemplo con los humanos:

–      Tomando una muestra de la población de 25 años: 500,000 personas

–      En el curso de un año, datos de fallas (muertes) son recolectados.

–      El tiempo de vida operacional de la población es: 500,000*1 año = 500,000 personas.año

–   A lo largo de un año, 625 personas fallaron (murieron)

–   El índice de fallas es 625 fallas / 500,000 personas.año = 0.125 fallas/año

–   El MTBF es el inverso del índice de fallas, 1 / 0.125 = 800 años

El hecho que el MTBF sea de 800 años, el tiempo de esperanza de vida de un humano (en operación) es mucho más corta y no están interrelacionadas.

La realidad es que los humanos no tienen un índice de fallas (muertes) constante.  Cuando la gente envejece, más fallas (muertes) ocurren.  Por lo tanto, la única manera real de obtener el MTBF sería que la muestra de personas de 25 años de edad alcanzara el fin de su vida útil (muerte).  Entonces el promedio de su ciclo de vida podría ser calculado.  Estaríamos de acuerdo que este número estaría en el orden de 75-80 años.

Entonces, ¿El MTBF de los humanos de 25 años sería 80 ó 800 años?

La respuesta seria tal vez, ¡ambos!  Pero, ¿cómo podría darse que la misma muestra de población tenga dos diferentes valores de MTBF tan diferentes?  La respuesta está en las asunciones.

Si el valor de MTBF de 80 años es más exacto porque refleja la vida del producto (humanos en este caso) ¿sería el mejor método para calcularlo?  Este valor es más claro e intuitivo.  Sin embargo, existen más variables que limitan el uso de este método con productos comerciales electrónicos.  La más grande limitante es el tiempo.  Para realizarlo de esta manera, habría que esperar que toda la muestra de personas de 25 años fallará (muera), y en el caso de los productos este tiempo está en alrededor de 10 a 15 años.  Además, si esperamos todo este tiempo antes de calcular el valor de MTBF, se tendrían problemas de trazabilidad y muestreo de los productos.  Es decir, ¿cómo sabría un fabricante de equipos sí su producto está aún en servicio ó si ha fallado y nunca se le ha reportado?

Aún si lo anterior fuera posible, la tecnología está cambiando constantemente y cuando estos números estén disponibles, ya no podrían ser útiles.  ¿A quién le podrían interesar los valores de MTBF de productos que han quedado obsoletos por actualizaciones debido al avance de la tecnología?

La manera objetiva de ver el MTBF es la siguiente: supongamos que un producto tiene un MTBF de 800 años, la interpretación es que de una muestra de 800 productos,  1 podría fallar al año.  Pero, nuevamente insistimos, esta es una probabilidad y dependerá de diversos factores: de las condiciones de operación (el 70% de los productos electrónicos falla por una mala calidad de la energía); de las condiciones ambientales (polvo, corrosión, erosión, altas temperaturas, etc.); y, aún antes de poner en servicio un producto, ¿quién se aseguró que le producto estuvo almacenado en condiciones óptimas y no sufrió envejecimiento debido a las condiciones de humedad y temperatura en las que estuvo expuesto?.
