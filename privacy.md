# Política de Privacidad de RUNLVL

**Última actualización:** 14 de junio de 2026
**Desarrollador:** Alejandro Ortiz
**Contacto:** ortizyalzate@gmail.com

---

## 1. Información que recopilamos

### 1.1 Información de cuenta
- **Correo electrónico** — recopilado al registrarte con email/contraseña o Google Sign-In (gestionado por Firebase Authentication).

### 1.2 Datos de entrenamiento
- Plan de entrenamiento generado (semanas, sesiones, kilómetros objetivo).
- Historial de sesiones completadas: distancia, ritmo, tiempo y calificación de esfuerzo percibido (RPE).
- Puntos de experiencia (XP), nivel de corredor y logros desbloqueados.

### 1.3 Datos de ubicación
- **Ubicación precisa en primer plano** — únicamente durante sesiones GPS activas y con tu permiso explícito.
- Los datos de ruta se almacenan localmente en tu dispositivo y opcionalmente se sincronizan en tu cuenta de Firestore para restaurar el historial en nuevos dispositivos.
- Nunca compartimos tu ubicación con terceros.

### 1.4 Datos de uso y diagnóstico
- Información de fallos y rendimiento recopilada por Firebase Crashlytics y Firebase Analytics.
- Estos datos no se vinculan con tu identidad personal.

### 1.5 Datos del clima
- Condiciones climáticas de tu ubicación aproximada, consultadas a través de OpenWeatherMap únicamente cuando abres la pantalla de sesión activa.

---

## 2. Cómo usamos tu información

| Dato | Finalidad |
|------|-----------|
| Email | Autenticación y recuperación de contraseña |
| Plan y sesiones | Mostrar progreso, calcular métricas y adaptar el plan |
| GPS | Medir distancia y ritmo en tiempo real durante las sesiones |
| Crashlytics / Analytics | Detectar y corregir errores; mejorar la experiencia |
| Clima | Mostrarte condiciones ambientales antes de cada sesión |

---

## 3. Servicios de terceros

| Servicio | Propósito | Política de privacidad |
|----------|-----------|------------------------|
| Firebase Authentication | Inicio de sesión y gestión de cuenta | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Firebase Firestore | Sincronización del historial de entrenamiento | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Firebase Crashlytics | Reporte de errores y estabilidad | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Firebase Analytics | Métricas de uso de la app | [policies.google.com/privacy](https://policies.google.com/privacy) |
| OpenWeatherMap | Datos meteorológicos | [openweathermap.org/privacy-policy](https://openweathermap.org/privacy-policy) |

**No vendemos, rentamos ni cedemos tu información personal a ningún tercero.**

---

## 4. Almacenamiento y seguridad

- Los datos se almacenan en **Firebase Cloud Firestore** (Google Cloud).
- Toda la comunicación entre la app y los servidores se cifra mediante HTTPS/TLS.
- El acceso a Firestore requiere autenticación activa con Firebase Auth.
- Los archivos locales del dispositivo que contienen datos de sesión se excluyen de las copias de seguridad automáticas de Android para proteger tu privacidad.

---

## 5. Retención de datos

Conservamos tus datos mientras tengas una cuenta activa en RUNLVL. Si eliminas tu cuenta desde **Configuración → Eliminar cuenta**, suprimimos todos tus datos de Firestore en un plazo de 30 días.

---

## 6. Tus derechos

Puedes en cualquier momento:

- **Acceder** a tus datos de entrenamiento directamente desde la app.
- **Corregir** tu información desde la pantalla de Configuración.
- **Eliminar** tu cuenta y todos tus datos desde **Configuración → Eliminar cuenta**.
- **Contactarnos** en ortizyalzate@gmail.com para cualquier solicitud relacionada con tu privacidad.

---

## 7. Menores de edad

RUNLVL no está dirigido a personas menores de 13 años. No recopilamos conscientemente datos de menores. Si eres padre o tutor y crees que tu hijo ha proporcionado información personal, contáctanos para eliminarla de inmediato.

---

## 8. Cambios a esta política

Notificaremos cambios importantes a través de una notificación dentro de la app o por correo electrónico. El uso continuado de RUNLVL después de la notificación implica la aceptación de los cambios.
