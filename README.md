# Biblioteca Operativa - Datos Remotos

Este repositorio contiene unicamente los archivos remotos de la biblioteca operativa.

La aplicacion puede consultar estos archivos desde GitHub y conservar una copia local como respaldo si no hay conexion o si GitHub no responde.

## Estructura

```text
data/
  biblioteca_catalogos.json

assets/
  FIC-AH-01.html
  FIC-CR-01.html
  FIC-GC-2025_01.html
  FIC-MC-01.html
  FIC-VH-01.html
  INS.html
  PRO-GC-2025-05.html
  app.qss
  check_white.svg
```

## Uso recomendado

1. La aplicacion consulta `version.json`.
2. Si hay una version nueva, descarga `data/biblioteca_catalogos.json`.
3. Luego descarga o usa los archivos referenciados dentro de `assets/`.
4. Si GitHub falla, se usa la copia local existente.

## Nota

Los archivos de bancos, cheques, libretas, logs y estados locales no forman parte de este repositorio.
