# Bikesantiago

**Challenge Hackathon:** La app de [Bikesantiago](https://play.google.com/store/apps/details?id=com.bikesantiagoapp) tiene solo 2.0 estrellas en la Play Store. Como equipo debemos entender por qué tiene tan bajo rating y cómo podemos hacer para mejorar la experiencia de los usuarios y el rating de la app.
Hackathon del final del Bootcamp de Laboratoria a modo de preparación para el Talenfest; nuestro equipo de trabajo estuvo conformado por 3 Front-end (Tanko Azócar, Paulina Baeza y Andrea Diaz) y 1 UX (Pabla Bazán) y el tiempo para realizar el producto minimo viable fueron 2 días.

![zooapp-img-1](https://user-images.githubusercontent.com/32286870/37943810-8d9bb4c6-314f-11e8-9e2a-2a2b423de10d.png)

## Desarrollado para 
[Laboratoria y Bikesantiago](https://marvelapp.com/c8f7hgj/screen/40092310)

## ¿Qué es Bikesantiago? |
Bikesantiago es un Sistema Intercomunal de Bicicletas Públicas de Santiago de Chile. Con el respaldo de banco Itaú y la más moderna tecnología mundial, entrega un servicio 100% automatizado, complementario al transporte público. Es una alternativa eficiente, económica y segura que mejora la calidad de vida de miles de personas y contribuye decididamente al desarrollo sostenible.

***

## Descubrimiento e Investigación |

![bike-2](https://user-images.githubusercontent.com/32286870/37944210-235094e0-3151-11e8-915f-83edf7909cba.jpg)

## Research
**Bikesantiago** ofrece a los usuarios que bajan la app 5 funciones principales:
- Notificaciones instantaneas a tú teléfono a la hora en que sacas y devuelves la bicicleta.
- Listado de estaciones favoritas.
- Ve la cantidad de bicicletas disponibles.
- Asocia tu tarjeta y podrás ver tus viajes de los últimos 30 días.
- Asistencia online a través del centro de ayuda de la app. 

Teniendo en cuenta estas 5 funciones primordiales, entrevistamos a usuarios que hayan ocupado u ocupen el sistama de Santiago Bike y buscamos en la web sobre temas relevantes al problema que estamos enfrentando. Con el objetivo de averiguar si los puntos que la empresa ofrece a sus usuarios se cumplian y a la vez conocer los puntos de conflicto (paint points) de los usuarios al ocupar la aplicación.

![bike-3](https://user-images.githubusercontent.com/32286870/37944868-c8ffa758-3153-11e8-90bf-fa1a7f50c091.jpg)

![bike-4](https://user-images.githubusercontent.com/32286870/37945275-c509d220-3155-11e8-84de-0317260f6701.jpg)

## Problematicas al ocupar la aplicación:
- "Las bicicletas que muestra la app no siempre estan en buen estado".
- "Las bicicletas estan todas malas. De 5 bicicletas, 1 buena y 4 malas".
- "En el mapa se mostraban 10 bicicletas, pero al llegar no había ninguna. El inventario no estaba actualizado".
- "En el mapa no están todas las estaciones existentes".
- "La aplicación muestra con una foto referencial el lugar en que esta la estación, pero esta foto no coincide e incluso 10 estaciones de distintos lugares tienen la misma fotografía".
- "Nunca funciono para lo que yo quería la aplicación: por ejemplo dónde estaban las bicicletas, dónde habían bicicletas, y dónde habían puestos disponibles para colocar las bicicletas".
- "Problemas con infrestructura de las bicicletas: no tenían frenos, los asientos estaban malos, no podía bajarse el asiento, las luces no funcionaban o no tenian y casi ninguna tenía timbre".
- "A veces las bicicletas quedaban abiertas, si no suena, no cierra y es como si siguieras andando y por lo cual te cobran extra y uno como usuario nunca se entera".
- "La tarjeta para liberar las bicicletas no siempre funciona".
- "Te cobra demás cuando pasa el tiempo, sin embargo la aplicación no te avisa nada".

***

## Sintesis y definición |

## Creando personas, usuario primario
- Estudiantes Universitarios.
- Trabajadores adultos/jovenes.

Nuestro usuario primario ocupa el sistema **Bikesantiago** por que no cuentan con una bicicleta propia para movilizarse, lo ven como una alternativa para evitar el trafico en hora punta y a la vez ahorrar dinero. También les ayuda a tener una vida más saludable y encuentran que es una forma para contribuir con el medio ambiente, ya que al andar en bicicleta reducen la contaminación.

## Problem Statement
Luego de analizar todo la información obtenida, nos dimos cuenta que **de las 5 funciones que ofrece la app, 2 de ellas no estan cumpliendo su objetivo** en ningún aspecto, lo que conlleva a una mala experiencia del usuario al ocupar la aplicación. Las funciones que no cumplen con el objetivo son las siguientes:
- Ver la cantidad de bicicletas disponibles, ya que a pesar de que muestran la cantidad de bicicletas y espacios disponibles, esta información no esta actualizada o hay muchas bicicletas en mal estado, por lo cual no se pueden ocupar; provocando en el usuario una perdida de tiempo en la busqueda de una bicicleta.
- Notificaciones instantaneas al teléfono a la hora en que sacas y devuelves la bicicleta, lo que provoca un cobro extra y desconocido por los usuarios.

***

## Ideación |
Usando nuestras nuevas personas, creamos un escenario para que cada uno comience a idear cómo podemos resolver cada una de sus necesidades. La sesión de ideación proporcionó muchas ideas geniales.

## What if… 
- Que pasaría si existiese un **servicio de reporte** que informe entre usuarios si hay bicicletas en mal estado en las estaciones para evitar el ir de una estación a otra. 
- Que pasaría si existiese un **cronometro** (de 1 hora o 30 minutos, según el plan) que avise a los usuarios que les queda poco tiempo para evitar de esta manera los cobros extras.
- Que pasaría si en vez de tarjerta, el desbloqueo funcionará por medio de un **codigo QR**, para evitar las tarjetas bloqueadas y reportar desperfectos de manera más rápida.
- Que pasaría si uno pudiese **reservar** una bicicleta por 15 minutos para que los usuarios se aseguren que este la bicicleta cuando lleguen a la estación.
- Que pasaría si la app pudiese **mostrar las ciclovias en el mapa** para que los usuarios pudiesen planificar sus rutas de viajes.

## Crear el MVP 
Limitamos nuestras ideas a las características que pondríamos en la aplicación y priorizamos lo que sería nuestro Producto Minimo Viable. Es por ello que, como equipo decidimos que en una primera instancia nos enfocaremos en dar un servicio de reporte de bicicletas en mal estado y diseñaremos un cronometo que ayude y alerte a los usuarios cuando les quede poco tiempo; ya que estos son los puntos más criticos, tanto a nivel de aplicación como cuando se utiliza el servicio Bikesantiago.

***

## Prototipado
Se realizó un prototipado rápido digital, a través de marvelapp. Se utilizó user flow para determinar el flujo de navegación para realizar diferentes tareas dentro de la aplicación, de esta manera mis compañeras de front-end al momento de codificar el prototipo de alta fidelidad a traves del programa react, tendrían claro conceptos del maqueteado tales como: paleta de colores, iconos a utilizar, textos y diagramación dentro de la plataforma, ahorrando de esta manera tiempo.

### Actividades a realizar
- Ver cantidad de bicicletas y espacios disponibles.
- Reportar problema con bicicleta.
- Reserva de bicicleta.
- Ver perfil de usuario.

![bike-5](https://user-images.githubusercontent.com/32286870/38200013-1ea1094e-3669-11e8-8f76-d7798f344f6d.jpg)
