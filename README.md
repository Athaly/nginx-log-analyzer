# Nginx Log Analyzer

Script en Bash que analiza un archivo de logs de acceso de Nginx.  
Proyecto original: https://roadmap.sh/projects/nginx-log-analyser

## Descripción

Este script permite obtener un resumen rápido del tráfico web registrado en los logs de Nginx, útil para tareas básicas de análisis.

## Funcionalidad

El script muestra:

- Top 5 direcciones IP con más solicitudes
- Top 5 rutas (paths) más solicitadas
- Top 5 códigos de estado HTTP
- Top 5 User Agents más comunes

## Uso

```bash
chmod +x nginx-log-analyzer.sh
./nginx-log-analyzer.sh
```
