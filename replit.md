# Comparame Express Mx - Plataforma de Comparación de Servicios

## Project Overview
Plataforma integral para propietarios mexicanos que permite comparar y encontrar los mejores servicios para el hogar incluyendo internet, seguros, servicios públicos, seguridad, jardinería y garantías. Construido con React, TypeScript y Express con optimización SEO y soporte multiidioma (Español/Inglés).

## Architecture
- **Frontend**: React + TypeScript + Tailwind CSS + shadcn/ui
- **Backend**: Express + TypeScript
- **Database**: PostgreSQL with Drizzle ORM (fallback to in-memory storage for development)
- **Routing**: Wouter for client-side routing
- **State Management**: TanStack Query for server state
- **Styling**: Tailwind CSS with custom design system

## Key Features
- Service comparison tables with filtering and sorting
- SEO-optimized pages with meta tags and Open Graph
- Responsive design for mobile, tablet, and desktop
- Contact form with backend API
- Resource center with guides and tools
- Dynamic service provider data

## Database Schema
- `users` - User authentication
- `service_categories` - Service types (internet, insurance, etc.)
- `service_providers` - Provider details with ratings and coverage areas
- `contact_messages` - Contact form submissions

## Recent Changes
- **2025-01-28**: Initial project setup with full-stack architecture
- **2025-01-28**: Fixed wouter navigation hooks (useLocation instead of useNavigate)
- **2025-01-28**: Added comprehensive SEO implementation
- **2025-01-28**: Implemented database layer with Drizzle ORM
- **2025-01-28**: Created dual storage system (database/memory) for flexibility
- **2025-01-28**: Complete rebrand to "Comparame Express Mx"
- **2025-01-28**: Added i18next multilingual support (Spanish/English)
- **2025-01-28**: Modern minimalist UI redesign with gradients and animations
- **2025-01-28**: Updated sample data with Mexican providers and services
- **2025-01-28**: Enhanced SEO with Mexico-focused content and metadata

## User Preferences
- Language: Spanish (user prefers Spanish communication)
- Focus: Complete, production-ready implementation with permanent deployment
- Project Name: "Comparame Express Mx" (finalized)
- Design: Modern minimalist with current trends, fast and visually attractive
- Target Market: Mexican homeowners
- Languages: Spanish (primary) and English support required

## Project Status
- ✅ Frontend components and pages with modern design
- ✅ Backend API endpoints with Mexican data
- ✅ SEO optimization for Mexico market
- ✅ Database schema and storage layer
- ✅ Multilingual support (Spanish/English)
- ✅ Modern UI with animations and gradients
- ✅ Mobile responsive design
- 📋 Ready for permanent deployment