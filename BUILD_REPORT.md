# Informe de construccion: Ecuador, que sistema encaja con esta plantilla

Fecha de construccion: 18 de noviembre de 2026.
Estado: publicado en GitHub el 18 de noviembre de 2026, con el visto bueno de Jesus.

## Metodo

Trabaje solo con el contexto verificado aportado para este proyecto, salvo en el cuaderno 07, donde busque estadisticas nuevas en FotMob, Ceroacero, SoFIFA, 365Scores, Sportradar y prensa ecuatoriana, y las cite con fecha. No invente filas y no complete huecos con estimaciones. Cada numero en los cuadernos lleva su fuente y su temporada al lado.

Los pasos fueron: primero, cargar la convocatoria de noviembre de 2026 y los datos de club de cada jugador. Segundo, medir los primeros cinco partidos de Gallardo con los marcadores verificados. Tercero, poner lado a lado los siete modelos tacticos, con puntos, goles, posesion, xG y logros. Cuarto, puntuar cada sistema por grupo de posiciones, del 1 al 5, con la razon escrita. Quinto, elegir el sistema principal y el once, con cambios por rol. Sexto, escribir el plan de partido y la alternativa.

La puntuacion de ajuste es mi juicio analitico, basado en los datos verificados. No es un dato medido en el campo. Por eso cada nota lleva su justificacion en el cuaderno 04, y por eso la media se calcula delante del lector.

## Fuentes

Wikipedia, pagina de la seleccion de Ecuador, a 17 de noviembre de 2026, para partidos y goles con la seleccion. Flashscore a 14 de noviembre de 2026 para Galindez. FBref para Pacho, Caicedo, Torres, Alonso, Xavi y Maresca. FootballCritic para el pase de Pacho. SoFIFA a 11 de noviembre de 2026 para Preciado. FotMob para Paez en el Chelsea Sub-21. UEFA para el PSG de Luis Enrique y el analisis del partido ante el Manchester City. Global Sports Archive para el 4-2-2-2 ante Costa Rica. OBNews, fuente secundaria, para Kleindienst y Kimmich en la Nations League. La lista completa, con fechas, esta en `data/PROVENANCE.md`.

## Resultados principales

Sistema principal: 4-2-3-1, media de ajuste 4.29 sobre 5.
Sistema alternativo: 3-4-2-1, media de ajuste 3.71 sobre 5.
Tercer sistema: 4-3-3, media de ajuste 3.29 sobre 5.

Once principal: Galindez, Hurtado, Torres, Pacho, Estupinan, Caicedo, Franco, Plata, Vite, Sarmiento y Jordy Caicedo. Capitan: Moises Caicedo. Actualizado el 18 de noviembre de 2026 en el cuaderno 07: Hurtado entra por Preciado. Top 3 de lateral derecho: 1 Jose Hurtado, 2 Bryan Ramirez, 3 Jhon Espinoza. Preciado pasa a tercera opcion. Mejor para 4-2-3-1: Hurtado. Mejor para 3-4-2-1: Ramirez como carrilero. Emergencia: Alan Franco como lateral adaptado dentro del partido.

Gallardo en 2026: 2 victorias, 2 empates, 1 derrota, 5 goles a favor, 4 en contra. Noviembre: 2 victorias, 4 goles a favor, 0 en contra.

## Limites honestos

La muestra de Gallardo es pequena, solo 5 partidos. No tengo datos de eventos completos para todos los jugadores de Ecuador en una sola fuente gratuita. Las estadisticas de club no se trasladan una a una a la seleccion, y las temporadas de referencia no son identicas entre jugadores.

El ajuste tactico es una recomendacion basada en los datos disponibles, no una prediccion. Kendry Paez si estaba en la convocatoria, y la correccion queda registrada. Jordy Caicedo tiene 5 goles segun la pagina de plantilla y 6 segun su pagina individual, sin resolver. El club de Leonardo Campana tiene una contradiccion sin resolver. La convocatoria anunciada era de 29 jugadores, pero los nombres aportados suman 30, sin resolver. El PPDA no es comparable entre fuentes, con valores entre 8.05 y 9.3 para el Liverpool de Klopp. Los porcentajes de jugadas a balon parado no estan verificados para ningun modelo. El 4-2-3-1 de noviembre era proyectado, no confirmado, porque Global Sports Archive registro un 4-2-2-2 ante Costa Rica.

Cuaderno 07: los minutos de Preciado en Serie A difieren entre fuentes, 1,587 segun Ceroacero y unos 900 segun FotMob y SoFIFA. Las titularidades exactas de Preciado no estan verificadas. Los minutos de Daykol Romero no estan verificados. La puntuacion por criterio en el Top 3 es juicio analitico, no un dato medido.

## Verificacion

Los siete cuadernos se ejecutaron de principio a fin, sin errores, incluido el cuaderno 07, ejecutado el 18 de noviembre de 2026, con 0 errores. Los graficos se generaron en `charts/` y se copiaron a `docs/charts/`, ahora 14 en total. Se reviso que no apareciera el caracter de raya larga en ningun archivo de texto del proyecto, con grep, y el resultado fue cero.

## Archivos

- `README.md`
- `BUILD_REPORT.md`
- `data/jugadores_noviembre_2026.csv`
- `data/gallardo_partidos_2026.csv`
- `data/modelos_tacticos.csv`
- `data/PROVENANCE.md`
- `notebooks/01_plantilla_y_jugadores.ipynb`
- `notebooks/02_gallardo_primeros_cinco_partidos.ipynb`
- `notebooks/03_modelos_tacticos_mundiales.ipynb`
- `notebooks/04_ajuste_por_lineas.ipynb`
- `notebooks/05_sistema_recomendado.ipynb`
- `notebooks/06_plan_de_partido_y_alternativa.ipynb`
- `notebooks/07_lateral_derecho_preciado.ipynb`
- `data/laterales_derechos_2026.csv`
- `data/pool_ampliado_2026.csv`
- `charts/` con 14 graficos en PNG
- `docs/index.html`
- `docs/charts/` con copias de los 14 graficos
