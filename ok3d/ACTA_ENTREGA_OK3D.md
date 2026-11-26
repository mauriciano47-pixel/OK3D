# Acta de Entrega y Conformidad Técnica — Proyecto Web OK3D

**Cliente:** OK3D — 3D Imprimiendo Soluciones (+56 9 6895 9553)
**Desarrollador:** Mauricio Uribe Maldonado
**Versión Entregada:** 1.0.0

## 1. Alcance y Módulos Entregados
1. **Sitio Web Oficial & Catálogo 3D:** 20 productos oficiales pre-renderizados con fotografías optimizadas, buscador instantáneo, filtro por categorías y carrito de compras en CLP.
2. **Sistema de Concurso por Números (#001 al #100):** Tablero interactivo con reserva de lugares, selección manual o aleatoria y acreditación automática con código verificador único (`OK3D-XXXX-###`).
3. **Integración de Pasarela de Pago (Flow.cl / Mercado Pago Chile):** Flujo de cobro en CLP y validación de Webhook (`server_webhook_mailer.mjs`).
4. **Motor de Notificaciones por Correo Electrónico:** Envío automático de comprobante/boleto acreditado al comprador y alerta de venta interna a la administración de OK3D.
5. **Enlace Directo con WhatsApp Business (+56 9 6895 9553):** Deep-links configurados para atención personalizada y respaldo de boletos.

## 2. Propiedad de Credenciales
- Las cuentas de pasarela de pago (Flow.cl / Mercado Pago) y cuenta bancaria receptora están registradas directamente bajo el RUT del titular de OK3D.
- Las credenciales técnicas (`SMTP_PASS`, `API_KEY`, `SECRET_KEY`) operan mediante variables de entorno privadas (`.env`).

## 3. Garantía y Soporte Post-Entrega
- **Garantía Técnica:** 30 días corridos a partir de la firma/aceptación de la presente acta para corrección sin costo de cualquier error funcional sobre los módulos descritos en el punto 1.
- **Nuevos Requerimientos y Mantención:** La carga de nuevos catálogos, reinicio de tableros para futuros concursos o desarrollo de nuevas funciones se gestionará mediante Plan de Mantención Mensual o cotización evolutiva independiente.
