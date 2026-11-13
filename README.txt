# hoy. — agenda personal

Prototipo funcional de agenda minimalista para iPhone.

## Incluye
- Vista HOY con tareas simples.
- Marcar tareas como urgentes con banderita bordó.
- Marcar como listo y consultar completadas.
- Editar y eliminar tareas.
- Asignar fecha y hora; los eventos con horario aparecen en SEMANA.
- Vista semanal vertical, de lunes a domingo.
- Datos guardados localmente en el navegador mediante localStorage.

## Importante para iPhone
El archivo funciona como sitio web local, pero iOS no permite instalar una web app desde un archivo HTML local en la pantalla de inicio con funcionamiento PWA completo. Para agregarla como app y habilitar el modo offline, necesita servirse una primera vez desde una dirección HTTPS (puede ser un hosting estático gratuito; no requiere Railway ni backend). Una vez instalada y cargada, las tareas quedan guardadas en el almacenamiento local de Safari en ese iPhone.

Para probar el prototipo en una computadora, abrí `index.html` en un navegador. Para probar en iPhone, se necesita servir la carpeta por HTTPS.
