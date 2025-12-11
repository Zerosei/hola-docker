# Hola Docker - Actividad 3.2

Aplicación web mínima para cumplir criterios h, i, g, j.

## Ejecutar localmente
```bash
docker build -t hola-docker .
docker run -d -p 8080:80 --name hola hola-docker