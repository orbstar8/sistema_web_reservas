# Template taller de software 

## Descripción de carpetas 

|Carpeta|Descripción|
|:----:|:---------:|
|src| Código fuente del proyecto|
|informes| Informes del proyecto|
|docker| Archivo Dockerfile que permite correr el proyecto|

## Ejemplo de como ejecutar docker

```bash
docker build -t srcdocker -f docker/Dockerfile .
docker run -p 80:8080 srcdocker
```
