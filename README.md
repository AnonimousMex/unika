# UNIKA

Página web y prototipo del sistema de operación de UNIKA Tacos & Cortes Selectos, Morelia.

## Ejecutar en local

Requiere Python 3. Desde esta carpeta:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

- Página web: http://localhost:8080/reservas.html
- Sistema: http://localhost:8080/index.html
- Comandas por tiempos: http://localhost:8080/unika.html

## Archivos

- `reservas.html`: página pública, carta y demostración de reservas.
- `index.html`: gestión de mesas y rondas.
- `unika.html`: comandas por tiempos y demostración de cocina.
- `assets/`: estilos e imagen de portada.

## Estado

Prototipo con datos de demostración. Aún no cuenta con base de datos persistente, autenticación, sincronización entre dispositivos ni integración con WhatsApp. Las reservas y órdenes de demostración no constituyen operaciones reales.

La fotografía de portada es ilustrativa y proviene de Unsplash:
https://images.unsplash.com/photo-1544025162-d76694265947
