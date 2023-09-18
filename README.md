# Realizar un programa que sea capaz de revisar el estado de tu aplicación
Materia: Computación Tolerante a Fallas<br>
Maestro: MICHEL EMANUEL LOPEZ FRANCO<br>
Nombre: Diego Alonso Mercado Brizuela<br>
Carrera: Ingeniería en Computación<br>
Código: 215425636<br>
Fecha: 18/09/2023<br>
Sección: D06<br>

## Introducción
Todo sistema operativo basa su funcionamiento en una correcta ejecución de los procesos que lo componen. Estos procesos corresponden, entre otras cosas, a las aplicaciones que en cada momento ejecuta el usuario. Sin embargo, además de los asociados al navegador o al juego de turno, nos encontramos con otros llamados "de sistema", que sostienen el funcionamiento general de Windows.
## Pruebas
En esta práctica se valida si los programas enviados como parámetros no estén activos en windows, si lo están se cierra.
<br>
<img
src="https://github.com/Diego3207/estatus/blob/main/Evidencia%201.png">
<br>
Se descarga esta herramienta non-sucking service manager como ayuda para crear servicios en Windows, se copia el archivo del script en el programa, abrimos el programa con la consola.
<img
src="https://github.com/Diego3207/estatus/blob/main/Evid
encia%202.png">
<br>
<img
src="https://github.com/Diego3207/estatus/blob/main/Evidencia%203.png">
<br>
Y lo que hace es que, si teníamos ventanas de Chrome abiertas, las cierra, y si
queremos abrir más, no nos deja, esto porque se ejecuta continuamente.
# Conclusiones
Un servicio en segundo plano puede ayudar a validar tareas sin que el usuario tenga que ejecutarlos o para ayudar al programador a tener tareas secundarias pequeñas para ayudar al programa principal, esto aplicado a la tolerancia a fallas podría ser crucial para evitar fallas.
