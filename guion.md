# Guión del laboratorio denominado "Propiedades emergentes de los ecosistemas o el todo es más que la suma de sus partes"


> + **_Versión_**: 2023-2024
> + **_Titulación_**: Programa "jóvenes con investigadores"
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **_Duración_**:  3 horas de campo (11 de enero), 4 horas de gabinete (15 febrero) y 3 horas de trabajo en remoto (21 de marzo)
> + ***Conexión a la wifi de la UCO*** 
>   + usuario: VisitasUCO
>   + contraseña: 2024Centros



## Objetivos 

En este "laboratorio" tratamos de abordar los siguientes objetivos, agrupados en dos tipos. 

+ Disciplinares: Están relacionados con competencias propias de la ecología.
  + Entender (más o menos) la idea de "sistema complejo"
  + Empezar a entender el concepto de "propiedad emergente"
  + Analizar cómo una propiedad emergente puede ser útil para evaluar el funcionamiento de un ecosistema.
+ Instrumentales: Están relacionados con la adquisición de competencias en el manejo de herramientas potencialmente útiles en ecología y en otros ámbitos.
  + Conocer la teledetección como disciplina.
  + Aprender cómo gracias a la teledetección podemos medir algunas propiedades emergentes de los sistemas complejos.



## Introducción: Desde Rajoy a cómo respira un bosque

+ Corría el año 2012 y el por aquel entonces presidente del gobierno, M. Rajoy, asistía a una reunión de alto nivel con varios líderes europeos. En un momento de la reunión, los micrófonos captaron cómo nuestro presi decía: "*it is very difficult todo esto*". Rajoy reaccionó ante un problema complejo como hacemos habitualmente: quejándonos de que la vida es compleja. 



![Rajoy](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/raw/main/imagenes/rajoy.jpg)



+ El Sr. Rajoy tenía razón. Todo es muy difícil. Muy complejo, para ser más precisos. El mundo es complejo. Todo lo que vemos es el resultado de miles, millones de interacciones de átomos, moléculas y otras entidades que ocurren en cada lapso de tiempo y en cada "trozo" del espacio. Estamos rodeados de "sistemas complejos". 

+ Hay muchos sistemas complejos a nuestro alrededor. Un puente es un buen ejemplo de un sistema complejo. Para que dure mucho tiempo y cumpla su función es necesario saber muchas cosas. Debemos de conocer las leyes físicas que gobiernan la distribución de masas, las tensiones, la resistencia de los materiales, etc. No es fácil mantener y conservar un puente.

![puente](https://raw.githubusercontent.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/main/imagenes/puente_de_alcantara.jpg)

+ Los ecosistemas son también sistemas complejos. Un bosque, por ejemplo, es una agrupación de seres vivos que hacen cosas de seres vivos: comen, se reproducen, compiten, cooperan, etc. ¿sabemos construir ecosistemas?, ¿y mantenerlos?

![bosque](https://raw.githubusercontent.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/main/imagenes/bosque.jpg)

+ La diferencia fundamental entre un puente y un ecosistema (desde el punto de vista de los sistemas complejos) es que las propiedades del puente resultan de la agrupación de las propiedades de los elementos que lo conforman. Es decir, un bloque de hormigón pequeño tiene propiedades parecidas a las de un puente. Esto no pasa con los bosques (ni con los ecosistemas en general). Las propiedades de los ecosistemas van más allá de las propiedades de los elementos que lo constituyen. Es decir, el bosque es más que la suma de sus partes. Estas características que surgen cuando muchos seres vivos se asocian en un ecosistema, son las denominadas "propiedades emergentes" de un sistema complejo. Data nos lo explica muy bien en [este](https://www.youtube.com/watch?v=LSXffX8weME) vídeo con otro ejemplo.


+ Veamos ahora este vídeo.

<iframe width="560" height="415" src="https://www.youtube.com/embed/jlO8NiPbgrk?start=48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

  + ¿Reconocéis lo que se describe en él?
  + En efecto, vemos una animación en 4D de la fotosíntesis. Estamos observando cómo trillones de fotones estimulan las moléculas de los fotosistemas y provocan la fotolisis del agua, la liberación de oxígeno y la producción de moléculas de azúcar. 

+ ¿Qué pasa si observamos millones de hojas haciendo la fotosíntesis? ¿y si además observamos cómo los animales se las comen y luego se comen entre ellos?. En definitiva, ¿qué propiedad o propiedades emergentes surgen cuando vemos la fotosíntesis de un ecosistema en su conjunto? En el vídeo mostrado a continuación se observa este proceso a escala planetaria.


<iframe width="560" height="415" src="https://www.youtube.com/embed/8uDYfpw1gg0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


+ En este rato trataremos de responder (parcialmente) alguna de estas preguntas. Estudiaremos los ecosistemas desde arriba, viéndolos en su conjunto sin preocuparnos de cómo los fotones estimulan las moléculas de clorofila. Para ello usaremos una serie de técnicas englobadas en una disciplina llamada "teledetección". 

+ Como su nombre indica, la teledetección nos permite ver cosas desde lejos. Nuestros ojos son aparatos muy eficaces de teledetección. Pero en este caso usaremos satélites. 

+ Para entender esto tienes que evocar el conocimiento que ya tienes sobre el espectro electromagnético. La siguiente figura resume un poco las ideas principales.

![espectro](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/raw/main/imagenes/espectro.png)




+ Los satélites tienen cámaras parecidas a las de nuestros móviles. Al menos conceptualmente. Se caracterizan porque son capaces de "excitarse" (en el sentido fotónico de la palabra) cuando llegan a ellas ondas electromagnéticas con una longitud de onda concreta. A nuestros ojos les pasa algo parecido. Vemos ciertas longitudes de ondas y somos ciegos ante otras. No vemos en el infrarrojo ni en el ultravioleta, por ejemplo. La siguiente imagen resume esta idea.



![solete](https://raw.githubusercontent.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/main/imagenes/sol.png)




+ Pues bien, resulta que hay satélites que son capaces de "ver" la fotosíntesis. Una planta que hace la fotosíntesis refleja poca radiación roja porque la utiliza para romper moléculas de agua y producir glucosa. Una planta muerta refleja menos radiación de infrarrojos que una viva. Así que, si tenemos en un satélite sensores que pueden ver la radiación roja e infrarroja que refleja la superficie, podemos cuantificar cuánta fotosíntesis está ocurriendo en un lugar determinado. Para cuantificar esto construimos índices de vegetación. El más utilizado se denomina NDVI (Normalized Difference Vegetation Index).

![NDVI](https://raw.githubusercontent.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/main/imagenes/ndvi.png)


+ Todo este rollo sirve para que entendáis cómo las imágenes de satélite nos ayudan a visualizar una propiedad emergente de los ecosistemas: la producción primaria. Se define como la cantidad de biomasa que pueden generar los organismos autótrofos de un ecosistema en un momento dado. Cuando tomamos imágenes de satélite estamos viendo en realidad el resultado de la interacción de trillones de fotones con los cloroplastos de millones de plantas. 

En [este](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_hipatia_UCO/raw/main/presentacion/prop_emergentes.pptx) enlace está disponible la presentación que usamos como guía de la charla. 

## Qué vamos a hacer

Para entender bien qué es un sistema complejo y cómo podemos medir las propiedades emergentes de uno de estos sistemas, trabajaremos estableciendo un paralelismo (una especie de metáfora) entre los sistemas ecológicos y el cuerpo humano. Ambas entidades son sistemas complejos. Una propiedad emergente de ambos es el concepto de "salud". Para medir la salud de una persona usamos una serie de indicadores, como por ejemplo, la fiebre o el nivel de oxígeno en sangre. Estas medidas sencillas nos dan idea de cómo funciona el sistema en su conjunto. Si queremos conocer el estado de salud de un bosque también podemos usar indicadores útiles. En nuestro caso usaremos indicadores a partir de mediciones en campo y por satélite de una serie de variables relacionadas con la capacidad de un bosque de hacer la fotosíntesis. 

Para ello, procedemos de la siguiente forma.

El primer día (11 de enero) salimos al campo y dimos un paseo por los alrededores del campus. Vimos *insitu* distintas especies y formaciones vegetales. Tomamos datos de alguna de sus características con objeto de comparar nuestras impresiones con lo que veremos con la información de satélite. A continuación se describen las paradas que realizamos:

+ Olivar intensivo. Se trata de cultivo de olivar en "espaldera". Esto quiere decir que los árboles están plantados muy juntos, están en regadío y hay un trabajo agrícola muy intenso para reducir la herbivoría. Es decir, se consumen muchos productos fitosanitarios (abonos y pesticidas). [Aquí](https://www.google.com/maps/place/37%C2%B055'12.8%22N+4%C2%B043'28.0%22W/@37.920212,-4.724432,1373m/data=!3m1!1e3!4m4!3m3!8m2!3d37.920212!4d-4.724432?entry=ttu) se puede ver la ubicación de esta zona. Concluimos que el estado de conservación de esta zona es mala.
+ Bosque de ribera. En este bosque de ribera junto al arroyo de Rabanales observamos varias especies de árboles y arbustos. También vemos el impacto provodado por la sequía y por las especies invasoras. [Aquí](https://www.google.com/maps/place/37%C2%B055'33.0%22N+4%C2%B043'42.4%22W/@37.925838,-4.728445,1373m/data=!3m1!1e3!4m4!3m3!8m2!3d37.925838!4d-4.728445?entry=ttu) está la ubicación de esta zona. Concluimos que el estado de conservación es regular-mala. 
+ Dehesa. Paseamos por los alrededores de una dehesa en la que solo había encinas y algunos herbívoros introducidos por el ser humano. El ecosistema era algo más complejo que el del olivar. [Aquí](https://www.google.com/maps/@37.9346712,-4.7250946,1392m/data=!3m1!1e3?entry=ttu) tenemos su ubicación. 
+ Encinar. Aunque no llegamos a ver un encinar de cerca, sí que se intuía hacia la sierra. En el mapa anterior de la dehesa podréis ver un bosque más al norte. En este ecosistema no solo hay encinas, sino matorrales, hierbas y muchas más especies de animales que en los demás ecosistemas que hemos estudiado. 

Ahora, después de estudiar la estructura y funcionamiento de los ecosistemas *in situ*, veremos qué podemos aprender de ellos mediante el satélite. Para ello haremos analizaremos el funcionamiento de la producción primaria (fotosíntesis) a dos escalas temporales diferentes. En primer lugar veremos cómo ha cambiado la producción primaria máxima anual para cada ecosistema desde 1980 hasta la actualidad. Además, analizaremos cómo cambia la producción primaria dentro de un año. Es decir, estudiaremos el patrón de cambio de la producción primaria a escala intraanual. Todo eso lo haremos con una aplicación informática online que permite analizar el comportamiento de la vegetación en cualquier parte del planeta:

+ [Este](https://jstnbraaten.users.earthengine.app/view/landsat-timeseries-explorer#run=false;lon=-122.91966;lat=44.24135;from=06-10;to=09-20;index=NBR;rgb=SWIR1%2FNIR%2FGREEN;chipwidth=2;) enlace nos lleva a la aplicación que usaremos para caracterizar la serie interanual.
+ Y [este](https://jstnbraaten.users.earthengine.app/view/eo-timeseries-explorer#run=false;sensor=Sentinel-2%20SR;lon=-121.68804;lat=36.46517;index=NBR;rgb=SWIR1%2FNIR%2FGREEN;duration=12;cloud=30;chipwidth=2;) otro nos lleva a la aplicación que nos dará información a escala intraanual. 

Antes de trabajar con estas aplicaciones tendremos que cambiar los siguientes parámetros de la pestaña "options":

- Para la escala interanual hay que poner:
  - Y-axis index (bands are LC08): **NDVI**
- Para la escala intraanual hay que poner:
  - Sensor selection: **Sentinel**
  - Y-axis index: **NDVI**

Con todo lo anterior, tendréis que hacer lo siguiente:

+ Visitar los lugares que se describen más arriba con google maps.
+ Hacer click en cada uno de ellos con cada una de las herramientas anteriores.
+ Copiar las gráficas que se generan abajo a la izquierda y pegarlas en un powerpoint indicando a qué punto se refieren.
+ Cuando hagáis esto, comentaremos los resultados en clase y aprenderemos a interpretar las gráficas anteriores.
+ En casa, y para preparar el póster, tendréis que añadir cinco puntos más con características diferentes. Podéis buscar zonas conocidas por vosotros o lugares remotos. Lo importante es que sepáis qué tipo de vegetación hay en cada zona y que podáis interpretar su funcionamiento a partir de las imágenes de satélite. 

