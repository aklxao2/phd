# Modelos descriptivos basados en aprendizaje supervisado para el tratamiento de big data y flujos continuos de datos.

En este repositorio se almacenan los fichero fuente de LaTeX necesarios para poder compilar mi tesis doctoral. Debido a problemas de Copyright, no se muestran los artículos presentados en la tesis, sino únicamente la referencia a dicho trabajo.

## Cómo compilar la tesis.

En el repositorio tenemos un fichero Makefile que nos facilitará la compilación del documento. Para poder utilizarlo, necesitaremos tener instalado en nuestro sistema:
+ XeLaTeX
+ Biber
+ GhostScript (opcional, sirve para la compresión del PDF)

Las opciones del fichero Makefile son las siguientes:

```
make build      # Para compilar el pdf desde el fichero fuente
make compress   # Opcional, para comprimir el pdf
make clean      # Opcional, para eliminar los ficheros auxiliares generados por LaTeX
```
