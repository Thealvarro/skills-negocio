<div align="center">

![skills-negocio — Skills de IA para emprendedores y negocios reales](assets/banner.png)

</div>

# Skills para tu negocio

**5 skills gratis para Claude y ChatGPT.** Para gente que tiene un negocio, no para programadores.

Una skill es un archivo de texto donde está escrito cómo hacer una tarea bien. Se lo pasas una vez a la IA y de ahí en adelante ya sabe cómo lo haces tú.

---

## Instalación: pégale esto a tu IA

Copia este mensaje completo y pégalo en **Claude** o **ChatGPT**:

```
Instala las skills de este repositorio:
https://github.com/Thealvarro/skills-negocio

Léelo, dime qué skills trae y para qué sirve cada una,
y déjalas listas para que las use.
```

Eso es todo. La IA lee el repositorio y las deja disponibles.

### Qué esperar según dónde estés

| Dónde | Qué pasa |
|---|---|
| **Claude Code** | Se instalan de verdad. Quedan disponibles siempre, en todos tus chats |
| **Claude.ai** (navegador) | Las lee y las usa en esa conversación. Para dejarlas fijas, créate un Proyecto y pega el contenido en sus instrucciones |
| **ChatGPT** | Igual que Claude web. Para dejarlas fijas, créate un GPT personalizado |

---

## Qué trae

| Skill | Para qué sirve | Le dices algo como… |
|---|---|---|
| **responder-clientes** | Qué contestar en WhatsApp y correo: el que regatea, el que desapareció, un reclamo, cobrar una factura impaga, decir que no | *"cómo le respondo a este cliente"* |
| **cotizar-cliente** | Armar la cotización y calcular cuánto cobrar de verdad | *"cuánto le cobro a este cliente"* |
| **prospectar-clientes** | El primer mensaje a alguien que no te conoce, sin sonar a spam | *"cómo le escribo a este negocio"* |
| **descripcion-productos** | Descripciones de catálogo que venden, para ecommerce o Instagram | *"descríbeme este producto"* |
| **ordenar-mi-semana** | Tus pendientes desordenados convertidos en un plan con prioridades | *"estoy colapsado, ordename la semana"* |

---

## Instalación manual

Si prefieres hacerlo tú:

**En Claude.ai o ChatGPT:** abre el `SKILL.md` de la skill que quieras, copia todo el contenido y pégalo al inicio de una conversación nueva. Debajo escribe lo que necesitas.

**En Claude Code:** copia la carpeta completa de la skill a `~/.claude/skills/` (en Windows: `C:\Users\TU-USUARIO\.claude\skills\`). Reinicia y listo.

> La carpeta tiene que llamarse igual que el `name` de la primera línea del archivo, o no la encuentra.

---

## Cómo saber si funcionó

Pídele algo que la skill cubra. Por ejemplo:

> *"Un cliente me pidió una web de 5 páginas. Ayúdame a cotizar."*

Si funcionó, **no te va a tirar un precio al azar: te va a empezar a hacer preguntas** para calcularlo bien.

Esa es la señal. Que pregunte antes de responder significa que está siguiendo la skill.

---

## Son tuyas: edítalas

Si el resultado no te gustó, **abre el archivo y cámbialo**. Es texto plano, se edita con el Bloc de notas.

Esa es la parte que a nadie le cae la primera vez: las skills no son intocables. Ajústalas para que trabajen como trabajas tú.

Y cuando quieras crear la tuya propia, copia una de estas y úsala de molde.

---

## Estructura del repositorio

```
skills/
├── responder-clientes/SKILL.md
├── cotizar-cliente/SKILL.md
├── prospectar-clientes/SKILL.md
├── descripcion-productos/SKILL.md
└── ordenar-mi-semana/SKILL.md
```

Cada `SKILL.md` empieza con un bloque `---` que declara `name` y `description`, y sigue con las instrucciones en español.

---

<sub>Desarrollado por <a href="https://alvarocofre.dev" target="_blank" rel="noopener noreferrer">SICS</a> · Licencia MIT: úsalas, cámbialas y compártelas</sub>
