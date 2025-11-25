# Propuesta de Sintaxis para DuckScript

## Palabras Clave Principales
- `iniciar`: para comenzar una nueva función.
- `fin`: para terminar una función.
- `si`: para una sentencia condicional.
- `mientras`: para bucles.

## Reglas de Asignación
- Utiliza el símbolo `=` para asignar valores a las variables.
- Ejemplo de asignación: `x = 5`

## Ejemplo Sencillo
```
función ejemplo() {
    x = 5
    si (x > 3) {
        imprimir("X es mayor que 3")
    } 
}
```

## Sintaxis Explicada
- `función ejemplo()`: empieza la definición de una función llamada "ejemplo".
- `x = 5`: asigna el valor 5 a la variable `x`.
- `si (x > 3)`: verifica si `x` es mayor que 3.
- `{...}`: contiene el bloque de código que se ejecuta si la condición es verdadera.
- `imprimir(...)`: función para mostrar mensajes en la consola.

Esta propuesta busca establecer una sintaxis clara y concisa para el lenguaje DuckScript, facilitando su aprendizaje y uso.