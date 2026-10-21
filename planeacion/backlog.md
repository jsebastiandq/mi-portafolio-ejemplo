# Backlog de mi-portafolio

Este archivo es el **plan** del proyecto. Cada historia de usuario (HU) de aquí
se convierte en un **issue** en GitHub, se pone en el **tablero** de GitHub
Projects y se cierra con un **commit** que diga `closes #número`.

Formato de cada criterio de aceptación:

> `- [ ] Dado <contexto>, cuando <acción>, entonces <resultado esperado>.`

Cuando crees el issue en GitHub, escribe su número en la línea **Issue:**
(por ejemplo `**Issue:** #4`).

---

## HU-01 · Menú de navegación fijo  ✅ (ejemplo resuelto)

**Historia:** Como visitante del portafolio, quiero un menú fijo en la parte superior, para ir a cualquier sección sin hacer scroll.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio, cuando miro la parte superior, entonces veo un menú con enlaces a "Sobre mí", "Proyectos" y "Contacto".
- [ ] Dado que estoy en la parte de arriba, cuando hago clic en "Proyectos", entonces la página baja hasta la sección de proyectos.
- [ ] Dado que hice scroll hasta el final, cuando miro la parte superior de la pantalla, entonces el menú sigue visible.

**Issue:** #1

---

## HU-02 · Sección de habilidades  ✅ (ejemplo resuelto)

**Historia:** Como reclutador, quiero ver las habilidades técnicas del aprendiz en una lista, para evaluar rápidamente si su perfil encaja con la vacante.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio, cuando llego a la sección "Habilidades", entonces veo al menos 6 habilidades técnicas.
- [ ] Dado que estoy en la sección "Habilidades", cuando la leo, entonces las habilidades están agrupadas en "Frontend" y "Herramientas".
- [ ] Dado que estoy en el menú, cuando hago clic en "Habilidades", entonces la página baja hasta esa sección.

**Issue:** #2

---

## HU-03 · Pie de página con redes

**Historia:** Como visitante, quiero un pie de página con el año y los enlaces a las redes del aprendiz, para contactarlo desde cualquier parte de la página.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que estoy en cualquier sección, cuando bajo hasta el final de la página, entonces veo un pie de página con el texto "© 2026" y mi nombre.
- [ ] Dado que estoy en el pie de página, cuando hago clic en el enlace de GitHub, entonces se abre mi perfil de GitHub en una pestaña nueva.
- [ ] Dado que estoy en el pie de página, cuando hago clic en el enlace de LinkedIn, entonces se abre mi perfil de LinkedIn en una pestaña nueva.

**Issue:** #3

---

## HU-04 · Enlace al repositorio en cada proyecto

**Historia:** Como reclutador, quiero que cada tarjeta de proyecto tenga un enlace a su repositorio en GitHub, para revisar el código que escribió el aprendiz.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que estoy en la sección Proyectos, cuando miro cada tarjeta, entonces veo un enlace con el texto "Ver código".
- [ ] Dado que estoy en una tarjeta, cuando hago clic en "Ver código", entonces se abre el repositorio de ese proyecto en GitHub en una pestaña nueva.
- [ ] Dado que abrí el repositorio en otra pestaña, cuando regreso a la pestaña del portafolio, entonces sigo en el mismo lugar de la página.

**Issue:** #4

---

## HU-05 · Portafolio adaptable al celular

**Historia:** Como visitante que usa el celular, quiero que el portafolio se vea bien en pantallas pequeñas, para leerlo sin hacer zoom ni scroll horizontal.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** M

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio en una pantalla de menos de 600 px, cuando llego a Proyectos, entonces las tarjetas se muestran una debajo de la otra.
- [ ] Dado que estoy en el celular, cuando recorro toda la página, entonces no aparece scroll horizontal.
- [ ] Dado que estoy en el celular, cuando miro el menú, entonces todos sus enlaces se ven completos y se pueden tocar con el dedo.

**Issue:** #5

---

## HU-06 · Botón "volver arriba"

**Historia:** Como visitante que llegó al final de la página, quiero un botón para volver arriba, para no tener que hacer scroll largo hasta el menú.

**Etiquetas:** historia, frontend, prioridad-baja · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que estoy en cualquier parte de la página, cuando miro la esquina inferior derecha, entonces veo un botón con una flecha hacia arriba.
- [ ] Dado que estoy al final de la página, cuando hago clic en el botón, entonces la página sube hasta el encabezado.
- [ ] Dado que estoy en el celular, cuando aparece el botón, entonces no tapa el texto del pie de página.

**Issue:** #6
