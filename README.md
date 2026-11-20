# SEES Training Archive — Android

Proyecto Android nativo en Kotlin + Jetpack Compose.

## Requisitos
- Android Studio Ladybug o posterior
- JDK 17
- Android SDK 35
- Conexión a Internet durante la primera sincronización de Gradle

## Abrir y compilar
1. Descomprimí el ZIP.
2. Abrí la carpeta `SEESTrainingArchive` desde Android Studio.
3. Esperá la sincronización de Gradle.
4. Conectá un teléfono Android con depuración USB o creá un emulador.
5. Ejecutá `app`.

Para generar un APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
El APK de depuración suele quedar en `app/build/outputs/apk/debug/app-debug.apk`.

## Funciones incluidas en esta primera versión
- Navegación inferior: Status, Plan, Calendar, Database y Profile.
- Registro de sesiones con categoría, notas y duración.
- XP, niveles y rangos F–S.
- Social Stats de fuerza, resistencia, movilidad y disciplina.
- Gráfico de sesiones de los últimos siete días.
- Logros básicos desbloqueables por hitos de sesiones.
- Misiones diarias con checklist (estado temporal durante la sesión de app).
- Calendario mensual con días de actividad.
- Base inicial de ejercicios con buscador.
- Perfil con nombre y selección de avatar simbólico.
- Recordatorio periódico mediante WorkManager y canal de notificaciones.
- Persistencia local de sesiones con Room.

## Próximas mejoras recomendadas
- Persistir misiones y logros en Room.
- Editor completo de rutinas y ejercicios por series/repeticiones.
- Misiones diarias/semanales persistentes y logros desbloqueables.
- Gráficos históricos con filtros por semana/mes.
- Selector de hora y días para recordatorios.
- Exportación y copia de seguridad de datos.
- Icono, splash screen y pruebas en dispositivos reales.

## Nota
Este es un proyecto inicial funcional para abrir y compilar en Android Studio; no incluye todavía un APK firmado para distribución. La rutina incluida es una plantilla general: adaptá ejercicios e intensidad a tu experiencia y priorizá la técnica, el descanso y el bienestar.
