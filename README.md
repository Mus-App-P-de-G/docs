# docs

Documentación técnica y no técnica

## Stack

1. Ahora mismo se está haciendo una REST API en **Elixir** (por que mola xd) que interactua con una base de datos **PostreSQL**. La idea es poder usar esta API para comunicarse con el back desde distintos front.

Dependencias de **Elixir** (están en el mix file pero bueno):
- 'dotenvy': Para gestionar cómodamente las variables de entorno
- 'plug_cowboy': Servidor HTTP
- 'ecto_sql': Interfaz de comunicación con bases de datos SQL
- 'postgrex': Plugin para 'ecto_sql' que gestiona la comunicación con bases de datos **PostgreSQL**

2. Mobile front: Supongo que la idea es hacerlo en **Kotlin** o **Dart** por que por lo general todos tenemos Android. Nos permitiría usarla a nosotros facilmente, que es el principal objetivo.

3. Web front: Habría que pensarlo, tampoco tiene que ser nada del otro mundo, pero nada de full stack, que ya tenemos un backend. No prioritario, daría mucha pereza tener que meterse al portatil para gestionar las partidas puf...

## Ideas

El objetivo de este apartado es escribir las ideas sobre la funcionalidad de la app, las cosas que queremos que haga y como queremos que las haga.

- Guardar partidas de Mus
    - Pareja de jugadores
    - Puntuación final
    - Guardar hórdagos (por los jajas)
    - ...
- Ver estadisticas de juego
    - Winrate
    - Puntos medios
    - Info sobre hórdagos
    - Mejores parejas
    - ...
- Un contador de Mus para seguir la partida y facilitar el registro de partidas (la alternativa sería un formulario asqueroso que daría demasiado)
- Sistema de cuentas para registrar a los jugadores y crear las parejas facilmente (la cuenta no es posible crearla, el registro se realiza desde administración, no va a estar abierta al público)

## Cosas locas

En esta parte se incluyen las ideas locas que suenan horriblemente complicadas e innecesarias.

- Hacer un contador de Mus realista, que use piedras y amarracos, sincronizando 4 teléfonos (un teléfono de la pareja lleva las piedras y el otro los amarracos)