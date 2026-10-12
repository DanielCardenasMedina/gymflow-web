# GYMFlow — Gestión integral del gimnasio

Prototipo web responsive creado a partir de los documentos académicos adjuntos de Arquitectura de Tecnologías de la Información (Evidencia 2, AA2 y Evidencia 3).

## Cómo abrirlo
1. Descarga y descomprime `GYMFlow_Web.zip`.
2. Abre la carpeta `gym-web`.
3. Haz doble clic en `index.html` para abrirlo en tu navegador.
4. Para editar el proyecto, abre la carpeta en Visual Studio Code.

No requiere instalar dependencias ni ejecutar un servidor para la demostración estática.

## Contenido
- `index.html`: estructura y secciones de la página.
- `styles.css`: estilos responsive y diseño visual.
- `app.js`: filtros, clases, suscripciones, formularios y panel administrativo demostrativo.

## Funciones de demostración
- Filtrar y buscar clases.
- Visualizar suscripciones con precios de ejemplo.
- Registrar solicitudes de suscripción e inscripción.
- Abrir un panel administrativo y añadir/eliminar clases.
- Consultar solicitudes y pagos simulados.
- Los datos se guardan en el `localStorage` del navegador.

## Importante: límites del prototipo
Este es un **frontend demostrativo**, no un sistema de producción. No tiene backend, base de datos cloud, autenticación real, gestión de permisos segura ni pasarela de pago conectada. Los precios, las clases y los horarios son datos de ejemplo porque los documentos no fijan un tarifario ni un catálogo definitivo. Las solicitudes y los pagos son simulados y permanecen solamente en el navegador donde se registran.

## Arquitectura descrita en la Evidencia 3
La interfaz representa la propuesta de arquitectura: Amazon S3 + CloudFront para frontend, API Gateway, Cognito, AWS Lambda (Node.js), DynamoDB, EventBridge, CloudWatch y un servicio externo de pagos aún por seleccionar. Esos servicios no están desplegados ni conectados en este ZIP.
