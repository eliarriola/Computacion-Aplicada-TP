# Computacion-Aplicada-TP
Trabajo Practico Computacion Aplicada
Integrantes:
Grupo N° 10:
⦁	Ruth Arriola
⦁	Lucas Antuña
⦁	Agustin Javier Bricchi
⦁	Mario Durand

## ACLARACION ##

No se pudo comprimir directorio /proc, se creo un directorio llamado particiones, en su defecto.
Se busco los motivos por el cual no se pudo comprimir /proc y se encontro lo siguiente:

- /proc no es un directorio "real" en el disco; es un sistema de archivos virtual que representa información del kernel y procesos en tiempo real.

- Muchos de sus archivos son dinámicos y no legibles por herramientas de archivo como tar.

- Intentar acceder a ciertos archivos de /proc puede resultar en errores como Input/output error o tar: read error.
