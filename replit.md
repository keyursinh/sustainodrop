# Water Tank Monitoring System

## Overview

This project is a sophisticated water tank monitoring system that provides real-time monitoring, control, and management of water tanks across multiple locations. The application features a modern web interface for monitoring water levels, flow rates, sensor health, and system performance with automated alerts and smart controls.

The system is built as a full-stack application with a React frontend and Express.js backend, utilizing PostgreSQL for data persistence and WebSocket connections for real-time updates. It includes comprehensive monitoring capabilities, automated alerting, and remote control functionality for water tank management.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript for type safety and better developer experience
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack React Query for server state management and caching
- **UI Framework**: shadcn/ui components built on Radix UI primitives with Tailwind CSS for styling
- **Real-time Updates**: Custom WebSocket hooks for live data synchronization

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules for modern JavaScript features
- **API Design**: RESTful endpoints with structured error handling and request logging
- **Real-time Communication**: WebSocket server for live updates to connected clients
- **Development Setup**: Vite for development server with hot module replacement

### Data Storage Solutions
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Schema Management**: Drizzle migrations for database version control
- **Connection**: Neon Database serverless PostgreSQL with connection pooling
- **Data Modeling**: Comprehensive schema covering locations, tanks, sensors, alerts, usage records, system configurations, and activities

### Authentication and Authorization
- **Session Management**: PostgreSQL-based session storage using connect-pg-simple
- **Security**: Express middleware for request validation and error handling
- The authentication system appears to be prepared but not fully implemented in the current codebase

### External Service Integrations
- **Database Provider**: Neon Database for managed PostgreSQL hosting
- **Monitoring**: Custom WebSocket implementation for real-time system monitoring
- **Development Tools**: Replit integration with development banners and cartographer plugin
- **Font Loading**: Google Fonts integration for typography

## External Dependencies

### Core Technologies
- **Database**: PostgreSQL via Neon Database serverless platform
- **ORM**: Drizzle ORM with Drizzle Kit for migrations and schema management
- **UI Components**: Extensive Radix UI component library for accessible interface elements
- **Styling**: Tailwind CSS with custom design system and CSS variables
- **State Management**: TanStack React Query for server state and caching
- **Real-time Communication**: Native WebSocket API with custom connection management

### Development and Build Tools
- **Build System**: Vite for fast development and optimized production builds
- **TypeScript**: Full TypeScript support across frontend, backend, and shared code
- **Code Quality**: ESBuild for fast bundling and compilation
- **Development Environment**: Replit-specific tooling and error overlay systems

### Third-party Services
- **Database Hosting**: Neon Database for managed PostgreSQL with connection pooling
- **Font Services**: Google Fonts for web typography
- **Development Platform**: Replit environment with integrated development tools