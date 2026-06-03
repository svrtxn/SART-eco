# Sart-Eco

Plataforma inteligente de gestión financiera personal diseñada para centralizar, analizar y optimizar todas las finanzas de una persona desde múltiples fuentes de información.

---

# Descripción

**Sart-Eco** es una plataforma fintech personal que permite consolidar información financiera proveniente de bancos, correos electrónicos, tarjetas, inversiones y registros manuales en un único ecosistema inteligente.

Su objetivo es entregar una visión financiera completa mediante automatización, inteligencia artificial y análisis avanzado de datos.

La plataforma permite:

* Centralizar ingresos y gastos.
* Detectar movimientos automáticamente.
* Administrar bancos y tarjetas.
* Analizar hábitos financieros.
* Controlar presupuestos.
* Gestionar metas de ahorro.
* Detectar suscripciones recurrentes.
* Generar reportes avanzados.
* Obtener recomendaciones financieras mediante IA.

---

# Visión

Convertirse en el centro financiero personal más completo e inteligente para cualquier usuario, permitiendo tomar mejores decisiones económicas mediante automatización, análisis e inteligencia artificial.

---

# Objetivos Principales

* Centralizar todas las finanzas en una única plataforma.
* Automatizar la captura de movimientos financieros.
* Reducir el ingreso manual de información.
* Entregar visibilidad financiera en tiempo real.
* Detectar gastos innecesarios.
* Mejorar hábitos financieros.
* Facilitar el ahorro y el cumplimiento de metas.
* Generar reportes financieros inteligentes.
* Proporcionar recomendaciones personalizadas mediante IA.

---

# Funcionalidades Principales

## Dashboard Financiero Inteligente

Visualización consolidada de:

* Patrimonio total.
* Balance consolidado.
* Ingresos mensuales.
* Gastos mensuales.
* Flujo de caja.
* Evolución financiera.
* Distribución por categorías.
* Metas financieras.
* Inversiones.
* Deudas.
* Suscripciones activas.
* Alertas importantes.
* Insights generados por IA.

Dashboard completamente configurable mediante widgets.

---

## Integración con Correos Electrónicos

Compatible con:

* Gmail
* Outlook
* Microsoft 365
* Yahoo Mail

Permite:

* Escaneo histórico.
* Sincronización automática.
* Procesamiento continuo.
* Detección de movimientos financieros.
* Clasificación automática mediante IA.

---

## Integración Bancaria

Soporte para:

* APIs bancarias.
* Open Banking.
* Agregadores financieros.
* Importaciones manuales.

Permite:

* Agregar bancos.
* Eliminar bancos.
* Configurar sincronización.
* Gestionar múltiples cuentas.

---

## Gestión de Cuentas

Tipos soportados:

* Cuenta Corriente.
* Cuenta Vista.
* Cuenta Ahorro.
* Cuenta Digital.
* Cuenta de Inversión.

---

## Gestión de Tarjetas

Tipos soportados:

* Crédito.
* Débito.
* Prepago.

Características:

* Identificación automática mediante BIN Lookup.
* Detección de banco emisor.
* Detección de marca.
* Detección de categoría.
* Administración de cupos.
* Seguimiento de utilización.

---

## Centro de Transacciones

Funciones avanzadas:

* Búsqueda global.
* Filtros dinámicos.
* Clasificación automática.
* Etiquetas personalizadas.
* Edición de movimientos.
* Agrupación de transacciones.
* División de movimientos.
* Exportación de datos.

---

## Presupuestos

Permite:

* Presupuestos mensuales.
* Presupuestos anuales.
* Presupuestos por categoría.

Incluye:

* Alertas automáticas.
* Proyecciones de gasto.
* Indicadores de riesgo.

---

## Metas Financieras

Creación de objetivos como:

* Fondo de emergencia.
* Viajes.
* Vehículos.
* Vivienda.
* Jubilación.
* Objetivos personalizados.

Con seguimiento visual y estimaciones automáticas.

---

## Detector de Suscripciones

Detecta automáticamente:

* Netflix
* Spotify
* Disney+
* Amazon Prime
* SaaS
* Membresías

Muestra:

* Costo mensual.
* Costo anual.
* Próximos cobros.
* Variaciones de precio.

---

## Asistente Financiero con IA

Permite realizar consultas como:

* ¿En qué gasté más este mes?
* ¿Qué categoría aumentó más?
* ¿Cuánto gasto en restaurantes?
* ¿Qué gastos puedo reducir?
* ¿Qué suscripciones no utilizo?

Genera:

* Insights financieros.
* Alertas.
* Recomendaciones.
* Predicciones.
* Resúmenes automáticos.

---

## Reportes

Exportación en:

* PDF
* Excel
* CSV

Reportes:

* Mensuales.
* Trimestrales.
* Anuales.
* Personalizados.

---

# Arquitectura Tecnológica

## Frontend

* Angular 20+
* TypeScript
* Angular Signals
* RxJS
* Angular Material
* TailwindCSS
* Angular CDK
* PWA
* SSR

## Backend

* NestJS
* TypeScript

## Base de Datos

* PostgreSQL

## Cache

* Redis

## Mensajería

* RabbitMQ

## Inteligencia Artificial

* OpenAI

## Infraestructura

* Docker
* Kubernetes
* AWS

---

# Seguridad

Sart-Eco fue diseñado bajo un enfoque Security First.

## Autenticación

* OAuth2
* OpenID Connect
* JWT
* Refresh Tokens
* MFA

## Protección

* AES-256
* TLS 1.3
* CSP
* XSS Protection
* CSRF Protection
* SQL Injection Protection
* Secrets Management
* Rate Limiting

## Auditoría

Registro completo de:

* Inicios de sesión.
* Conexiones bancarias.
* Sincronizaciones.
* Cambios de configuración.
* Acciones administrativas.

---

# Módulos

```text
Dashboard
Transactions
Banks
Accounts
Cards
Budgets
Goals
Subscriptions
Reports
AI Assistant
Notifications
Profile
Settings
Administration
Email Sync
Audit
Security
```

# Estructura del Proyecto

```text
src/

core/
shared/
layouts/
features/

features/
├── dashboard
├── transactions
├── banks
├── accounts
├── cards
├── budgets
├── goals
├── subscriptions
├── reports
├── ai-assistant
├── notifications
├── settings
├── profile
└── admin

services/
models/
guards/
interceptors/
state/
utils/
```

# Roadmap

## MVP

* Autenticación.
* Dashboard.
* Bancos.
* Cuentas.
* Tarjetas.
* Transacciones.
* Importación CSV.
* Reportes básicos.
* IA básica.

## Versión Avanzada

* Escaneo inteligente de correos.
* Integración Open Banking.
* IA avanzada.
* Predicciones financieras.
* Detección automática de suscripciones.
* Automatizaciones.

## Enterprise

* Multiusuario.
* Equipos familiares.
* Contadores externos.
* Auditorías avanzadas.
* Machine Learning personalizado.
* Detección de fraude.
* Integraciones financieras globales.

---

# Principios del Proyecto

Sart-Eco se construye sobre seis pilares fundamentales:

1. Seguridad.
2. Privacidad.
3. Precisión.
4. Automatización.
5. Escalabilidad.
6. Inteligencia Financiera.

Cada funcionalidad debe aportar valor real al usuario y ayudarle a comprender mejor su situación financiera.

---

# Estado del Proyecto

🚧 En desarrollo activo.

Arquitectura orientada a producción, preparada para escalar desde usuarios individuales hasta una plataforma fintech de nivel empresarial.
