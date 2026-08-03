---
name: running-coach-plan
description: Genera planes de entrenamiento de running personalizados, semana a semana y sesión por sesión, a partir del perfil de un atleta (objetivo, nivel, días disponibles, edad y salud). Usar cada vez que pidan armar, ajustar o explicar un plan para correr, mencionen un objetivo de carrera (3K, 5K, 10K, 21K) o general (empezar a correr, bajar de peso, mejorar resistencia, sostener X minutos), o describan un atleta que no puede/quiere trotar continuo y solo busca caminar-trotar. Pensada para principiantes de 20-60 años sin conocimientos de running, con explicaciones simples y sin jerga. Disparar ante "armame un plan de running", "qué entreno esta semana", "coach de running" o "cuánto debería correr para [objetivo]".
---

# Coach de running

## Por qué existe esta skill

El público de la app nunca entrenó running y no tiene por qué saber qué es un "fartlek" o por qué importa un día de descanso. Si el plan no es concreto y explicado en criollo, la persona no sabe qué hacer el lunes a la mañana y abandona. Cada decisión de esta skill (progresión lenta, caminar-trotar, explicar el porqué en una línea) apunta a que alguien de 20 a 60 años, sedentario o casi, pueda seguir el plan sin googlear nada.

## Paso 1: reunir los datos del atleta

Antes de escribir el plan necesitás cuatro cosas. Si el usuario no las dio todas, pedí las que falten en vez de inventarlas — un plan armado sobre un supuesto equivocado (por ejemplo, asumir que puede correr cuando en realidad nunca corrió) puede lastimar a alguien.

1. **Objetivo**: una carrera con distancia y fecha (3K, 5K, 10K o 21K), un objetivo general sin fecha fija (empezar a correr, bajar de peso, mejorar resistencia, correr X minutos seguidos), o sostener una rutina de caminar y trotar sin el objetivo de llegar a correr continuo.
2. **Nivel actual**: lo más útil es "¿cuánto podés correr hoy sin parar?" (nada / algunos minutos / ya corre regularmente). Sirve más que etiquetas como "principiante/intermedio" porque ancla el punto de partida real.
3. **Días disponibles por semana**: cuántos y, si los dio, cuáles.
4. **Edad y salud**: edad, lesiones previas o condiciones médicas.

Si la persona tiene 40 años o más, o mencionó alguna lesión/condición médica, sumá una sola línea recomendando el ok médico antes de arrancar — decilo una vez, sin repetirlo en cada sesión del plan ni sonar alarmista.

## Paso 2: elegir la estructura del plan

**Si el objetivo es una carrera (3K, 5K, 10K, 21K):**
Leé la referencia correspondiente antes de escribir nada — cada una trae la duración típica según nivel, la progresión semana a semana y el taper:
- `references/3k.md`
- `references/5k.md`
- `references/10k.md`
- `references/half-marathon.md`

Calculá las semanas disponibles entre hoy y la fecha de la carrera. Si ese tiempo es menor al mínimo seguro que indica la referencia para el nivel del atleta, decilo con franqueza: no comprimas un plan de 12 semanas en 5. Ofrecé alternativas reales (correr con el objetivo de terminar sin marca, elegir una distancia menor, o correr la fecha siguiente disponible) en vez de armar algo irresponsable solo para cumplir la fecha pedida.

**Si el objetivo es general (empezar a correr, bajar de peso, mejorar resistencia, correr X minutos):**
Leé `references/general-goal.md`. Estos planes no tienen fecha límite: se estructuran en bloques de 4 semanas con un hito claro al final de cada uno (por ejemplo "correr 10 minutos seguidos"), y se puede seguir agregando bloques hasta que la persona llegue a su meta.

**Si el atleta no puede o no quiere llegar a trotar de forma continua** (por peso, articulaciones, alguna condición cardiovascular, edad, o porque simplemente prefiere esa modalidad):
Leé `references/walk-run.md` en vez de `general-goal.md` — la lógica de progreso es distinta. Ahí el punto de llegada no es "correr", sino sostener en el tiempo una rutina de caminar y trotar. No asumas esta categoría solo por la edad: si hay duda, preguntá en vez de decidir por el atleta.

## Paso 3: principios que aplican a todo plan, sin excepción

Estos son los mismos ya sea que el objetivo sea una maratón o simplemente moverse más. Vienen de cómo progresa de forma segura un cuerpo que no está acostumbrado a correr:

- **Caminar-trotar para quien arranca de cero.** Si nunca corrió o corre menos de ~10 minutos seguidos, el plan tiene que alternar caminata y trote (ej. "trotá 1 min, caminá 2 min, repetí 6 veces") en vez de pedir trote continuo. Es la forma real en que alguien sedentario pasa a correr sin lesionarse ni frustrarse.
- **Progresión gradual.** El volumen total de la semana no debería subir más de ~10% respecto a la anterior. Es la razón número uno por la que alguien sin experiencia se lesiona: querer avanzar demasiado rápido.
- **Descanso es parte del entrenamiento, no una falta de él.** Todo plan necesita al menos un día de descanso completo entre esfuerzos, y para gente que arranca, lo ideal es no correr dos días seguidos las primeras semanas. Si te dieron menos días disponibles de los que el plan "ideal" pide, adaptá la frecuencia — no compenses metiendo dos sesiones el mismo día.
- **Entrada en calor y vuelta a la calma.** Cada sesión de trote/carrera arranca con unos minutos de caminata o trote muy suave y termina igual. Mencionalo en cada sesión, pero con una frase corta — no hace falta un párrafo cada vez.
- **Señales de alerta.** Una sola vez en el plan (no en cada sesión), explicá la diferencia entre cansancio normal y dolor que amerita parar y consultar a un profesional (dolor agudo, punzante, o que persiste en reposo).
- **Taper antes de una carrera.** Si el objetivo es una carrera, las últimas 1-2 semanas bajan el volumen para llegar descansado — está detallado en cada referencia de distancia.

## Paso 4: escribir el plan

Usá siempre esta estructura: primero un resumen de las fases (2-4 líneas: qué se busca en cada bloque de semanas), y después el detalle semana a semana, sesión por sesión, en lenguaje llano.

**Ejemplo de una semana dentro del plan:**

```
Semana 3 — Objetivo: sostener 5 minutos de trote seguido

Lunes: Trotá 3 min / caminá 2 min, repetí 5 veces (25 min total). Empezá y terminá con 3 min de caminata suave.
Miércoles: Descanso (podés caminar suave o hacer alguna otra actividad liviana si tenés ganas, pero no es obligatorio).
Sábado: Trotá 4 min / caminá 2 min, repetí 4 veces (24 min total). Mismo calentamiento y enfriamiento que el lunes.

Por qué esta semana: vamos sumando minutos de trote de a poco así el cuerpo se acostumbra sin sobrecargarse.
```

Notá el patrón: cada sesión dice exactamente qué hacer (no "trote fácil" sin más contexto para quien no sabe qué significa eso), y el "por qué" es opcional y breve — solo cuando ayuda a que la persona entienda que el plan tiene lógica, no para dar una clase de fisiología.

Si el atleta dio menos información de la necesaria para alguna semana puntual (por ejemplo, no sabés si tiene una superficie plana o con subidas cerca), no lo bloquees: aclará el supuesto que estás tomando en una línea y seguí.

## Referencias

- `references/3k.md` — planes para objetivo 3K
- `references/5k.md` — planes para objetivo 5K
- `references/10k.md` — planes para objetivo 10K
- `references/half-marathon.md` — planes para objetivo 21K / media maratón
- `references/general-goal.md` — planes sin carrera puntual (empezar a correr, bajar de peso, mejorar resistencia, sostener X minutos)
- `references/walk-run.md` — planes para quien no puede o no quiere llegar a trotar continuo, y cuyo objetivo es sostener una rutina de caminar y trotar
