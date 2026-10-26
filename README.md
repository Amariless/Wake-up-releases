# Wake up

App de Android que junta en un solo lugar tu **agenda escolar** y un **reloj con alarmas** pensadas para que de verdad te despiertes.

> Este repositorio solo contiene las **descargas** (APK) y las notas de cada versión.

## ⬇️ Descargar

**[Descargar la última versión (wake-up.apk)](https://github.com/Amariless/Wake-up-releases/releases/latest/download/wake-up.apk)**

También puedes ver todas las versiones en [Releases](https://github.com/Amariless/Wake-up-releases/releases).

### Cómo instalarla

1. Descarga el `.apk` desde tu celular y ábrelo.
2. Android te pedirá permitir **"Instalar apps desconocidas"** para el navegador o gestor de archivos que usaste. Es normal: la app no está en Play Store.
3. Si Google Play Protect muestra un aviso de "app no verificada", elige **Instalar de todos modos**.
4. Las siguientes versiones se instalan desde la propia app: **Ajustes → Buscar actualizaciones**. Se instalan encima de la anterior y **no borran tus datos**.

Requiere **Android 8.0 o superior**.

## ¿Qué hace?

- **Carpetas** (semestres o lo que quieras) con **materias**, horarios por día y salón, y **tareas** con fecha de vencimiento y recordatorios (1 semana y 1 día antes, y un aviso extra justo cuando vence).
- **Reloj**: alarmas generales y por carpeta, temporizador y cronómetro.
- **Retos para apagar la alarma**: agitar el celular, resolver una cuenta, conectar puntos en orden, seguir una línea curva o escribir una frase. Así no la apagas dormido.
- **Aviso una hora antes** de cada alarma, con botón para apagarla solo esa vez.
- **Terminar un semestre**: desactiva todas sus alarmas y recordatorios de un toque, sin borrar el historial.
- **Widgets** de pantalla de inicio: próximas clases y próximas tareas (agrupadas en Vencidas, Hoy, Mañana…).
- **Tiempo de pantalla** por app, con avisos configurables (por ejemplo, "llevas 90 min en redes sociales").
- **Bloqueo de contenido**: limita los minutos diarios de Reels de Instagram / TikTok sin tocar los mensajes directos.

## 🔐 Permisos: qué pide y para qué

La app tiene un asistente en **Ajustes → Permisos** que te guía por cada uno. Solo los marcados como *necesarios* afectan a las alarmas; el resto activa funciones concretas y puedes ignorarlos si no las usas.

| Permiso | ¿Es necesario? | Para qué se usa |
|---|---|---|
| **Notificaciones** | Sí | Avisos de alarma, de tareas por vencer y de tiempo de pantalla. |
| **Alarmas y recordatorios exactos** | Sí | Que las alarmas y los avisos de tareas suenen a la hora exacta, no minutos después. |
| **Notificaciones a pantalla completa** | Sí | Que la alarma aparezca sobre la pantalla bloqueada cuando suena. |
| **Ignorar optimización de batería** | Muy recomendado | Evita que el sistema "duerma" o cierre la app y se pierdan alarmas. |
| **Inicio automático** (Xiaomi / MIUI / HyperOS) | Muy recomendado en Xiaomi | Que las alarmas se reprogramen solas después de reiniciar el celular. |
| **Ventanas emergentes en segundo plano** (Xiaomi) | Muy recomendado en Xiaomi | Que la pantalla de la alarma se reabra sola si la mandas a segundo plano sin apagarla. |
| **Mostrar sobre otras apps** | Solo para el bloqueo de contenido | Dibujar el aviso de "límite diario alcanzado" encima de Instagram/TikTok. |
| **Acceso a datos de uso** | Solo para tiempo de pantalla | Medir cuánto usas cada app. Se concede desde Ajustes de Android. |
| **Ver lista de apps instaladas** | Solo para tiempo de pantalla | Mostrar el nombre y el ícono de cada app en las estadísticas. |
| **Servicio de accesibilidad** | **No es obligatorio** | Detectar cuándo estás en Reels / TikTok para avisarte o bloquear al llegar a tu límite. **Solo se necesita para el bloqueo de contenido y los avisos de "llevas X min en…".** |
| **Internet** | Solo para actualizar | Consultar si hay una versión nueva y descargarla desde este repositorio. |
| **Instalar paquetes** | Solo para actualizar | Abrir el instalador de Android con el APK descargado. |

Otros permisos menores (vibrar, mantener el celular despierto mientras suena la alarma, iniciar al encender el celular, servicios en primer plano) son los que Android exige para que una alarma funcione bien y no piden nada al usuario.

### ⚠️ Sobre el servicio de accesibilidad

- **Es opcional.** Si no lo activas, la app funciona completa: agenda, tareas, alarmas, retos, temporizador, widgets y tiempo de pantalla. Solo quedan desactivados el bloqueo de Reels/TikTok y los avisos de uso de redes.
- Es un permiso muy poderoso de Android, por eso se explica aquí: la app lo usa **únicamente** para saber qué pantalla de Instagram/TikTok estás viendo (si son Reels o no). **No lee mensajes ni contenido personal, y nunca toca la bandeja de mensajes directos.**
- Todo se procesa **en el celular**. La app no tiene servidor, no envía datos a nadie y no incluye analítica ni anuncios: el único uso de internet es consultar y descargar actualizaciones de este repositorio.
- Puedes revocarlo cuando quieras en **Ajustes de Android → Accesibilidad**.
- Como Google Play no permite este uso de accesibilidad, la app **no se publica en Play Store**; por eso se distribuye como APK.

### Nota para celulares Xiaomi / MIUI / HyperOS

Estos sistemas son especialmente agresivos cerrando apps en segundo plano. Si usas Xiaomi, activa **Inicio automático** y **Ventanas emergentes en segundo plano** (Seguridad → Permisos) y deja la batería de Wake up en **Sin restricciones**; si no, la alarma puede no sonar o no reabrirse sola.

## Actualizaciones

Cada versión nueva aparece aquí en [Releases](https://github.com/Amariless/Wake-up-releases/releases) con su `wake-up.apk`. Dentro de la app, **Ajustes → Buscar actualizaciones** revisa este repositorio, descarga la última versión y te deja instalarla con un toque. Todas las versiones están firmadas con la misma llave, así que se instalan encima de la anterior sin perder carpetas, tareas, alarmas ni ajustes.
