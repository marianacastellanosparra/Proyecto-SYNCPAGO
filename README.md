# README - SYNCPAGO

## ⭐ Nombre del Proyecto

**SYNCPAGO**

---

## 📝 Descripción

SYNCPAGO es una plataforma web propuesta para la gestión integral de pagos de servicios y obligaciones financieras. La solución busca centralizar recibos, fechas de vencimiento y recordatorios automáticos para reducir olvidos, cargos por mora y complicaciones en el control de pagos.

---

## 🚩 Problemática

Muchas personas pierden el control de pagos recurrentes como:

- Agua
- Energía
- Internet
- Arriendo
- Televisión
- Suscripciones digitales

El seguimiento mediante notas físicas, agendas o aplicaciones generales suele ser ineficiente y aumenta el riesgo de retrasos, intereses adicionales y desorganización financiera.

SYNCPAGO propone consolidar esta información en una única plataforma que facilite la visualización, organización y el recordatorio oportuno de las obligaciones de pago.

---

## 🎯 Objetivo General

Desarrollar una plataforma web que permita gestionar recibos y pagos de servicios mediante recordatorios automáticos, calendarios y herramientas de organización financiera personal.

---

## 🎯 Objetivos Específicos

- Registrar y administrar recibos de servicios.
- Mostrar fechas de vencimiento de manera clara y ordenada.
- Generar recordatorios automáticos antes del vencimiento.
- Enviar notificaciones mediante WhatsApp.
- Sincronizar eventos con Google Calendar.
- Facilitar el seguimiento del historial de pagos.
- Mejorar la organización financiera de los usuarios.

---

## 🚀 Alcance

### 🧩 Funcionalidades previstas en la primera versión

- Registro de usuarios.
- Inicio de sesión.
- Registro manual de recibos.
- Gestión de estados de pago.
- Calendario de vencimientos.
- Historial de pagos.
- Recordatorios automáticos.
- Notificaciones por WhatsApp.
- Sincronización con Google Calendar.

### 🌟 Funcionalidades futuras

- Escaneo automático de recibos.
- Reconocimiento de texto mediante OCR.

---

## 🧭 Funcionalidades Principales

- Registro de usuarios.
- Inicio de sesión seguro.
- Recuperación de contraseña.
- Registro manual de recibos.
- Edición de recibos.
- Eliminación de recibos.
- Consulta de historial de pagos.
- Calendario de vencimientos.
- Recordatorios automáticos.
- Notificaciones por WhatsApp.
- Sincronización con Google Calendar.
- Dashboard informativo.
- Búsqueda y filtrado de recibos.
- Gestión de estados de pago.

---

## 🛠️ Tecnologías Sugeridas

### Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend

- Python
- FastAPI

### Base de Datos

- PostgreSQL

### Herramientas

- Git
- GitHub
- Visual Studio Code

### Servicios Externos

- WhatsApp API
- Google Calendar API

---

## 🏗️ Arquitectura General

### Frontend

Responsable de la interacción con el usuario mediante formularios, paneles, calendarios y notificaciones visuales.

### Backend

Procesa la lógica de negocio, valida datos, maneja autenticación y gestiona recordatorios.

### Base de Datos

Almacena información de usuarios, recibos, categorías, estados de pago y notificaciones.

### Integraciones externas

Gestiona el envío de mensajes y la sincronización de eventos con servicios externos.

---

## ✅ Requisitos Funcionales

RF-001: El sistema debe permitir registrar usuarios mediante correo electrónico.
RF-002: El sistema debe permitir iniciar sesión con usuario y contraseña.
RF-003: El sistema debe permitir recuperar contraseñas olvidadas.
RF-004: El sistema debe permitir cerrar sesión de forma segura.
RF-005: El sistema debe permitir registrar recibos manualmente.
RF-006: El sistema debe permitir editar recibos registrados.
RF-007: El sistema debe permitir eliminar recibos registrados.
RF-008: El sistema debe mostrar el historial de pagos realizados.
RF-009: El sistema debe mostrar pagos pendientes del usuario.
RF-010: El sistema debe mostrar pagos vencidos automáticamente.
RF-011: El sistema debe permitir cambiar el estado de los recibos.
RF-012: El sistema debe generar recordatorios automáticos de pago.
RF-013: El sistema debe enviar notificaciones por WhatsApp.
RF-014: El sistema debe mostrar un calendario de vencimientos.
RF-015: El sistema debe sincronizar eventos con Google Calendar.
RF-016: El sistema debe permitir buscar recibos registrados.
RF-017: El sistema debe permitir filtrar recibos por fecha.
RF-018: El sistema debe permitir filtrar recibos por estado.
RF-019: El sistema debe permitir clasificar recibos por categorías.
RF-020: El sistema debe permitir visualizar detalles completos de recibos.
RF-021: El sistema debe validar campos obligatorios antes de guardar datos.
RF-022: El sistema debe permitir configurar recordatorios personalizados.
RF-023: El sistema debe permitir activar o desactivar notificaciones.
RF-024: El sistema debe mostrar próximos pagos en el dashboard.
RF-025: El sistema debe mostrar alertas de pagos vencidos.
RF-026: El sistema debe permitir registrar la fecha de pago realizada.
RF-027: El sistema debe permitir ordenar recibos por vencimiento.
RF-028: El sistema debe permitir visualizar estadísticas básicas de gastos.
RF-029: El sistema debe permitir diferenciar servicios prioritarios.
RF-030: El sistema debe permitir actualizar automáticamente estados vencidos.
RF-031: El sistema debe permitir almacenar información individual por usuario.
RF-032: El sistema debe permitir visualizar resumen mensual de gastos.
RF-033: El sistema debe permitir acceder al sistema desde dispositivos móviles.
RF-034: El sistema debe permitir acceso desde navegadores web modernos.
RF-035: El sistema debe permitir mantener sesión activa temporalmente.
RF-036: El sistema debe permitir validar autenticidad del usuario.
RF-037: El sistema debe permitir mostrar notificaciones dentro del sistema.
RF-038: El sistema debe permitir gestionar múltiples recibos simultáneamente.
RF-039: El sistema debe permitir visualizar pagos próximos a vencer.
RF-040: El sistema debe permitir registrar diferentes tipos de servicios.
RF-041: El sistema debe permitir actualizar información del perfil del usuario.
RF-042: El sistema debe permitir almacenar historial de modificaciones.
RF-043: El sistema debe permitir identificar automáticamente fechas vencidas.
RF-044: El sistema debe permitir organizar información cronológicamente.
RF-045: El sistema debe permitir mostrar resumen de pagos pendientes.
RF-046: El sistema debe permitir generar alertas visuales prioritarias.
RF-047: El sistema debe permitir sincronizar información en tiempo real.

---

## ⚙️ Requisitos No Funcionales

### 🔒 Seguridad

RNF-001: El sistema debe garantizar seguridad de datos personales.
RNF-002: El sistema debe cifrar las contraseñas almacenadas.
RNF-003: El sistema debe proteger sesiones activas automáticamente.
RNF-004: El sistema debe restringir accesos no autorizados.
RNF-005: El sistema debe utilizar conexiones seguras para transmitir datos.

### ⚡ Capacidad

RNF-006: El sistema debe soportar múltiples usuarios simultáneamente.
RNF-007: El sistema debe almacenar gran cantidad de recibos.
RNF-008: El sistema debe responder en menos de 3 segundos.
RNF-009: El sistema debe mantener rendimiento estable continuamente.
RNF-010: El sistema debe soportar crecimiento de información almacenada.
RNF-011: El sistema debe optimizar velocidad de consultas.

### 🌍 Compatibilidad

RNF-012: El sistema debe funcionar en celulares y computadores.
RNF-013: El sistema debe ser compatible con navegadores modernos.
RNF-014: El sistema debe adaptarse a diferentes tamaños de pantalla.
RNF-015: El sistema debe mantener compatibilidad entre versiones futuras.
RNF-016: El sistema debe integrarse con Google Calendar.
RNF-017: El sistema debe integrarse con servicios de WhatsApp.

### 🛡️ Confiabilidad

RNF-018: El sistema debe minimizar errores de funcionamiento.
RNF-019: El sistema debe evitar pérdida de información.
RNF-020: El sistema debe mantener disponibilidad las 24 horas.
RNF-021: El sistema debe realizar copias de seguridad automáticas.
RNF-022: El sistema debe mantener estabilidad operativa continua.
RNF-023: El sistema debe conservar integridad de los datos almacenados.

### 📈 Escalabilidad

RNF-024: El sistema debe permitir futuras mejoras y actualizaciones.
RNF-025: El sistema debe soportar crecimiento de usuarios.
RNF-026: El sistema debe permitir integración de nuevas funcionalidades.
RNF-027: El sistema debe soportar futuras integraciones externas.
RNF-028: El sistema debe mantener rendimiento al aumentar información.

### 🧩 Mantenibilidad

RNF-029: El código fuente debe estar organizado y documentado.
RNF-030: El sistema debe facilitar futuras correcciones técnicas.
RNF-031: El sistema debe permitir mantenimiento sin afectar usuarios.
RNF-032: El sistema debe facilitar actualizaciones futuras.
RNF-033: El sistema debe mantener consistencia entre módulos.

### 😊 Facilidad de uso

RNF-034: La plataforma debe ser intuitiva y fácil de usar.
RNF-035: La interfaz debe ser amigable para usuarios novatos.
RNF-036: La navegación debe ser sencilla y rápida.
RNF-037: Los formularios deben ser claros y comprensibles.
RNF-038: El sistema debe mostrar mensajes fáciles de entender.
RNF-039: La plataforma debe brindar buena experiencia de usuario.

### ⚡ Otro

RNF-040: El sistema debe tener diseño responsive adaptable.
RNF-041: La plataforma debe mantener consistencia visual.
RNF-042: El sistema debe minimizar consumo de datos móviles.
RNF-043: El sistema debe mantener disponibilidad continua del servicio.
RNF-044: La plataforma debe tener diseño moderno y ordenado.

---

## 🌐 Requisitos de la Interfaz Externa

### 🖥️ Interfaz de Usuario

RIU-001: La plataforma debe tener una interfaz gráfica sencilla y organizada.
RIU-002: El sistema debe incluir un menú principal visible y accesible.
RIU-003: La interfaz debe adaptarse correctamente a celulares y computadores.
RIU-004: La plataforma debe utilizar colores para diferenciar estados de pago.
RIU-005: Los formularios deben ser claros y fáciles de completar.
RIU-006: El sistema debe mostrar mensajes de confirmación al guardar datos.
RIU-007: El sistema debe mostrar mensajes de error comprensibles.
RIU-008: La plataforma debe incluir botones fáciles de identificar.
RIU-009: El sistema debe utilizar íconos representativos en cada módulo.
RIU-010: La interfaz debe mostrar notificaciones visibles al usuario.
RIU-011: La plataforma debe mantener consistencia visual en todas las pantallas.
RIU-012: El dashboard debe mostrar información resumida visualmente.
RIU-013: Los botones principales deben destacarse visualmente.
RIU-014: La navegación entre módulos debe ser rápida y sencilla.
RIU-015: La interfaz debe evitar sobrecarga visual de información.
RIU-016: La plataforma debe mostrar alertas visuales para pagos vencidos.
RIU-017: El sistema debe resaltar pagos próximos a vencer.
RIU-018: La interfaz debe incluir tipografía legible y clara.
RIU-019: La plataforma debe mantener tamaños adecuados de botones y textos.

### 🧩 Interfaz de Hardware

RIH-001: El sistema debe funcionar en computadores de escritorio.
RIH-002: El sistema debe funcionar en laptops.
RIH-003: El sistema debe funcionar en tablets.
RIH-004: El sistema debe funcionar en teléfonos móviles.
RIH-005: La plataforma debe adaptarse a diferentes tamaños de pantalla.
RIH-006: El sistema debe soportar interacción táctil en dispositivos móviles.
RIH-007: El sistema debe funcionar con teclado y mouse.
RIH-008: La aplicación debe optimizar el uso de recursos del dispositivo.
RIH-009: El sistema debe funcionar con conexión estable a internet.
RIH-010: La plataforma debe mantener rendimiento aceptable en dispositivos de gama media.

### 💻 Interfaz de Software

RIS-001: El sistema debe ser compatible con Google Chrome.
RIS-002: El sistema debe ser compatible con Microsoft Edge.
RIS-003: El sistema debe ser compatible con Mozilla Firefox.
RIS-004: El sistema debe integrarse con Google Calendar.
RIS-005: El sistema debe integrarse con servicios de WhatsApp.
RIS-006: El sistema debe utilizar una base de datos segura y confiable.
RIS-007: El sistema debe permitir sincronización de información en tiempo real.
RIS-008: El sistema debe soportar futuras integraciones externas.
RIS-009: El sistema debe mantener compatibilidad con futuras actualizaciones.
RIS-010: El sistema debe permitir almacenamiento seguro de información.

### 🔐 Interfaz de Comunicación

RIC-001: El sistema debe enviar recordatorios automáticos al usuario.
RIC-002: El sistema debe enviar notificaciones mediante WhatsApp.
RIC-003: El sistema debe permitir sincronización con Google Calendar.
RIC-004: El sistema debe mostrar alertas dentro de la plataforma.
RIC-005: El sistema debe mantener comunicación segura con la base de datos.
RIC-006: El sistema debe utilizar conexión segura para transmisión de datos.
RIC-007: El sistema debe permitir intercambio de información en tiempo real.
RIC-008: El sistema debe mostrar mensajes de actualización correctamente.
RIC-009: El sistema debe garantizar estabilidad durante sincronizaciones externas.
RIC-010: El sistema debe minimizar fallos de comunicación entre servicios.

---

## � Definiciones y Acrónimos

| Término | Definición |
|---------|-----------|
| **SRS** | Software Requirements Specification |
| **API** | Interfaz de Programación de Aplicaciones |
| **Frontend** | Parte visual del sistema |
| **Backend** | Lógica interna del sistema |
| **PostgreSQL** | Sistema gestor de bases de datos relacional |
| **FastAPI** | Framework backend en Python |
| **React** | Biblioteca frontend para interfaces web |
| **RF** | Requisito Funcional del sistema |
| **RNF** | Requisito No Funcional del sistema |
| **RIU** | Requisito de Interfaz de Usuario |
| **RIH** | Requisito de Interfaz de Hardware |
| **RIS** | Requisito de Interfaz de Software |
| **RIC** | Requisito de Interfaz de Comunicación |
| **Dashboard** | Panel principal donde se muestran resúmenes, alertas y pagos del usuario |
| **Responsive Design** | Diseño adaptable a diferentes tamaños de pantalla y dispositivos |
| **WhatsApp API** | Servicio utilizado para enviar recordatorios automáticos y notificaciones |

---

## �💡 Beneficios Esperados

- Reducción de pagos atrasados.
- Mejor organización financiera.
- Disminución de recargos por vencimientos.
- Centralización de la información.
- Mayor control sobre obligaciones económicas.
- Ahorro de tiempo en la gestión de pagos.

---

## 👨‍💻 Equipo de Desarrollo

- Sofía Martin Torres — Líder, Backend, Analista
- Mariana Castellanos Parra — Frontend, Analista
- José Luis Castillo Cañas — Base de Datos, Analista
