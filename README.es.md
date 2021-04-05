# Portafolio Personal en React

![Portafolio Personal Roman](https://github.com/breatheco-de/exercise-personal-portfolio-react/blob/main/preview.gif)

Tener un portafolio o sitio web personal es una excelente herramienta para tu marca personal y tu carrera profesional. Sin embargo, tiene un significado especial para los desarrolladores de software, ya que nos permite compartir nuestro trabajo más valioso de una manera organizada.

## Objetivo

Un portafolio personal es como un curriculum vitae (CV) con esteroides; puedes hacerlo tan interactivo/cool/bello como quieras, pero no olvides su objetivo principal: Mostrarte a ti mismo, tus logros profesionales y tus proyectos más importantes.

> La calidad es más importante que la cantidad, sobre todo porque estás empezando una nueva carrera y no tienes muchos proyectos que mostrar.

### Pero no tienes ningún proyecto

Un portafolio es un sitio web en vivo; puedes cambiarlo en cualquier momento. Tienes que planificar el futuro. 

No te preocupes si no tienes proyectos; puedes empezar con uno y a partir de ahí irás creciendo. Todo el mundo ha empezado desde cero, en cuestión de meses, tendrás un par de proyectos.

### Estructura típica

La siguiente es la estructura típica de un portafolio, pero por supuesto puedes añadir otras secciones que te gusten:

- Una pequeña biografía sobre ti: Busca una forma breve -no aburrida- de hablar de ti mismo: ¿Qué te hace ser "tú"? ¿Alguna hobby o pasión? Intenta no escribir más de 250 caracteres en esta sección.

- Habilidades: El desarrollo de software es un conjunto de habilidades técnicas; debes especificar tus áreas de especialidad como React, Javascript, HTML/CSS, Bootstrap, Python, Flask, Bases de datos, etc. Es una buena idea especificar tu nivel de experiencia en cada una de ellas (como una barra de progreso o un número del uno al diez).

- Proyectos: Cada proyecto debe tener una foto, una pequeña descripción, un enlace al sitio web de trabajo en vivo y un enlace al perfil de GitHub.

- Sección de contacto: Las redes sociales, el correo electrónico, y también se puede incluir un pequeño formulario utilizando un servicio como Netlify, Foxyform, etc.

![Portafolio personal de Fernando Funez](https://github.com/breatheco-de/exercise-personal-portfolio-react/blob/main/fernando-funez.png?raw=true)

## ¿Por dónde empiezo?

### 👩🔬 Investigación

Empecemos por investigar un poco; ¿qué portafolio te gusta más? Aquí hay algunos ejemplos: 

| Enlace | Desarrollador | Por qué nos gusta
| ------------------------------- | --------------- | ------------------------------------------------------------------------------------- |
| https://www.fernandofunez.com/ | Fernando Funez | Muy sencillo y directo, muestra personalidad y es fácil de navegar. 

| https://www.my-resume.dev/ | Roman Khalnepesov | Causa una gran primera impresión sin tener efectos complicados | | https://www.my-resume.dev/
| https://mattfarley.ca/ | Matt Farley | Organizado y limpio, a los reclutadores les encantará |#.


### 🕵🏽♀️ Encuentra tu plantilla

Puedes buscar en internet plantillas HTML/CSS gratuitas, y puedes adaptarlas para que reaccionen muy fácilmente siempre que no contengan lo siguiente:

1. Evita los efectos complicados usando Javascript como **Parallax o animaciones**.
2. Asegúrate de que usen proceso o nada de Javascript; la parte de javascript será mucho más difícil de migrar a React; puedes incluir animaciones más adelante usando librerías de animación React.js como [React Spring](https://www.react-spring.io/docs/hooks/examples) o [Framer Motion later](https://www.framer.com/motion/).
3. Intenta elegir una plantilla que **se haya construido con Bootstrap**, eso acelerará mucho tu proceso.
4. Los scrollers de una página son siempre una gran idea para empezar.

Aquí tienes algunas webs con plantillas gratuitas para descargar, pero nada mejor que [una gran búsqueda en google al respecto](https://www.google.com/search?q=html+templates+portfolio+software+developer).

- [https://templated.co/](https://templated.co/).
- [https://rigorousthemes.com](https://rigorousthemes.com/blog/best-software-developer-portfolio-template-free-paid/).

💡 Nota: Si no encuentras nada que te guste puedes empezar con cualquiera de estas estupendas plantillas:

- [Freelancer by Start Bootstrap](https://startbootstrap.com/theme/freelancer).
- [Agencia por Start Bootstrap](https://startbootstrap.com/theme/agency)

O puedes encontrar [más plantillas de StartBootstrap aquí](https://startbootstrap.com/themes?showAngular=false&showVue=false&showPro=false).

## 🌱  Cómo iniciar este proyecto

No clones este repositorio.

El primer paso para comenzar a codificar es clonar el [react.js boilerplate](https://github.com/4GeeksAcademy/react-hello) en tu compjutador local o con Gitpod.

a) Si usas Gitpod puedes clonar el boilerplate [clic aquí](https://gitpod.io#https://github.com/4GeeksAcademy/react-hello).

b) Si trabajas localmente, escribe el siguiente comando en tu terminal: `git clone https://github.com/4GeeksAcademy/react-hello`.

💡 Importante: Recuerda actualizar el `remote` del proyecto con el de tu repositorio usando `git remote set-url origin <your new url>`, y luego guardar tu código en tu nuevo repositorio usando `add`, `commit` y `push`.

## 📝 Empieza a programar

1. Comienza ejecutando tu plantilla en HTML plano.
2. Elimina todo lo que no te guste de ella.
3. Visualiza cómo se verán tus proyectos, biografía e información dentro de ella, puede que tengas que cambiar algunas cosas, eso está bien.
4. Crea un nuevo proyecto vacío de React.js y empieza a migrar poco a poco, empieza por conectar la hoja de estilos y luego coge cada pieza de HTML una a una:
  4.1 El Navbar
  4.2 El Footer
  4.3 El Jumbroton
5. Asegúrate de que la hoja de estilos CSS está bien conectada y funciona.
6. Asegúrate de renombrar todas las propiedades `class=` a `className=`, cierra todas las etiquetas `<img />` y reemplaza también los otros atributos HTML que no te gusten a react como `hmltFor` o cualquier otro que veas en inspector de la consola como un error, ten mucha paciencia para esto, es posible si lo haces poco a poco.

## ¿Te sientes frustrado?

¡Pide ayuda! Esta es tu primer portafolio y no será perfecto, pero te empujará en la dirección correcta :)


