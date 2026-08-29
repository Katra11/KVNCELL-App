# KVNCELL Servicio Técnico

Proyecto base Android (Kotlin + Jetpack Compose) preparado para conectar con Firebase o Supabase.

## Módulos
- Inicio / Dashboard
- Clientes
- Órdenes de reparación
- Fotos por orden
- Inventario
- Finanzas
- Usuarios y roles
- Acceso rápido a WhatsApp

## Arquitectura
UI -> ViewModel -> Repository -> DataSource
La capa Repository permite cambiar entre Firebase y Supabase sin rehacer la interfaz.

## Configuración
1. Abrir en Android Studio.
2. Crear proyecto Android y agregar el contenido de `app/`.
3. Elegir backend: Firebase o Supabase.
4. Completar las variables en `BackendConfig.kt`.
5. Implementar el DataSource correspondiente.
6. Configurar autenticación, base de datos/storage y reglas de seguridad.
7. Ejecutar y generar APK.

Este paquete es un esqueleto funcional/arquitectónico; no contiene credenciales ni un backend real.
