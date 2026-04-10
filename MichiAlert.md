# MichiAlert - Sistema de Alimentación Inteligente para Gatos

## Descripción general
MichiAlert es un sistema que detecta cuando un gato se acerca a su plato de comida y notifica al dueño si el plato está vacío. Usa un sensor de movimiento para saber si el gato está cerca y un sensor de peso para verificar si queda comida en el plato. Si el gato llega y no hay comida, se enciende una luz roja y suena una alerta para que el dueño lo sepa. Si hay comida, se enciende una luz verde indicando que todo está bien.

## Salidas
- LED verde: indica que hay comida en el plato. Señal digital.
- LED rojo: indica que el plato está vacío. Señal digital.
- Buzzer: emite una alerta cuando el gato llega y el plato está vacío. Señal PWM.