# guia de istalacion de obs studio

## buscamos el programa
```bash
estudiante@conectarigualdad:~$ apt-cache search obs-studio
obs-studio - recorder and streamer for live video content
estudiante@conectarigualdad:~$ 
```

## instalamos
```bash
obs-studio - recorder and streamer for live video content
estudiante@conectarigualdad:~$ sudo apt install obs-studio
[sudo] password for estudiante:          
Sorry, try again.
[sudo] password for estudiante:           
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Tal vez quiera ejecutar «apt --fix-broken install» para corregirlo.
Los siguientes paquetes tienen dependencias incumplidas:
 code : Depende: libxkbfile1 (>= 1:1.1.0) pero 1:1.0.9-2+b11 va a ser instalado
 obs-studio : Depende: obs-plugins (= 22.0.3+dfsg1-1) pero no va a instalarse
              Depende: libobs0 (= 22.0.3+dfsg1-1) pero no va a instalarse
E: Dependencias incumplidas. Intente «apt --fix-broken install» sin paquetes (o especifique una solución).
estudiante@conectarigualdad:~$ ^C
estudiante@conectarigualdad:~$ apt --fix-broken
E: No tiene sentido la opción de línea de órdenes --fix-broken combinada con las otras opciones
estudiante@conectarigualdad:~$ sudo apt --fix-broken
E: No tiene sentido la opción de línea de órdenes --fix-broken combinada con las otras opciones
estudiante@conectarigualdad:~$ sudo apt --fix-broken install
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Corrigiendo dependencias... Listo
Los siguientes paquetes se ELIMINARÁN:
  code
0 actualizados, 0 nuevos se instalarán, 1 para eliminar y 398 no actualizados.
1 no instalados del todo o eliminados.
Se liberarán 419 MB después de esta operación.
¿Desea continuar? [S/n] s
(Leyendo la base de datos ... 303692 ficheros o directorios instalados actualmente.)
Desinstalando code (1.95.3-1731513102) ...
Procesando disparadores para mime-support (3.62) ...
Procesando disparadores para gnome-menus (3.31.4-3) ...
Procesando disparadores para shared-mime-info (1.10-1) ...
Procesando disparadores para desktop-file-utils (0.23-4) ...
estudiante@conectarigualdad:~$ 

```

## instalacion del programa
```bash
estudiante@conectarigualdad:~$ sudo apt install obs-studio
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Se instalarán los siguientes paquetes adicionales:
  libobs0 libxcb-xinput0 obs-plugins
Se instalarán los siguientes paquetes NUEVOS:
  libobs0 libxcb-xinput0 obs-plugins obs-studio
0 actualizados, 4 nuevos se instalarán, 0 para eliminar y 398 no actualizados.
Se necesita descargar 3.338 kB de archivos.
Se utilizarán 12,1 MB de espacio de disco adicional después de esta operación.
¿Desea continuar? [S/n] s

```