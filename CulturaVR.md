# Auditoría cruzada — Aplicación CulturaVR

## 1. Datos de la auditoría

| Campo | Información |
|---|---|
| Equipo auditor | TeroByte |
| Equipo auditado | DharmaUY / CulturaVR |
| Sistema | CulturavR |
| Fecha | 2026-10-14 |
| Ambiente autorizado | https://culturavr.dharma-uy.com |
| Navegador y dispositivo | Opera GX, Laptop |
| Alcance | Usabilidad, diseño visual, navegación, accesibilidad visual, flujos de usuario y funcionalidades de la aplicación web y móvil, incluida la experiencia de realidad virtual. |

## 2. Resumen ejecutivo

**Objetivo:** identificar dificultades de usabilidad, inconsistencias visuales, problemas de navegación y comportamientos de la aplicación que puedan afectar la comprensión y la experiencia de los usuarios.

**Resultado general:** durante la revisión se identificaron observaciones relacionadas con la legibilidad y consistencia visual, la navegación entre páginas, la claridad de las instrucciones, las transiciones y los mensajes de confirmación. 

## 3. Funcionalidades revisadas

- Diseño visual y consistencia de la interfaz.
- Tipografía, tamaños de texto y legibilidad.
- Navegación entre páginas y continuidad de los flujos.
- Imágenes, carruseles y elementos visuales.
- Formularios.
- Inicio de sesión y recuperación de contraseña.
- Mensajes de confirmación.
- Carga de beneficios y visualización del ranking.
- Configuraciones de privacidad.
- Experiencia de realidad virtual y modo avanzado.

## 4. Hallazgos

### H-01 — Inconsistencias visuales y tipográficas

- **Categoría:** Diseño visual / usabilidad.
- **Severidad:** Alta.
- **Descripción:** se observan diferencias en los tamaños y las tipografías de los textos a lo largo de la aplicación. También el logo cambia de tamaño, fuentes o apariencia según la pantalla.
- **Observaciones relacionadas:**
  - El texto se pierde visualmente cuando se presenta junto a una imagen.
  - Algunas tipografías resultan difíciles de leer.
  - Hay textos demasiado pequeños, casi imperceptibles.
  - Se identifican diferencias tipográficas en la sección de Datos personales.
  - El logo presenta variaciones entre pantallas.
- **Resultado esperado:** mantener una jerarquía tipográfica coherente y una presentación consistente del logo y de los textos.
- **Resultado obtenido:** se observan diferencias tipográficas, variaciones del logo y problemas de legibilidad.
- **Recomendación:** unificar las tipografías, los tamaños de texto y las características visuales del logo en toda la aplicación.

### H-02 — Navegación confusa y falta de continuidad entre páginas

- **Categoría:** Navegación / usabilidad.
- **Severidad:** Alta.
- **Descripción:** la navegación no permite seguir un flujo claro. Al ingresar a determinadas páginas, el usuario pierde la referencia de dónde se encuentra dentro de la aplicación.
- **Observaciones relacionadas:**
  - Los enlaces no funcionan o los menús no corresponden con la opción esperada.
  - Algunos menús conducen a otra página y generan desorientación.
  - La sección que muestra un lugar parece una página independiente, sin continuidad con el resto.
  - No se identifica claramente la ubicación del usuario dentro de la navegación.
  - Se señala la necesidad de una transición más fluida entre las páginas del pasaporte.
- **Resultado esperado:** permitir que el usuario comprenda dónde se encuentra y cómo continuar o regresar dentro del flujo.
- **Resultado obtenido:** se reportan dificultades para seguir la navegación y pérdida de orientación al cambiar de página.
- **Recomendación:** revisar los enlaces y menús, mejorar la continuidad entre páginas e incorporar elementos de orientación, como un breadcrumb.

### H-03 — Animaciones y transiciones que dificultan la experiencia

- **Categoría:** Interfaz / experiencia de usuario.
- **Severidad:** Media.
- **Descripción:** determinadas transiciones y movimientos visuales generan desorientación. Se indica que algunas imágenes permanecen en movimiento o presentan demasiadas transiciones.
- **Observaciones relacionadas:**
  - La imagen se mantiene en movimiento y genera mareo.
  - Hay demasiadas transiciones y cambios visuales.
  - Al cargar un beneficio, la aplicación parece dejar de funcionar y luego vuelve a responder.
  - La pantalla de carga de la ventana Ranking no coincide con la del resto de la web porque falta la mascota.
- **Resultado esperado:** ofrecer transiciones fluidas y consistentes que permitan identificar cuándo una operación está cargando y cuándo ha finalizado.
- **Resultado obtenido:** se reportan movimientos que generan mareo visual, transiciones excesivas e inconsistencias visuales durante las cargas.
- **Recomendación:** reducir los movimientos innecesarios, mantener la continuidad visual durante las cargas y utilizar indicadores de carga consistentes.

### H-04 — Imágenes y elementos visuales poco claros

- **Categoría:** Diseño visual / usabilidad.
- **Severidad:** Alta.
- **Descripción:** se observan dificultades relacionadas con el tamaño, la presentación y la interacción con imágenes y otros elementos visuales.
- **Observaciones relacionadas:**
  - El ícono utilizada en la pantalla de privacidad de CulturaVR presenta un dimensionamiento inadecuado.
  - Aparece un círculo en el centro de una página que no parece corresponder con el contenido.
  - Falta un carrusel que permita cambiar las imágenes y no hay indicaciones claras de que la imagen esté cambiando.
  - Las imágenes podrían ampliarse para visualizarse mejor, incluso en pantalla completa.
  - Al utilizar las lentes y pararse en una esquina, la imagen se rompe.
- **Resultado esperado:** mostrar imágenes correctamente dimensionadas, permitir su visualización adecuada y proporcionar controles comprensibles para interactuar con ellas.
- **Resultado obtenido:** se reportan problemas de dimensionamiento, elementos visuales que no corresponden, falta de controles de navegación de imágenes y una imagen que se rompe en una situación concreta.
- **Recomendación:** revisar el dimensionamiento y la presentación de las imágenes, incorporar controles visibles para el carrusel cuando corresponda y revisar el comportamiento visual señalado al utilizar las lentes.

### H-05 — Instrucciones y pasos poco claros

- **Categoría:** Usabilidad / comprensión de los flujos.
- **Severidad:** Media
- **Descripción:** en la bitácora algunas instrucciones no explican suficientemente las acciones que debe realizar el usuario ni el propósito de determinados elementos.
- **Observaciones relacionadas:**
  - Los pasos son poco claros y podrían enumerarse.
  - No se comprende por qué se coloca el sello.
  - Los pasos quedan tapados y no se entiende el flujo realizado.
  - Las instrucciones del juego, en la parte del alfajor, explican los pasos básicos, pero no aclaran cómo realizar los gestos.
  - No queda claro qué representa el modo avanzado dentro de la experiencia de realidad virtual.
- **Resultado esperado:** proporcionar instrucciones ordenadas, visibles y comprensibles, que expliquen tanto las acciones como los gestos necesarios.
- **Resultado obtenido:** se reportan dudas sobre el propósito de determinados pasos, la realización de gestos y el significado del modo avanzado.
- **Recomendación:** enumerar los pasos, evitar que las instrucciones queden tapadas y explicar claramente los gestos y el propósito de las acciones.

### H-06 — Falta de confirmación después de realizar acciones

- **Categoría:** Usabilidad / retroalimentación del sistema.
- **Severidad:** Alta.
- **Descripción:** no siempre queda claro si una acción realizada por el usuario se completó correctamente.
- **Observaciones relacionadas:**
  - Al guardar un comentario, no se muestra un mensaje que confirme el guardado.
  - Se plantea la duda de si el usuario está avanzando o no durante una experiencia.
  - Al cargar un beneficio, el comportamiento visual puede hacer pensar que la aplicación dejó de funcionar.
- **Resultado esperado:** informar claramente el estado de las operaciones y permitir que el usuario identifique si una acción se completó o si debe continuar.
- **Resultado obtenido:** se reporta ausencia de confirmación al guardar comentarios y falta de claridad sobre el progreso de determinadas acciones.
- **Recomendación:** incorporar mensajes de confirmación y estados de progreso comprensibles, además de indicadores de carga coherentes.

### H-07 — Dificultades en funcionalidades de perfil y visitas

- **Categoría:** Funcionalidad.
- **Severidad:** Alta.
- **Descripción:** se reportan comportamientos que afectan la visualización o el uso de funcionalidades relacionadas con el perfil y las visitas.
- **Observaciones relacionadas:**
  - El ranking no se refleja en el perfil.
  - No se permite subir fotografías de las visitas.
- **Resultado esperado:** reflejar el ranking correspondiente en el perfil y permitir la carga de fotografías de las visitas.
- **Resultado obtenido:** se indica que el ranking no se refleja en el perfil y que no se pueden subir fotografías de las visitas.
- **Recomendación:** revisar la actualización del ranking en el perfil y el funcionamiento de la carga de fotografías.

### H-08 — Limitaciones y falta de claridad en la versión móvil

- **Categoría:** Funcionalidad / experiencia multidispositivo.
- **Severidad:** Media.
- **Descripción:** se reportan dudas sobre las funcionalidades disponibles desde el celular y una dificultad concreta al preparar un canje.
- **Observaciones relacionadas:**
  - No queda claro qué acciones se pueden realizar desde el celular y cuáles no.
  - Desde la versión móvil no se permite preparar un canje.
  - Se indica que el canje ya había sido realizado para ese usuario.
- **Resultado esperado:** permitir identificar las funcionalidades disponibles en cada dispositivo y ofrecer un comportamiento coherente al preparar canjes.
- **Resultado obtenido:** se reporta que no se puede preparar un canje desde la versión móvil y se señala que ya se había realizado el canje para ese usuario.
- **Recomendación:** revisar el flujo de preparación de canjes desde el celular y aclarar qué funcionalidades están disponibles en cada versión. Verificar el caso del canje previamente realizado.

### H-09 — Mensajes de error en inicio de sesión y recuperación de contraseña

- **Categoría:** Usabilidad / formularios.
- **Severidad:** Alta
- **Descripción:** se señala que los mensajes de error durante el inicio de sesión pueden pasar desapercibidos para el usuario. También se mencionan los mensajes predeterminados cuando se dejan vacíos el correo o la contraseña, tanto en el inicio de sesión como en la recuperación de contraseña.
- **Observaciones relacionadas:**
  - El mensaje de error del login podría perderse visualmente.
  - Los mensajes predeterminados para los campos vacíos requieren revisión.
  - Se indica que el campo de contraseña permite introducir más de 32 caracteres.
- **Resultado esperado:** presentar mensajes de validación visibles y comprensibles, y aplicar las restricciones correspondientes al campo de contraseña.
- **Resultado obtenido:** se reportan dificultades de visibilidad de los errores, mensajes predeterminados que requieren revisión y aceptación de contraseñas de más de 32 caracteres.
- **Recomendación:** revisar la visibilidad y claridad de los mensajes de error, las validaciones de campos vacíos y el comportamiento del campo de contraseña.

### H-10 — Las configuraciones de privacidad no se conservan

- **Categoría:** Funcionalidad / privacidad.
- **Severidad:** Media.
- **Descripción:** se indica que las configuraciones de privacidad elegidas por el usuario no se guardan.
- **Resultado esperado:** conservar las opciones de privacidad seleccionadas por el usuario.
- **Resultado obtenido:** se reporta que las configuraciones de privacidad elegidas no se guardan.
- **Recomendación:** revisar el guardado y la recuperación de las configuraciones de privacidad seleccionadas.

### H-11 — Visualización de personas sin consentimiento

- **Categoría:** Privacidad / presentación de imágenes.
- **Severidad:** Alta.
- **Descripción:** se plantea la necesidad de difuminar a las personas que aparecen en las imágenes cuando no se cuenta con su consentimiento.
- **Resultado esperado:** tratar las imágenes de acuerdo con el consentimiento correspondiente.
- **Recomendación:** evaluar la aplicación de difuminado a las personas que aparecen en las imágenes cuando no se dispone de su consentimiento.

### H-12 — Inconsistencias en la experiencia de realidad virtual

- **Categoría:** Usabilidad / realidad virtual.
- **Severidad:** Alta
- **Descripción:** se reportan dificultades para comprender y utilizar determinados elementos de la experiencia de realidad virtual.
- **Observaciones relacionadas:**
  - Desde el menú avanzado, las instrucciones paso a paso aparecen por encima del usuario, lo que resulta incómodo de visualizar.
  - El modo avanzado no deja claro a qué experiencia hace referencia.
  - Al utilizar las lentes y situarse en una esquina, la imagen se rompe.
- **Resultado esperado:** ofrecer instrucciones visibles y cómodas de consultar, explicar claramente los modos disponibles y mantener una presentación visual adecuada durante la experiencia.
- **Resultado obtenido:** se reportan dificultades de visualización de las instrucciones, falta de claridad sobre el modo avanzado y un problema de visualización en una ubicación concreta.
- **Recomendación:** revisar la ubicación de las instrucciones, aclarar el propósito del modo avanzado y verificar el comportamiento de la imagen en la situación descrita.

## 5. Matriz consolidada

| ID | Categoría | Hallazgo | Severidad | Estado | Evidencia |
|---|---|---|---|---|---|
| H-01 | Diseño visual | Inconsistencias visuales y tipográficas | Alta | Observado | [H-01] |
| H-02 | Navegación | Navegación confusa y falta de continuidad | Alta | Observado | - |
| H-03 | Interfaz | Animaciones y transiciones que dificultan la experiencia | Media | Observado | [H-03] |
| H-04 | Diseño visual | Imágenes y elementos visuales poco claros | Alta | Observado | - |
| H-05 | Usabilidad | Instrucciones y pasos poco claros | Media | Observado | [H-05] |
| H-06 | Retroalimentación | Falta de confirmación después de realizar acciones | Alta | Observado | - |
| H-07 | Funcionalidad | Dificultades en funcionalidades de perfil y visitas | Alta | Observado | [H-07] |
| H-08 | Versión móvil | Limitaciones y falta de claridad en el uso desde el celular | Media | Observado | - |
| H-09 | Formularios | Mensajes de error y validaciones | Alta | Observado | [H-09] |
| H-10 | Privacidad | Las configuraciones de privacidad no se conservan | Media | Observado | - |
| H-11 | Privacidad | Visualización de personas sin consentimiento | Alta | Revisión pendiente | - |
| H-12 | Realidad virtual | Inconsistencias en la experiencia de realidad virtual | Alta | Observado | - |

## 6. Escenarios técnicos ejecutados

| Escenario | Resultado esperado | Resultado obtenido 
|---|---|---
| Navegación mediante menús y enlaces | Acceder a la página correspondiente y mantener la orientación | Se reportan enlaces que no funcionan, menús que no corresponden y pérdida de orientación | 
| Guardado de comentarios | Mostrar una confirmación del guardado | No se muestra un mensaje de confirmación | 
| Visualización del ranking en el perfil | Reflejar el ranking en el perfil | Se indica que el ranking no se refleja | 
| Carga de fotografías de visitas | Permitir subir fotografías | Se indica que no se permite la carga | 
| Preparación de canje desde el celular | Permitir realizar el flujo correspondiente o informar la limitación | Se reporta que no se permite preparar el canje | 
| Persistencia de privacidad | Conservar las configuraciones elegidas | Se indica que las configuraciones no se guardan | 
| Validación del campo de contraseña | Aplicar las restricciones correspondientes | Se indica que permite más de 32 caracteres | 
| Visualización de imágenes en realidad virtual | Mantener una imagen correctamente presentada | Se reporta que la imagen se rompe al situarse en una esquina con las lentes | 

## 7. Recomendaciones priorizadas

Las siguientes acciones se organizan por áreas de mejora. La prioridad definitiva debe acordarse con el equipo auditado, ya que las observaciones no incluyen una evaluación formal de severidad.

1. **Consistencia visual y legibilidad:** unificar tipografías, tamaños de texto, apariencia del logo y pantallas de carga.
2. **Navegación y continuidad:** revisar enlaces y menús, incorporar un breadcrumb y facilitar la orientación entre páginas.
3. **Transiciones y carga:** reducir movimientos que generan mareo y mejorar la continuidad visual al cargar beneficios y otras secciones.
4. **Claridad de las instrucciones:** enumerar los pasos, mantener las instrucciones visibles y explicar los gestos y el modo avanzado.
5. **Retroalimentación:** mostrar confirmaciones al guardar comentarios y proporcionar información clara sobre el progreso de las acciones.
6. **Funcionalidades de perfil y visitas:** revisar la visualización del ranking y la carga de fotografías.
7. **Experiencia móvil:** revisar la preparación de canjes desde el celular y aclarar qué funcionalidades están disponibles.
8. **Formularios:** revisar los mensajes de error, las validaciones de campos vacíos y la restricción de longitud de la contraseña.
9. **Privacidad:** verificar la persistencia de las configuraciones seleccionadas y evaluar el tratamiento de imágenes cuando no se cuenta con consentimiento.
10. **Realidad virtual:** revisar la ubicación de las instrucciones y el problema de visualización de imágenes descrito.

## 8. Validación con el equipo auditado

| Hallazgo | ¿Se pudo reproducir? | Respuesta del equipo | Acción acordada |
|---|---|---|---|
| H-01 | [Completar] | [Comentario] | [Acción] |
| H-02 | [Completar] | [Comentario] | [Acción] |
| H-03 | [Completar] | [Comentario] | [Acción] |
| H-04 | [Completar] | [Comentario] | [Acción] |
| H-05 | [Completar] | [Comentario] | [Acción] |
| H-06 | [Completar] | [Comentario] | [Acción] |
| H-07 | [Completar] | [Comentario] | [Acción] |
| H-08 | [Completar] | [Comentario] | [Acción] |
| H-09 | [Completar] | [Comentario] | [Acción] |
| H-10 | [Completar] | [Comentario] | [Acción] |
| H-11 | [Completar] | [Comentario] | [Acción] |
| H-12 | [Completar] | [Comentario] | [Acción] |
