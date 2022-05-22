# Programa capaz de factorizar por MCM:

Este código esta compuesto de dos partes:
  1. Las variables asignadas, listas de números usados para factorizar.
  2. Los mensajes empleados para colocar el número que el usuario vaya a colocar.

El programa como bien dice el nombre factorizar por el Mínimo común Mútiplo(MCM), pero el lugar de realizar el gráfico,
este solamente mostrara al usuario los números primos los cuales se emplearon para la factorización del número.

# Errores solucionados:
  •	El usuario al colocar el número 1 el programa terminaba sin más que decir.(Solución: Ahora el programa manda un mensaje
    diciendo que no existe números primos que dividan a 1, y vualve a pedir otro número).
    
  •	El usuario al colocar el número 0 el programa no continuaba como debería.(Solución: El programa ahora recuerda al usuario 
    que el número debe ser mayor a 1).
    
  •	El usuario al poner cualquier carácter que no sea un número el programa mandaba un error.(Solución: Se creo una excepción
    error de valor, mandando un mensaje diciendo que el número ingresado debe ser uno entero).
