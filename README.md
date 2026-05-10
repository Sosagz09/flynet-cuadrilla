# 📱 Flynet Cuadrilla

> Generador de reportes diarios para técnicos de campo

[![Netlify Status](https://api.netlify.com/api/v1/badges/d7345d9a-ed08-470d-8077-0d356a9a12b7/deploy-status)](https://flynet-rpt.netlify.app)
![Version](https://img.shields.io/badge/version-4.0-25d366?style=flat)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat)

---

## ¿Qué es?

App web móvil para técnicos de campo. Permite registrar visitas conforme avanza el día y generar un reporte formateado listo para enviar al grupo de WhatsApp — sin tener que recordar nombres al final del turno.

**🔗 Live:** [flynet-rpt.netlify.app](https://flynet-rpt.netlify.app)

---

## ✨ Funcionalidades

- **➕ Agregar rápido** — registra un cliente en segundos: nombre, categoría y nota opcional
- **🔍 Autocompletado** — sugiere nombres del historial mientras escribes
- **📋 Log del día** — muestra todos los registros en tiempo real con hora exacta
- **📄 Resumen** — vista agrupada por tipo de actividad lista para revisar
- **⚙️ Configuración** — activa/desactiva categorías y agrega tipos personalizados
- **🗂 Historial** — guarda los últimos 30 reportes con CRUD completo
- **🌙 Modo oscuro/claro** — se recuerda tu preferencia
- **💾 Sin servidor** — todo se guarda en el navegador con `localStorage`

---

## 📋 Formato del reporte

```
━━━━━━━━━━━━━━━━━
🔧 *REPORTE CUADRILLA* 👨‍🔧
━━━━━━━━━━━━━━━━━
📅 _10/05/26_

*𝐃𝐚𝐧𝐢𝐞𝐥 𝐒𝐨𝐬𝐚*
*𝐊𝐞𝐯𝐢𝐧 𝐌𝐚𝐫𝐭í𝐧𝐞𝐳*

*🏠Instalacion de Servicio*
├Juan Carlos Pérez López
└Ana García (con Flynet Security)

*🛜Soporte de Internet*
└José Guadalupe García

━━━━━━━━━━━━━━━━━
```

---

## 🗂 Categorías disponibles

| Emoji | Actividad |
|-------|-----------|
| 🛜 | Soporte de Internet |
| 📺 | Soporte de IPTV |
| 🏠 | Instalacion de Servicio |
| 📦 | Desinstalacion |
| 🚚 | Cambio de Domicilio |
| ⚠️ | Mantenimiento Preventivo |
| 🔄 | Cambio de Equipo |
| 💰 | Venta de Equipos |
| 🔁 | Renovacion de Servicio |
| ⚡ | Averias |
| ❌ | Cancelados |
| 🏝️ | No Encontrados |

> También puedes agregar categorías personalizadas desde ⚙️ Config.

---

## 🚀 Deploy

El proyecto es HTML/CSS/JS puro — sin dependencias ni build steps.

```
GitHub (main) → Netlify (auto-deploy)
```

Cualquier push a `main` actualiza la app en producción en menos de 30 segundos.

---

## 🛠 Stack

- HTML · CSS · Vanilla JS
- `localStorage` para persistencia
- Netlify para hosting gratuito
- GitHub para control de versiones

---

## 👤 Autor

**Daniel Sosa** — Soporte Técnico e infraestructura  
Técnico de campo · Redes · Fibra óptica · Mikrotik · Cisco
