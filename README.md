# 🛡️ EPI-c - Gestión Inteligente de EPIs para Centros Logísticos

<div align="center">

**Aplicación web responsive para automatizar la gestión de uniformes y equipos de protección individual (EPIs) en almacenes logísticos de gran volumen.**

</div>

---

## 📋 Tabla de Contenidos

- [Acerca del Proyecto](#-acerca-del-proyecto)
- [Características Principales](#-características-principales)
- [Stack Tecnológico](#️-stack-tecnológico)
- [Ejemplos de Uso](#-ejemplos-de-uso)
- [Licencia](#-licencia)
- [Agradecimientos](#-agradecimientos)

---

## 🎯 Acerca del Proyecto

**EPI-c** nace de una necesidad real identificada en un centro logístico con más de 2.000 empleados: la gestión manual de EPIs genera colas interminables, pérdida de tiempo productivo y frustración entre trabajadores y administradores.

### El Problema

En centros logísticos tradicionales:
- ⏱️ Los empleados pierden **30-45 minutos** al mes gestionando EPIs
- 📋 El personal administrativo dedica **4+ horas diarias** a gestión manual
- 😤 Largas colas durante cambios de turno
- ❓ Confusión sobre plazos de renovación según normativa PRL
- 📊 Falta de trazabilidad para auditorías

### La Solución

EPI-c transforma este proceso caótico en un sistema digital eficiente:

```
ANTES (Manual)                    DESPUÉS (EPI-c)
├─ Ir físicamente al almacén  →  ├─ Solicitar desde cualquier dispositivo
├─ Hacer cola 15-20 minutos   →  ├─ 3 clics, 30 segundos
├─ ¿Cuándo puedo renovar?     →  ├─ Contador automático visible
├─ Cita cuando el almacén esté→  ├─ Sistema inteligente según tu turno
└─ Papel/Excel desorganizado  →  └─ Dashboard analítico en tiempo real
```

**Resultado:** Ahorro de **300+ horas/año** por cada 1.000 empleados gestionados.

---

## ✨ Características Principales

### Para Empleados 👷

- 🔐 **Autenticación corporativa** - Login seguro con email de empresa
- 📦 **Solicitud ultra-simple** - Pide tus EPIs en solo 3 clics
- ⏰ **Control automático de plazos** - El sistema bloquea solicitudes prematuras según normativa
- 📅 **Agendamiento inteligente** - Elige cita compatible con tu turno laboral (mañana/tarde/noche)
- 📊 **Historial completo** - Consulta todas tus entregas pasadas
- 🔔 **Notificaciones automáticas** - Recibe avisos cuando puedas renovar EPIs

### Para Administradores 👨‍💼

- 📈 **Dashboard analítico** - Gráficos en tiempo real sobre solicitudes, inventario y tendencias
- ✅ **Gestión de solicitudes** - Aprobar/rechazar con sistema de comentarios
- 📦 **Control de inventario** - Stock en tiempo real con alertas de reposición
- 🗓️ **Calendario interactivo** - Visualiza y gestiona todas las citas agendadas
- 📄 **Reportes para auditorías** - Genera PDFs/Excel para cumplimiento PRL
- 🔍 **Trazabilidad completa** - Quién solicitó qué, cuándo y cómo

### Seguridad y Compliance 🔒

- 🛡️ Protección SQL Injection (prepared statements)
- 🔒 Encriptación SSL/TLS
- ✅ Cumplimiento RGPD (derecho al olvido, exportación datos)

---

## 🛠️ Stack Tecnológico

### Frontend
- **Vue.js 3** - Framework JavaScript reactivo
- **Bootstrap 5** - Diseño responsive y componentes UI
- **JavaScript ES6** - Lógica del cliente

### Backend
- **PHP 8.2** - Lenguaje servidor (arquitectura MVC)
- **MySQL 8.0** - Base de datos relacional
- **PDO** - Capa de abstracción de base de datos

### DevOps & Herramientas
- **Git/GitHub** - Control de versiones
- **Composer** - Gestión de dependencias PHP
- **npm** - Gestión de dependencias JavaScript
- **AWS EC2** - Hosting en producción

---

## 💡 Ejemplos de Uso

### Caso 1: Empleado solicita botas de seguridad

```
1. Login → empleado@empresa.com
2. Dashboard → Ver "Próximas renovaciones disponibles"
3. Click "Solicitar Botas de Seguridad"
4. Sistema valida: ✅ Han pasado 6 meses desde última entrega
5. Seleccionar talla: 42
6. Elegir cita: Jueves 15:30 (compatible con turno de tarde)
7. Confirmar → ✅ Solicitud enviada
8. Notificación email: "Tu cita es el jueves a las 15:30"
```

### Caso 2: Administrador gestiona inventario bajo

```
1. Login admin → Dashboard
2. Alerta roja: "Stock crítico: Chalecos reflectantes (8 unidades)"
3. Click en alerta → Ver histórico de consumo
4. Gráfico muestra: consumo promedio 15 unidades/mes
5. Generar orden de compra: 50 chalecos
6. Sistema actualiza stock proyectado
7. Exportar PDF para compras
```

### Caso 3: Auditoría PRL solicita trazabilidad

```
1. Admin → Reportes
2. Seleccionar: "Entregas de EPIs - Último trimestre"
3. Filtrar por: "Calzado de seguridad"
4. Generar Excel con:
   - Empleado
   - Fecha entrega
   - Tipo EPI
   - Próxima renovación obligatoria
5. Descargar → Entregar a auditor
```

## 📄 Licencia

Distribuido bajo la Licencia MIT. Ver `LICENSE` para más información.

La Licencia MIT permite:
- ✅ Uso comercial
- ✅ Modificación
- ✅ Distribución
- ✅ Uso privado

**Restricciones:**
- ⚠️ Sin garantía
- ⚠️ Debes incluir el aviso de copyright original

---

## 🙏 Agradecimientos

**Especial agradecimiento:**
- A los **2.000+ trabajadores** del centro logístico que inspiraron este proyecto
- A **IES Domenico Scarlatti** por la formación en DAW que hizo esto posible
- A la **comunidad open source** por compartir conocimiento libremente
---

<div align="center">

**¿Te ha resultado útil EPI-c?** ¡Dale una ⭐ al proyecto!

Hecho con ❤️ en Aranjuez, Madrid por Chaimae y Andrea

[Volver arriba ⬆️](#️-epi-c---gestión-inteligente-de-epis-para-centros-logísticos)

</div>
