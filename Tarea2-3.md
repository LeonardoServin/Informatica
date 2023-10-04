# PSEUDOCÓDIGO

El pseudocóigo es una manera clara y legible de representar algoritmos sin estar vinculado a un lenguaje de programación específico.
Este código es simple, pero sirve para poder entender qué es un proceso y un subproceso:

```

Proceso SumarNumeros
  Definir numero1, numero2, suma Como Real

  Escribir "Ingrese el primer número: "
  Leer numero1

  Escribir "Ingrese el segundo número: "
  Leer numero2

  suma <- numero1 + numero2

  Escribir "La suma es: ", suma
FinProceso

Proceso RestarNumeros
  Definir numero1, numero2, resta Como Real

  Escribir "Ingrese el primer número: "
  Leer numero1

  Escribir "Ingrese el segundo número: "
  Leer numero2

  resta <- numero1 - numero2

  Escribir "La resta es: ", resta
FinProceso

Inicio
  Escribir "Seleccione una operación:"
  Escribir "1. Sumar números"
  Escribir "2. Restar números"
  Leer opcion

  Si opcion = 1 Entonces
    Call SumarNumeros
  Sino
    Si opcion = 2 Entonces
      Call RestarNumeros
    Sino
      Escribir "Opción no válida"
    FinSi
  FinSi
Fin

```

En este ejemplo:

Hemos definido dos procesos (SumarNumeros y RestarNumeros) que realizan la suma y resta de dos números ingresados por el usuario.

En el programa principal (Inicio), el usuario selecciona una operación para sumar o restar números. Luego, se llama al proceso correspondiente utilizando la instrucción Call.

Este pseudocódigo utiliza procesos y subprocesos para organizar la lógica de las operaciones matemáticas y mejorar la legibilidad del código. Los procesos y subprocesos son una forma efectiva de dividir un programa en tareas más pequeñas y manejables.

> [*Continuar*](Tarea2-4.md)

> [*Volver*](Tarea2-2.md)
