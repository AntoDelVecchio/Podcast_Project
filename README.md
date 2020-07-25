# Podcast_Project
Proyecto del final de 1er bloque del curso de DWFE en Acamica. Landing UI de un podcast en version mobile, tablet y desktop.

La idea principal del proyecto es imitar la landing propuesta de manera obligatoria en modo mobile y desktop; y de manera opcional tablet. 
El proyecto se encuentra terminado, esta construido sobre HTML y CSS. Para este último se uso el preprocesador SASS, para lograr un código que sea fácil de leer y que no sea repetitivo, garcias al uso de mixins.

Para lograr un diseño responsive de la web decidí utilizar unidades de medidas relativas, el proyecto en su gran mayoría está medido en REM y en algunos casos use VW/VH. Dado que mi objetivo fue que el proyecto fuera lo mas parecido posible al propuesto y en el kit las medidas eran en PX, algunas medidas no estan en numeros enteros pero si redondeadas.

Las variables del proyecto como colores, fuentes y demas las agrupe para lograr un resultado mas organizado en el proyecto. En cuanto a los media queries y otros estilos que se repetian, los agrupe en un archivo llamado utilities.scss, porque considere una buena forma de no repetir valores ni codigo y que sea a la vez fácil de leer. En ese hoja van a encontrar mixins (utilizados para media queries), extends para reutilizar estilos, entre otros.
