# Criterios de clasificación de osu!catch

***Aviso: Este artículo es una extensión de los [criterios de clasificación generales](/wiki/Ranking_criteria).***

Este conjunto de **criterios de clasificación de osu!catch** establece [reglas y pautas](/wiki/Ranking_criteria) que los [beatmaps](/wiki/Beatmap) específicos de [osu!catch](/wiki/Game_mode/osu!catch) deben seguir para avanzar en el [procedimiento de clasificación](/wiki/Beatmap_ranking_procedure).

## Universal

Las reglas y pautas generales se aplican a todo tipo de dificultad de osu!catch. Las reglas y pautas relacionadas con el ritmo se aplican a beatmaps de aproximadamente 180 BPM con compases de 4/4. Si tu canción es drásticamente más rápida o más lenta, algunas variables pueden ser diferentes, como se detalla en [Escalado del BPM según los criterios de clasificación](/wiki/Ranking_criteria/Scaling_BPM).

### General

#### Reglas

- **Debe ser posible obtener una SS en tu beatmap.** Esto significa que debe ser posible atrapar absolutamente todas las [frutas](/wiki/Gameplay/Hit_object/Fruit), [gotas](/wiki/Gameplay/Hit_object/Juice_stream#gota) y [gotitas](/wiki/Gameplay/Hit_object/Juice_stream#gotita).
- **Cada beatmap debe usar al menos dos [colores de combo](/wiki/Beatmapping/Combo_colour) diferentes, a menos que se fuerce el uso de la skin por defecto.** 
  - Los colores de combo no deben mezclarse con el fondo, storyboard o vídeo del beatmap en ningún caso.
- **No uses keysounds sin el soporte de un hitnormal.** Si los sonidos se mezclan perfectamente con la canción, la retroalimentación al atrapar las notas es mínima.
- **Si el [tiempo de drenaje](/wiki/Beatmap/Drain_time) de cada dificultad es...**
  - **... menos de 2:30**, la dificultad más baja no puede ser más difícil que una Salad, o proporcionar una distribución adecuada[^proper-spread] que contenga al menos 4 dificultades.
  - **... entre 2:30 y 3:15**, la dificultad más baja no puede ser más difícil que una Platter, o proporcionar una distribución adecuada[^proper-spread] que contenga al menos 3 dificultades.
  - **... entre 3:15 y 4:00**, la dificultad más baja no puede ser más difícil que una Rain, o proporcionar una distribución adecuada[^proper-spread] que contenga al menos 2 dificultades.
  - **Se pueden combinar los [descansos](/wiki/Beatmap/Break) con el [tiempo de drenaje](/wiki/Beatmap/Drain_time) para alcanzar los umbrales mencionados anteriormente.** Para la dificultad más alta, esto está limitado a 30 segundos de descanso como máximo. Esto no se aplica a dificultades con menos de 30 segundos de tiempo de drenaje.

#### Pautas

- **Todos las [frutas](/wiki/Gameplay/Hit_object/Fruit) deben representar un sonido existente en la música.** Esto suele ser un sonido distintivo, pero también puede representar un sonido continuo con un inicio o final indistinguible.
- **Los finales de sliders extendidos deben sincronizarse según la estructura rítmica de la canción.** Si la canción usa un compás cuaternario, se deben usar ajustes de 1/4, 1/8 y 1/16. Si la canción usa un compás ternario, se deben usar ajustes de 1/6 o 1/12.
- **No se deben usar [dashes](/wiki/Gameplay/Dash) e [hiperdashes](/wiki/Gameplay/Hyperdash) cuando el destino del dash o hiperdash esté cerca del borde izquierdo o derecho del campo de juego.** Esto crea un movimiento incómodo, ya que el catcher se detiene bruscamente al alcanzar el borde del campo de juego (x:16 a la izquierda y x:496 a la derecha).
- **Los [combos](/wiki/Beatmapping/Combo) no deberían ser extremadamente largos.** Esto asegura que las [frutas](/wiki/Gameplay/Hit_object/Fruit) atrapadas no obstruyan la vista del jugador.
- **La [dificultad general](/wiki/Beatmap/Overall_difficulty) debería tener el mismo valor que la [velocidad de aproximación](/wiki/Beatmap/Approach_rate).** Este es un valor estandarizado, ya que la dificultad general solo afecta a la puntuación máxima de una dificultad con [ScoreV1](/wiki/Gameplay/Score/ScoreV1/osu!catch).
  - Si una dificultad usa una velocidad de aproximación más baja que una o más dificultades en el nivel de dificultad inferior, entonces la dificultad general debería ser igual a la del valor de dificultad general más alto en la dificultad anterior.
- **La tasa de marcas del slider debe establecerse según la canción.** Por ejemplo, si tu canción solo usa un ritmo de 1/3, usar una tasa de marcas de 2 no se ajustaría a todo el beatmap.
- **Evita usar [colores de combo](/wiki/Beatmapping/Combo_colour) con una luminosidad de ~50 o menor.** Los colores oscuros influyen en la visibilidad de las [frutas](/wiki/Gameplay/Hit_object/Fruit) usando un fondo oscuro.
- **Evita usar [colores de combo](/wiki/Beatmapping/Combo_colour) con una luminosidad de ~220 o mayor si se usa un Kiai time.** Los colores luminosos crean pulsaciones brillantes en los Kiai time, lo cual puede ser incómodo para la vista.

### Skinning

#### Reglas

- **Los catchers personalizados deben ser incluidos en el formato de skin v2.** Los elementos necesarios pueden encontrarse en el [artículo de skinning de osu!catch](/wiki/Skinning/osu!catch).
- **Los objetos personalizados tienen que incluir todos los elementos necesarios y estar coloreados en una escala de grises.** Esto es para asegurar que tus imágenes estén definidas claramente y con una calidad aceptable. Los elementos necesarios pueden ser encontrados en [el artículo de skinning de osu!catch](/wiki/Skinning/osu!catch). Además, es recomendable usar elementos transparentes para las superposiciones.
- **Los elementos de la skin tienen que tener el mismo tamaño que los elementos correspondientes de la skin por defecto.** Esto es para representar el área de impacto apropiadamente y no alterar la dificultad. Las dimensiones usadas en la skin por defecto son 128x128 píxeles para las [frutas](/wiki/Gameplay/Hit_object/Fruit), 82x103 para las [gotas](/wiki/Gameplay/Hit_object/Juice_stream#gota) y 306x320 para el catcher.

## Dificultades específicas

Las reglas y pautas para las dificultades específicas solo se aplican al nivel de dificultad que se indica y, por lo tanto, *no se aplican a **todas** las dificultades de osu!catch*. Las reglas y pautas relacionadas al ritmo aplican para los beatmaps de aproximadamente 180 BPM. Si tu canción es drásticamente más rápida o lenta, algunas variables pueden ser diferentes, como se detalla en [Escalado del BPM según los criterios de clasificación](/wiki/Ranking_criteria/Scaling_BPM).

### Nombres de las dificultades

*Artículo principal: [Nombramiento de las dificultades](/wiki/Ranking_criteria/Difficulty_naming)*

- ![](/wiki/shared/diff/easy-c.png?20211215) Cup
- ![](/wiki/shared/diff/normal-c.png?20211215) Salad
- ![](/wiki/shared/diff/hard-c.png?20211215) Platter
- ![](/wiki/shared/diff/insane-c.png?20211215) Rain
- ![](/wiki/shared/diff/expert-c.png?20211215) Overdose

### Tabla de referencia para snaps

| Dificultad | Dash de snap básico | Dash de snap alto | Hiperdash de snap básico | Hiperdash de snap alto |
| :-- | :-- | :-- | :-- | :-- |
| **Cup** | - | - | - | - |
| **Salad** | 250 ms o más | 125-249 ms | - | - |
| **Platter** | 125 ms o más | 62-124 ms | 250 ms o más | 125-249 ms |
| **Rain** | 125 ms o más | 62-124 ms | 125 ms o más | 62-124 ms |
| **Overdose** | - | - | - | - |

### ![](/wiki/shared/diff/easy-c.png?20211215) Cup

#### Reglas

- Los **[dashes](/wiki/Gameplay/Dash) e [hiperdashes](/wiki/Gameplay/Hyperdash) de cualquier tipo no están permitidos.**
- **Debe haber al menos 250 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el inicio y final de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**

#### Pautas

- **Los [combos](/wiki/Beatmapping/Combo) no deben exceder los 8 objetos, incluyendo los finales y las repeticiones de los sliders.** Los [spinners](/wiki/Gameplay/Hit_object/Spinner) son una excepción.
- **La densidad de las notas debe seguir principalmente un patrón de 1/1.** Los patrones de 1/2 y/o 1/3 deben usarse con moderación.

#### Pautas para la configuración de la dificultad

- La [velocidad de aproximación](/wiki/Beatmap/Approach_rate) y la [dificultad general](/wiki/Beatmap/Overall_difficulty) deberían ser iguales o menor a 6.
- La [tasa de drenaje de HP](/wiki/Beatmap/HP_drain_rate) debería ser entre 2 y 3.
- El [tamaño del círculo](/wiki/Beatmap/Circle_size) debería ser menor o igual a 2,5.

### ![](/wiki/shared/diff/normal-c.png?20211215) Salad

#### Reglas

- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de cualquier tipo no están permitidos.**
- **Los [dashes](/wiki/Gameplay/Dash) deben tener al menos un espacio de 125 ms entre sus dos objetos.**
- **Los [dashes](/wiki/Gameplay/Dash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^salad-basic-dash] no deben usarse más de dos veces entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y [gotas](/wiki/Gameplay/Hit_object/Juice_stream#gota) consecutivas.**
- **Los [dashes](/wiki/Gameplay/Dash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^salad-higher-dash] siempre deben ir seguidos de un [walk](/wiki/Gameplay/Walk).**
- **Los [edge dashes](/wiki/Gameplay/Edge_dash) no deben ser usados.**
- **Debe haber al menos 250 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el inicio y final de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**

#### Pautas

- **Todas las distancias deben dejar claro si requieren que el jugador haga un [walk](/wiki/Gameplay/Walk) o un [dash](/wiki/Gameplay/Dash).** Esto es para asegurar que los jugadores puedan reconocer fácilmente patrones que requieran hacer un dash.
- **Los [dashes](/wiki/Gameplay/Dash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^salad-basic-dash] no deben usarse consecutivamente cuando se usan ritmos diferentes.**
- **Los [dashes](/wiki/Gameplay/Dash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^salad-higher-dash] no deben ir seguidos de patrones [antiflow](/wiki/Beatmapping/Mapping_techniques/Antiflow).**
- **No se deben usar [spinner traps](/wiki/Gameplay/Spinner_trap).**
- **Los [combos](/wiki/Beatmapping/Combo) no deben exceder las 10 [frutas](/wiki/Gameplay/Hit_object/Fruit).**
- **La densidad de las notas debe seguir principalmente un patrón de 1/1 y 1/2.** Los patrones de 1/3 y/o 1/4 deben usarse con moderación.

#### Pautas para la configuración de la dificultad

- La [velocidad de aproximación](/wiki/Beatmap/Approach_rate) y la [dificultad general](/wiki/Beatmap/Overall_difficulty) deberían ser iguales o menor a 7.
- La [tasa de drenaje de HP](/wiki/Beatmap/HP_drain_rate) debería ser entre 3 y 4.
- El [tamaño del círculo](/wiki/Beatmap/Circle_size) debería ser igual o menor a 3.

### ![](/wiki/shared/diff/hard-c.png?20211215) Platter

#### Reglas

- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) deben tener al menos un espacio de 125 ms entre sus dos objetos.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) no pueden usarse en [gotas](/wiki/Gameplay/Hit_object/Juice_stream#gota) individuales y/o repeticiones de sliders.** La precisión y control requeridos son poco razonables en este nivel y pueden crear una situación donde el jugador potencialmente no pueda leer la trayectoria del slider.
- **No se pueden usar [hiperdashes](/wiki/Gameplay/Hyperdash) de un ritmo diferente entre [frutas](/wiki/Gameplay/Hit_object/Fruit) consecutivas.** Por ejemplo, un hiperdash de 1/2 seguido de un hiperdash de 1/4.
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^platter-basic-hyperdash] no deben usarse más de dos veces entre [frutas](/wiki/Gameplay/Hit_object/Fruit) consecutivas.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^platter-higher-hyperdash] no deben usarse junto con ningún otro [dash](/wiki/Gameplay/Dash) o hiperdash.**
- **Los [dashes](/wiki/Gameplay/Dash) deben tener al menos un espacio de 62 ms entre sus dos objetos.**
- **Los [dashes](/wiki/Gameplay/Dash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^platter-basic-dash] no deben usarse más de cuatro veces entre [frutas](/wiki/Gameplay/Hit_object/Fruit) consecutivas.**
- **Los [dashes](/wiki/Gameplay/Dash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^platter-higher-dash] pueden usarse hasta dos veces entre [frutas](/wiki/Gameplay/Hit_object/Fruit) consecutivas, siempre que no haya un cambio de dirección entre ellos.**
- **Los [edge dashes](/wiki/Gameplay/Edge_dash) no deben ser usados.**
- **Debe haber al menos 125 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el inicio de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**
- **Debe haber al menos 250 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el final de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**

#### Pautas

- **No se deben usar [hiperdashes](/wiki/Gameplay/Hyperdash) fuertes.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^platter-higher-hyperdash] no deben ir seguidos de patrones de [antiflow](/wiki/Beatmapping/Mapping_techniques/Antiflow).**
- **No se deben usar [spinner traps](/wiki/Gameplay/Spinner_trap).**
- **Los [combos](/wiki/Beatmapping/Combo) no deben exceder las 12 [frutas](/wiki/Gameplay/Hit_object/Fruit).**
- **La densidad de las notas debe seguir principalmente un patrón de 1/2 y 1/3.** Los patrones de 1/4 y/o 1/6 deben usarse con moderación.

#### Pautas para la configuración de la dificultad

- La [velocidad de aproximación](/wiki/Beatmap/Approach_rate) y la [dificultad general](/wiki/Beatmap/Overall_difficulty) deberían ser iguales o menores a 8.
- La [tasa de drenaje de HP](/wiki/Beatmap/HP_drain_rate) debería ser entre 4 y 5.
- El [tamaño del círculo](/wiki/Beatmap/Circle_size) debería ser igual o menor a 3,5.

### ![](/wiki/shared/diff/insane-c.png?20211215) Rain

#### Reglas

- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) y [dashes](/wiki/Gameplay/Dash) deben tener al menos un espacio de 62 ms entre sus dos objetos.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^rain-basic-hyperdash] no deben usarse más de cuatro veces entre [frutas](/wiki/Gameplay/Hit_object/Fruit) consecutivas.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^rain-basic-hyperdash] no deben usarse más de dos veces dentro de un slider.** La trayectoria del slider debe ser simple y fácil de seguir.
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^rain-higher-hyperdash] no deben usarse junto con ningún otro hiperdash.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^rain-higher-hyperdash] no deben usarse dentro de un slider.**
- **Debe haber al menos 125 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el inicio y final de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**

#### Pautas

- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) no deben usarse en [gotas](/wiki/Gameplay/Hit_object/Juice_stream#gota) y/o repeticiones de sliders.**
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap básico](/wiki/Gameplay/Dash_snapping#snap-básico)[^rain-basic-hyperdash] no deben usarse consecutivamente cuando se usan ritmos diferentes.** Por ejemplo, un hiperdash de 1/1 seguido de un hiperdash de 1/2.
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^rain-higher-hyperdash] no deben usarse junto con [dashes](/wiki/Gameplay/Dash) de snap alto[^rain-higher-dash].** Si se usan, estos no pueden involucrar [antiflow](/wiki/Beatmapping/Mapping_techniques/Antiflow) y el dash debe usarse antes del hiperdash.
- **Los [hiperdashes](/wiki/Gameplay/Hyperdash) de [snap alto](/wiki/Gameplay/Dash_snapping#snap-alto)[^rain-higher-hyperdash] no deberían ir seguidos de [dashes](/wiki/Gameplay/Dash) [antiflow](/wiki/Beatmapping/Mapping_techniques/Antiflow).**
- **Los [edge dashes](/wiki/Gameplay/Edge_dash) solo se pueden usar de forma singular (no en conjunto con otros [dashes](/wiki/Gameplay/Dash) o [hiperdashes](/wiki/Gameplay/Hyperdash)).**
- **No se deben usar [spinner traps](/wiki/Gameplay/Spinner_trap).**
- **La densidad de las notas debe seguir principalmente un patrón de 1/2 + 1/4 y/o 1/3 + 1/6.** Los patrones de 1/8 y superiores deben usarse con moderación.

#### Pautas para la configuración de la dificultad

- La [velocidad de aproximación](/wiki/Beatmap/Approach_rate) y la [dificultad general](/wiki/Beatmap/Overall_difficulty) deberían ser iguales o menores a 9.
- La [tasa de drenaje de HP](/wiki/Beatmap/HP_drain_rate) debería ser entre 5 y 6.
- El [tamaño del círculo](/wiki/Beatmap/Circle_size) debería ser igual o menor a 4.

### ![](/wiki/shared/diff/expert-c.png?20211215) Overdose

#### Reglas

- **Debe haber al menos 62 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el inicio de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**
- **Debe haber al menos 125 ms de espacio entre [frutas](/wiki/Gameplay/Hit_object/Fruit) y el final de los [spinners](/wiki/Gameplay/Hit_object/Spinner).**

#### Pautas

- **Los [edge dashes](/wiki/Gameplay/Edge_dash) no deberían usarse después de [hiperdashes](/wiki/Gameplay/Hyperdash).**

#### Pautas para la configuración de la dificultad

- La [velocidad de aproximación](/wiki/Beatmap/Approach_rate) y la [dificultad general](/wiki/Beatmap/Overall_difficulty) deberían ser iguales o mayores a 9.
- La [tasa de drenaje de HP](/wiki/Beatmap/HP_drain_rate) debería ser igual o mayor a 5.
- El [tamaño del círculo](/wiki/Beatmap/Circle_size) debería ser igual o mayor a 4.

## Notas

[^proper-spread]: Una distribución «adecuada» *para las dificultades Rain y superiores* se define como una distribución con intervalos de dificultad similares a los existentes entre los [niveles de dificultad](/wiki/Beatmap/Difficulty#niveles-de-dificultad) inferiores, tal y como se especifica en los [criterios específicos de las dificultades](#dificultades-específicas).
[^salad-basic-dash]: En una Salad, un dash de snap básico tiene un espacio de 250 ms o más.
[^salad-higher-dash]: En una Salad, un dash de snap alto tiene un espacio entre 125 y 249 ms.
[^platter-basic-dash]: En una Platter, un dash de snap básico tiene un espacio de 125 ms o más.
[^platter-higher-dash]: En una Platter, un dash de snap alto tiene un espacio entre 62 y 124 ms.
[^platter-basic-hyperdash]: En una Platter, un hiperdash de snap básico tiene un espacio de 250 ms o más.
[^platter-higher-hyperdash]: En una Platter, un hiperdash de snap alto tiene un espacio entre 125 y 249 ms.
[^rain-higher-dash]: En una Rain, un dash de snap alto tiene un espacio entre 62 y 124 ms.
[^rain-basic-hyperdash]: En una Rain, un hiperdash de snap básico tiene un espacio de 125 ms o más.
[^rain-higher-hyperdash]: En una Rain, un hiperdash de snap alto tiene un espacio entre 62 y 124 ms.
