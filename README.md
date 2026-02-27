# 💅 SaaS Estética Pro

> **Plataforma de gestión integral para centros de estética y bienestar**

[![Demo en Vivo](https://img.shields.io/badge/Demo-Live-green?style=flat-square&logo=vercel)](https://saas-estetica-pro.vercel.app)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs)
![Supabase](https://img.shields.io/badge/Supabase_2-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white)

---

## 🌐 Demo en vivo

**👉 [saas-estetica-pro.vercel.app](https://saas-estetica-pro.vercel.app)**

---

## 📋 Descripción

SaaS completo para la gestión de centros de belleza y spa. Cubre el ciclo completo de operaciones: turnos, clientes, inventario y análisis de negocio — con inteligencia artificial integrada para predicciones y automatización.

### Características principales

- ✅ **Gestión de turnos** con calendario interactivo y recordatorios
- ✅ **CRM de clientes** con historial de servicios y preferencias
- ✅ **Dashboard analítico** con Recharts (ingresos, servicios más demandados)
- ✅ **Autenticación y roles** con Supabase Auth (admin, empleado, cliente)
- ✅ **Row Level Security (RLS)** — datos aislados por negocio
- ✅ **Asistente IA** con Google Gemini 2.5 Flash para recomendaciones
- ✅ Responsive, accesible y bilingüe EN/ES

---

## 🛠️ Stack Técnico

| Capa | Tecnología |
|---|---|
| **Framework** | Next.js 15 (App Router) |
| **Lenguaje** | TypeScript 5.x |
| **Estilos** | Tailwind CSS 4.x · Framer Motion 11.x |
| **Backend/Auth** | Supabase 2.x (Auth, RLS, Edge Functions) |
| **Base de datos** | PostgreSQL 16 |
| **AI** | Google Gemini 2.5 Flash API |
| **Charts** | Recharts 2.x |
| **Deploy** | Vercel |

---

## 🏗️ Arquitectura

```
┌────────────────────────────────────────┐
│          Next.js 15 App Router          │
│  ┌────────────┐    ┌──────────────────┐ │
│  │  Dashboard │    │  Server Actions  │ │
│  │  Calendario│    │  + API Routes    │ │
│  └────────────┘    └────────┬─────────┘ │
└───────────────────────────┼────────────┘
                            ▼
           ┌───────────────────────────┐
           │      Supabase BaaS        │
           │  Auth · RLS · Realtime    │
           │  Edge Functions · Storage │
           └───────────────────────────┘
```

---

> **Nota:** Este es un repositorio de exhibición. El código fuente completo es privado (producto comercial).
> Para consultas sobre licencias o desarrollo a medida: [diegofbis63@gmail.com](mailto:diegofbis63@gmail.com)
