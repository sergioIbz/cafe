### Ejercicio: Simulación de Máquina Expendedora de Café

#### Descripción del Ejercicio:
Desarrolla una aplicación en Java que simule el comportamiento de una máquina expendedora de café. La máquina debe ofrecer diferentes tipos de café y utilizar distintos ingredientes (agua, café y leche) en diferentes proporciones según el tipo de bebida seleccionada. Cada bebida tendrá un costo asociado. Los contenedores de agua, café y leche se irán vaciando conforme se vayan preparando las bebidas y deberán rellenarse si alguno de ellos se queda sin suficiente contenido para la preparación.

#### Requisitos:
1. **Tipos de Bebidas**: La máquina debe ofrecer al menos cuatro tipos de bebidas:
    - Espresso: 50 ml de agua, 18 g de café.
    - Americano: 100 ml de agua, 18 g de café.
    - Latte: 100 ml de agua, 18 g de café, 150 ml de leche.
    - Capuchino: 100 ml de agua, 18 g de café, 100 ml de leche.

2. **Ingredientes**: La máquina debe tener contenedores con capacidad inicial para:
    - Agua: 1000 ml
    - Café: 500 g
    - Leche: 500 ml

3. **Interfaz de Usuario**:
    - Mostrar las opciones de bebidas disponibles y sus precios.
    - Permitir al usuario seleccionar una bebida.
    - Indicar si no hay suficiente de algún ingrediente y solicitar el rellenado del contenedor correspondiente antes de continuar.

4. **Funciones Adicionales**:
    - Mostrar la cantidad actual de cada ingrediente después de cada transacción.
    - Permitir rellenar los contenedores de agua, café y leche.
    - Registrar el número de bebidas vendidas y la cantidad de dinero recaudado.
    - Mostrar la cantidad de cada ingrediente utilizado y el total de dinero recaudado desde el inicio de la simulación.

#### Ejemplo de Interacción:
```
Bienvenido a la Máquina Expendedora de Café!
Opciones de bebidas:
1. Espresso - $1.50
2. Americano - $2.00
3. Latte - $2.50
4. Capuchino - $3.00

Seleccione una bebida (1-4):
1
Preparando un Espresso...
Ingredientes actuales:
Agua: 950 ml
Café: 482 g
Leche: 500 ml
Bebida preparada. Precio: $1.50

Opciones:
1. Seleccionar otra bebida
2. Rellenar ingredientes
3. Mostrar estado de ingredientes
4. Mostrar total de ventas, ingredientes utilizados y dinero recaudado
5. Salir

Seleccione una opción (1-5):
4
Total de ventas: 1
Dinero recaudado: $1.50
Ingredientes utilizados:
Agua: 50 ml
Café: 18 g
Leche: 0 ml

Opciones:
1. Seleccionar otra bebida
2. Rellenar ingredientes
3. Mostrar estado de ingredientes
4. Mostrar total de ventas, ingredientes utilizados y dinero recaudado
5. Salir
```

#### Requerimientos Técnicos:
1. **Clase `MaquinaExpendedoraCafe`**:
    - Atributos para almacenar la cantidad de agua, café y leche disponibles.
    - Atributos para registrar las estadísticas de ventas (bebidas vendidas, dinero recaudado, y cantidad de ingredientes utilizados).
    - Métodos para:
        - Mostrar opciones de bebidas y sus precios.
        - Seleccionar una bebida y verificar si hay suficientes ingredientes.
        - Actualizar los contenedores de ingredientes y las estadísticas de ventas.
        - Rellenar los contenedores de ingredientes.
        - Mostrar el estado actual de los ingredientes.
        - Mostrar el total de ventas, ingredientes utilizados y dinero recaudado.

2. **Clase `Main`**:
    - Método `main` para gestionar la interacción con el usuario y permitir la selección de opciones.

#### Consideraciones:
- Validar la entrada del usuario para evitar errores.
- Asegurarse de que los contenedores no se queden con cantidades negativas.
- Implementar un sistema sencillo de menú que permita al usuario navegar entre las diferentes opciones del sistema.

Con este ejercicio, el estudiante podrá practicar la programación orientada a objetos, el manejo de entradas y salidas, y la gestión de estado de un sistema en Java.
