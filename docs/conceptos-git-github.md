# Comprobacion conceptual

## ¿Qué puede hacer Git aunque Github no exista?

--Git permite tener el control de versiones de un proyecto.
--GitHub es donde nos permite tener el proyecto en un alojamiento remoto.

## ¿Por qué una rama reduce el riesgo de dañar main?
--Permite saber que cambios realizo cada coloborador en que afectaria al main y comprobar si funciona ,en caso que no , se haria un descartado a esa rama hasta que se corriga.

## ¿Que diferencia existe entre guardar un archivo y crear un commit?
--El commit es una captura  de los cambios realizado a un archivo.
--El guardar un archivo es no tener un registro de cambios. Si no solo la creacion o modificacion de un archivo local.

## ¿Por qué un pull request no es lo mismo que un merge?
--EL pull reques es una solicitud para revisar si se une un rama a la otra o al main directamente 
-- A difrencia Merge une las ramas sin una autorizacion previa.

## ¿Que evidencia permite saber quien cambio algo y porque?
--El git log Muestra en detalle el registro de los ultimos commits subidos y quien fue su autor.
--Los pull request que solicita los demas colaboradores al autor.



## FLUJO DE SECUENCIA 
1. Crea el repositorio :Es el primer paso ya que permite alamcenar el proyecto,llevar un control de versiones y mantener un historial  de todos los cambios  historial realizados.
2. Crear rama : Se crea una rama para aislar el desarrollo de nuevas funcionalidades o correciones sin afectar la rama principal.
Esto facilita el trabajo y reduce el riesgo de errores en la version estable.
3. Hacer commit:Primero agregamos los archivos al área de preparación con git add. 
Luego,se crea un commit con un mensaje descriptivo que explique se realizo.
4. Crear un pull request:Se crea para solicitar que el codigo sea revisado.
5. Revisar el codigo: Se revisa el pull y se dice si se aprueba y fusiona o pasa a una fase de correcion o mejora del codigo.
6. Corregir observaciones: Si durante la revisión se detectan errores o se solicitan mejoras, se realizan las correcciones necesarias en la misma rama. Una vez actualizados los cambios, estos se revisan nuevamente antes de su integración definitiva.
7. Fusionar:Se fusiona con la rama main cuando ya se apruebe el pull request,esto con el fin de tener un mejor control del MAIN.