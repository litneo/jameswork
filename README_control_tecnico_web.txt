CONTROL TÉCNICO WEB V1.2

Abrir control_tecnico_web.html en navegador moderno. Para persistencia confiable en Android publicar en HTTPS siempre en mismo dominio. Requiere conexión para CDN Bootstrap y sql.js.

NUEVO: catálogo de servicios (nombre, categoría, precio editable, activo/inactivo), selector de servicio en órdenes, precarga de precio editable, migración automática desde V1.1 manteniendo clientes/trabajos cuando se usa el mismo origen del navegador. Trabajos previos sin servicio asociado deben seleccionarlo al editarlos. Precios históricos en órdenes no se actualizan al editar tarifa.

Datos SQLite en IndexedDB. Exportar respaldos periódicos. Borrar datos del sitio elimina la base local. Abrir mediante file:// puede limitar la persistencia por políticas del navegador; se recomienda HTTPS.
