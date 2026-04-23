# 👨‍🎓 Chambitas: Ecosistema de Microservicios para la Empleabilidad Juvenil

Bienvenido a la organización oficial de **Chambitas**, un Trabajo de Investigación desarrollado para optar el grado de bachiller en **Ingeniería de Software** en la **Universidad Peruana de Ciencias Aplicadas (UPC)**.

## 🚀 Visión del Proyecto
Chambitas es una plataforma web integral diseñada para reducir el desempleo juvenil en estudiantes universitarios de pregrado en Perú (meta: 11.3% → 10.4%). Nuestra solución aborda el "Skill Mismatch" y la falta de experiencia mediante un ecosistema distribuido y algoritmos de inteligencia artificial.

## 🏗️ Arquitectura del Sistema
El proyecto utiliza un enfoque de **Ecosistema de Microservicios** orquestado bajo un **Turborepo**, lo que permite escalabilidad multi-institucional y despliegues independientes.

### Componentes Principales:
- **Frontend:** React + Vite + TypeScript (Metodología Atomic Design).
- **API Gateway:** Punto de entrada único construido con NestJS.
- **Microservicios (Backend):** Lógica desacoplada en NestJS (Auth, Perfil, Marketplace, Notificaciones).
- **ML Engine:** Motor de recomendación híbrido (Random Forest/KNN) desarrollado en Python con Scikit-learn.
- **Analytics & Audit:** Servicio transversal para métricas de inserción laboral (HU-16) y cumplimiento de la Ley N° 29733.
- **Persistencia:** PostgreSQL en Supabase con búsqueda semántica (pgvector).

## 🛠️ Stack Tecnológico
| Capa | Tecnologías |
| :--- | :--- |
| **Monorepo** | Turborepo, pnpm |
| **Backend** | NestJS, TypeScript, gRPC, Docker |
| **IA/ML** | Python, FastAPI, Scikit-learn, Pandas |
| **Frontend** | React, Shadcn/UI, Tailwind CSS, React-icons |
| **Infraestructura** | Railway, Vercel, GitHub Actions (CI/CD) |
| **Seguridad** | Zero Trust Architecture, RLS (Row Level Security), Regex Validation |

## 👥 Equipo del Proyecto
- **Product Owner:** Rafael Oswaldo Castro Veramendi
- **Scrum Master:** Brayan Stiven Gamboa Delgado
- **Developer:** Rodrigo Adrián López Huamán

## 📋 Prerrequisitos para Desarrolladores
Para contribuir o levantar el entorno local, asegúrate de tener:
1. **Node.js** (v18+) y **pnpm** instalado globalmente: `npm install -g pnpm`
2. **Python** 3.10+ para el motor de ML.
3. **Docker Desktop** para la orquestación de servicios.
4. Aprobar los builds de dependencias nativas: `pnpm approve-builds`

## 📂 Repositorios
- [chambitas-turborepo](https://github.com/Chambitas-Project/chambitas-turborepo): Repositorio principal que contiene todas las aplicaciones y librerías compartidas.

---
© 2026 Chambitas Project - Facultad de Ingeniería, UPC.
