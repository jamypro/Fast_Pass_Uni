

#  Sistema de Pedidos para Cafeterías Universitarias

##  Descripción del Proyecto

Este proyecto propone el desarrollo de una **aplicación móvil para estudiantes universitarios** que permite realizar pedidos de comida en cafeterías y quioscos del campus de manera anticipada.

El objetivo principal del sistema es **reducir el tiempo de espera en filas**, optimizar el proceso de compra de alimentos y permitir a los estudiantes organizar mejor su tiempo durante los periodos de descanso o almuerzo.

La aplicación permitirá:

* Consultar el menú disponible
* Realizar pedidos anticipados
* Pagar desde la aplicación
* Recibir notificaciones cuando el pedido esté listo
* Elegir el punto de recogida
* Recoger el pedido de manera rápida

---

#  Historias de Usuario

## User Story #1: Ver el menú disponible

**Como** estudiante que tiene poco tiempo para almorzar
**quiero** ver el menú de la cafetería y quioscos desde la aplicación
**para** decidir qué comer antes de ir a recoger mi pedido.

---

## User Story #2: Hacer un pedido anticipado

**Como** estudiante que está en clase
**quiero** pedir mi comida desde el celular con anticipación
**para** evitar hacer largas filas en la cafetería.

---

## User Story #3: Recibir notificación cuando el pedido esté listo

**Como** estudiante que pidió comida en la app
**quiero** recibir una notificación cuando mi pedido esté listo
**para** ir a recogerlo sin tener que esperar.

---

## User Story #4: Pagar desde la aplicación

**Como** estudiante que quiere ahorrar tiempo
**quiero** pagar mi pedido desde la aplicación
**para** no tener que hacer fila en la caja.

---

## User Story #5: Ver si el menú está disponible

**Como** estudiante que quiere el menú del día
**quiero** ver si un plato aún está disponible en la app
**para** no hacer un pedido de algo que ya se agotó.

---

## User Story #6: Elegir punto de recogida

**Como** estudiante que compra comida en el campus
**quiero** elegir el quiosco o cafetería donde recoger mi pedido
**para** pasar por el lugar más cercano a mi clase.

---

## User Story #7: Reducir el tiempo de espera

**Como** estudiante con solo una hora de almuerzo
**quiero** recoger mi comida rápidamente
**para** poder comer tranquilo y llegar puntual a mi siguiente clase.

---

#  Requerimientos Funcionales

## Requisito #1: Ver el menú disponible

El sistema debe permitir al estudiante visualizar el menú disponible de las cafeterías y quioscos desde la aplicación.

**Funciones:**

* Mostrar nombre del plato
* Mostrar precio
* Mostrar descripción
* Indicar si el producto está **disponible o agotado**

---

## Requisito #2: Hacer un pedido anticipado

El sistema debe permitir al estudiante realizar pedidos de comida de manera anticipada desde la aplicación.

**Funciones:**

* Permitir seleccionar productos del menú
* Permitir confirmar el pedido antes de enviarlo

---

## Requisito #3: Recibir notificación cuando el pedido esté listo

El sistema debe notificar al estudiante cuando su pedido esté preparado.

**Funciones:**

* Mostrar el estado del pedido:

  * En preparación
  * Listo
* Enviar una **notificación en la aplicación**

---

## Requisito #4: Pagar desde la aplicación

El sistema debe permitir al estudiante pagar el pedido directamente desde la aplicación.

**Funciones:**

* Mostrar el total del pedido antes del pago
* Confirmar el pago realizado

---

## Requisito #5: Ver disponibilidad del menú

El sistema debe mostrar la disponibilidad actual de los productos.

**Funciones:**

* Marcar los productos agotados
* Actualizar automáticamente la disponibilidad del menú

---

## Requisito #6: Elegir punto de recogida

El sistema debe permitir al estudiante seleccionar dónde recoger su pedido.

**Funciones:**

* Mostrar lista de cafeterías o quioscos disponibles
* Asociar el pedido al punto de recogida seleccionado

---

## Requisito #7: Recoger el pedido rápidamente

El sistema debe permitir al estudiante consultar el estado del pedido y recogerlo cuando esté listo.

**Funciones:**

* Mostrar número o código del pedido
* Confirmar la entrega del pedido

---

# Diagramas de Flujo del Sistema

Los siguientes diagramas representan el flujo de funcionamiento de las principales funcionalidades del sistema.

---

# Diagrama de Flujo – Historias de Usuario 1 y 2

🔗 Diagrama:
[Diagrama 1 y 2: ]([https://lucid.app/lucidchart/f3ea9b3d-ef91-4b2f-93c8-4cb1b55c7bdf](https://lucid.app/lucidchart/f3ea9b3d-ef91-4b2f-93c8-4cb1b55c7bdf/edit?invitationId=inv_e7c102ba-c068-4327-8786-3f293eab8515))

### Explicación del flujo

1️⃣ El estudiante abre la aplicación.

2️⃣ El sistema carga el **menú disponible de cafeterías y quioscos**.

3️⃣ El estudiante revisa:

* nombre del plato
* precio
* descripción
* disponibilidad

4️⃣ El estudiante selecciona uno o varios productos.

5️⃣ El sistema agrega los productos al **carrito de pedido**.

6️⃣ El estudiante revisa su pedido.

7️⃣ Finalmente el estudiante **confirma el pedido anticipado**.

Este proceso permite que el estudiante **realice el pedido antes de llegar a la cafetería**, reduciendo el tiempo de espera.

---

# Diagrama de Flujo – Historias de Usuario 3, 4 y 5

🔗 Diagrama:
[Diagrama 3, 4 y 5: ](https://lucid.app/lucidchart/58030be7-1621-49a4-94be-3ba6ccc94b0b/edit?viewport_loc=-3087%2C1007%2C2336%2C1060%2C0_0&invitationId=inv_09bc8dc7-499a-44b7-8e58-c1fec75867af)

### Explicación del flujo

1️⃣ El estudiante confirma su pedido en la aplicación.

2️⃣ El sistema muestra el **total del pedido**.

3️⃣ El estudiante realiza el **pago desde la aplicación**.

4️⃣ El sistema registra el pago y envía el pedido a la cafetería.

5️⃣ El personal de la cafetería comienza la preparación del pedido.

6️⃣ Durante este proceso el sistema muestra el estado:

* En preparación
* Listo

7️⃣ Cuando el pedido está listo, el sistema envía una **notificación al estudiante**.

Esto permite que el estudiante **no tenga que esperar en el lugar mientras preparan su comida**.

---

# Diagrama de Flujo – Historias de Usuario 6 y 7

🔗 Diagrama:
[Diagrama 6 y 7: ](https://lucid.app/lucidchart/792d4cd4-713b-4713-9ed4-f61820470fdd/edit?viewport_loc=-1632%2C351%2C1766%2C801%2C0_0&invitationId=inv_686a52d5-a4b6-4a33-83b3-c36d6551122d)

### Explicación del flujo

1️⃣ El estudiante selecciona el **punto de recogida** dentro de la aplicación.

2️⃣ El sistema muestra las **cafeterías o quioscos disponibles en el campus**.

3️⃣ El estudiante elige el punto más cercano a su ubicación o clase.

4️⃣ El sistema asocia el pedido a ese punto de recogida.

5️⃣ Cuando el pedido está listo, el estudiante se dirige al lugar seleccionado.

6️⃣ El estudiante muestra el **código o número del pedido**.

7️⃣ El personal confirma la entrega del pedido.

Este proceso permite **recoger la comida rápidamente**, evitando filas y mejorando la organización del servicio.

---

# Beneficios del Sistema

Implementar este sistema permitiría:

* Reducir filas en cafeterías
* Optimizar el tiempo de los estudiantes
* Mejorar la organización de pedidos
* Evitar pedidos de productos agotados
* Facilitar el proceso de pago
* Mejorar la experiencia de compra dentro del campus

---

# Autores
* Males Goyes Jeison Andres
* Claros Muñoz Jefferson Andres

---
