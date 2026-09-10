---
name: responder-clientes
description: >
  Escribe respuestas listas para enviar a clientes por WhatsApp o correo según la situación:
  consulta de precio, cliente que desapareció, reclamo, cliente que regatea, cobro de una
  factura impaga, o decir que no a un trabajo. Mantiene un tono cordial y firme, sin sonar
  robótico ni suplicante. Úsalo cuando el usuario diga "cómo le respondo a este cliente",
  "no sé qué contestar", "me llegó este mensaje", "tengo que cobrarle a alguien",
  "cómo le digo que no" o cuando pegue una conversación con un cliente.
---

# Responder a clientes

Lo que hay que escribir cuando no sabes cómo contestar.

---

## Paso 1 — Identificar la situación

Si el usuario pegó el mensaje del cliente, léelo y clasifícalo. Si no, pregunta qué pasó.

Las situaciones típicas están abajo. Si no calza con ninguna, arma la respuesta con las reglas generales del final.

---

## Situación 1 — "¿Cuánto cuesta?" y nada más

El error clásico es tirar el precio de inmediato. Antes de eso hay que entender qué necesita, o el precio no significa nada.

```
Hola [nombre], gracias por escribir 🙌

Para darte un precio real necesito saber un par de cosas:

1. [pregunta clave del rubro]
2. [pregunta clave del rubro]

Con eso te mando una propuesta hoy mismo.
```

**Si insiste en un número al tiro:** dale un rango honesto. "Trabajos como el que describes andan entre $X y $Y, depende de [factor]".

---

## Situación 2 — El cliente desapareció

Le mandaste la cotización y silencio. Espera **3 días hábiles** antes del primer seguimiento.

**Primer seguimiento:**
```
Hola [nombre], ¿alcanzaste a ver la propuesta que te mandé?

Cualquier duda me dices, o si necesitas que ajustemos algo lo vemos sin problema.
```

**Segundo seguimiento, una semana después:**
```
Hola [nombre], te escribo por última vez para no seguir molestando.

Si el proyecto quedó para más adelante no hay drama, me avisas cuando
lo retomes. Y si decidiste ir por otro camino, también me sirve saberlo
para cerrar el presupuesto.
```

**Nunca hay un tercer seguimiento.** El segundo mensaje da permiso a decir que no, y eso es justamente lo que hace que muchos respondan.

---

## Situación 3 — Reclamo

Orden obligatorio: **reconocer → hacerse cargo → solución concreta → plazo**.

```
Hola [nombre], tienes razón y lamento que haya pasado.

[Explicación breve, sin excusas largas ni echarle la culpa a otro.]

Lo voy a solucionar así: [qué vas a hacer, concreto].
Lo tengo listo el [fecha].

Cualquier cosa me escribes directo.
```

**Reglas del reclamo:**
- Nunca discutas por escrito quién tiene la razón
- Nunca uses "lamento que te sientas así". Es un no-perdón y se nota
- Si el error fue tuyo, dilo derecho. Se pierde menos que negándolo
- Si el reclamo no corresponde, igual parte reconociendo la molestia, y después explica

---

## Situación 4 — El que regatea

La regla de oro: **no bajes el precio, saca alcance.**

```
Te entiendo. Lo que puedo hacer es ajustar el alcance para que
calce con ese presupuesto:

Por $[monto que ofrece] queda [versión reducida: menos entregables,
menos rondas de cambios, menos secciones].

La propuesta completa se mantiene en $[precio original].

Dime cuál te acomoda más.
```

Explícale al usuario por qué: si bajas el precio por el mismo trabajo, le enseñas al cliente que tu precio era inflado. Y el próximo trabajo también lo va a regatear.

---

## Situación 5 — Cobrar una factura impaga

Escalar de a poco, sin perder la cordialidad.

**Primer aviso, a los 3 días de vencido:**
```
Hola [nombre], te recuerdo la factura [número] por $[monto], que venció
el [fecha]. ¿La pudiste procesar?
```

**Segundo, una semana después:**
```
Hola [nombre], insisto con la factura [número] por $[monto], vencida
hace [X] días. ¿Hubo algún problema con el pago? Si necesitas otro
plazo, dime y lo conversamos.
```

**Tercero, dos semanas después:**
```
[nombre], la factura [número] lleva [X] días vencida y no he tenido
respuesta. Necesito que quedemos de acuerdo en una fecha de pago
esta semana. Mientras tanto dejo en pausa [el trabajo pendiente].
```

**Consejo para el usuario:** si esto pasa seguido, el problema está en las condiciones. Cobrar 50% de adelanto elimina casi todos estos casos.

---

## Situación 6 — Decir que no

Se puede rechazar sin cerrar la puerta.

```
Hola [nombre], gracias por pensar en mí para esto.

Prefiero ser honesto: [no es lo mío / no tengo la disponibilidad
que este proyecto necesita / no llego con los plazos].

Prefiero decírtelo ahora y no quedarte mal después.
[Si conoces a alguien: "te puedo recomendar a X, que hace justo esto".]

Cualquier otra cosa, me escribes.
```

---

## Reglas generales

- **Nunca** escribas enojado. Si el usuario está molesto, dile que escriba el mensaje y lo mande **al día siguiente**
- **Nunca** uses lenguaje de call center: "estimado cliente", "quedamos atentos a su pronta respuesta", "reciba un cordial saludo"
- **Nunca** te disculpes de más ni supliques. Una disculpa basta
- **Nunca** prometas plazos que el usuario no puede cumplir. Pregúntale antes de poner una fecha
- Mensajes de WhatsApp: **cortos**. Si pasa de 6 líneas, va por correo
- Trata de tú, salvo que el usuario diga que ese cliente es formal
- **Nunca** inventes datos: montos, números de factura, fechas. Pregúntalos

---

## Cómo sé que quedó bien

- [ ] El mensaje se puede copiar y enviar sin editar nada más que los datos
- [ ] No hay lenguaje robótico ni de formulario
- [ ] Si hay un compromiso, tiene fecha concreta
- [ ] No prometí nada que el usuario no me haya confirmado que puede cumplir
- [ ] Si es WhatsApp, tiene menos de 6 líneas
