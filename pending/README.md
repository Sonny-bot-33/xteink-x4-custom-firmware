# Pendientes backend

Archivo base consumido por la app Pendientes del firmware custom Xteink X4.

## Archivo principal

- `tasks.json`

## Formato

```json
{
  "date": "2026-05-21",
  "tasks": [
    {
      "id": "agua",
      "title": "Beber agua",
      "completed": false
    }
  ]
}
```

## Notas

- `id` debe ser estable para que el progreso local del dispositivo siga encajando.
- `title` es el texto visible en la pantalla.
- `completed` puede ir a `false` normalmente; el dispositivo sobreescribe estado localmente.
