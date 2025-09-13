# VoYatra - Travel Companion App

## Overview

VoYatra is a comprehensive travel companion application designed to help groups plan, track, and manage their travel experiences. The app provides real-time budget tracking, location sharing, weather updates, group communication, emergency assistance, and personalized travel recommendations. Built with modern web technologies, it follows a design approach inspired by travel-focused platforms like Airbnb and Booking.com while maintaining its own unique feature set for group travel coordination.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript, using Vite as the build tool
- **Routing**: Wouter for lightweight client-side routing
- **UI Components**: Radix UI primitives with shadcn/ui component library
- **Styling**: Tailwind CSS with custom design system featuring travel-themed color palette
- **State Management**: TanStack Query for server state management and caching
- **Real-time Communication**: WebSocket integration for live chat functionality

### Backend Architecture
- **Runtime**: Node.js with Express.js server
- **Language**: TypeScript with ES modules
- **API Design**: RESTful API with dedicated route handlers for different features
- **Real-time Features**: WebSocket server for group chat and live location updates
- **Error Handling**: Centralized error handling middleware with proper status codes

### Data Storage Solutions
- **Primary Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Database Provider**: Neon serverless PostgreSQL for cloud hosting
- **Schema Management**: Drizzle Kit for migrations and schema evolution
- **Session Storage**: PostgreSQL-based session management using connect-pg-simple

### Core Data Models
- **Users**: Profile management with travel preferences and statistics
- **Budget Entries**: Expense tracking with categories (food, hotel, transport, other)
- **Reviews**: Hotel and restaurant reviews with photo uploads and ratings
- **Chat Messages**: Group communication with support for text, location, and image messages
- **User Locations**: Real-time location tracking for team coordination
- **Travel Memories**: Photo-based travel history and experiences
- **Future Trips**: Trip planning and itinerary management
- **Emergency Contacts**: Local emergency services and personal emergency contacts
- **Emergency Alerts**: Safety notifications and alerts system

### Authentication and Authorization
- **Current Implementation**: Simplified demo user system for MVP
- **Session Management**: Server-side sessions with PostgreSQL storage
- **Security**: CORS configuration and request validation middleware

### Component Architecture
- **Design System**: Consistent theming with light/dark mode support
- **Reusable Components**: Modular UI components following atomic design principles
- **Feature Components**: Dedicated components for each major feature (BudgetTracker, GroupChat, MapView, etc.)
- **Layout System**: Responsive grid layouts with mobile-first approach

### Key Features Integration
- **Budget Management**: Real-time expense tracking with progress indicators and category-wise spending analysis
- **Live Location Sharing**: WebSocket-based real-time location updates for team coordination
- **Group Communication**: Instant messaging with typing indicators and online status
- **Weather Integration**: Hyperlocal weather data and local event information
- **Emergency Services**: Quick access to local emergency contacts and alert broadcasting
- **Travel Recommendations**: AI-powered suggestions based on user preferences and budget
- **Review System**: Photo-based reviews for hotels and restaurants with instant sharing

## External Dependencies

### Core Framework Dependencies
- **React Ecosystem**: React 18 with TypeScript, React Router alternative (Wouter)
- **UI Library**: Radix UI primitives for accessible components
- **Styling**: Tailwind CSS for utility-first styling approach
- **Build Tools**: Vite for fast development and optimized production builds

### Backend Dependencies
- **Server Framework**: Express.js for HTTP server and API routing
- **Database**: Drizzle ORM with PostgreSQL driver (@neondatabase/serverless)
- **Real-time**: WebSocket (ws) for live chat and location updates
- **Session Management**: connect-pg-simple for PostgreSQL-based sessions

### Development Tools
- **TypeScript**: Full-stack type safety with shared schema definitions
- **Database Tools**: Drizzle Kit for schema management and migrations
- **Code Quality**: ESBuild for production bundling and optimization

### Planned External Service Integrations
- **Weather APIs**: For real-time weather data and forecasts
- **Maps Services**: For location services and navigation features
- **Travel APIs**: For recommendations and booking integrations
- **Emergency Services APIs**: For local emergency contact information
- **Image Storage**: For photo uploads in reviews and travel memories
- **Notification Services**: For push notifications and emergency alerts

### Development Environment
- **Replit Integration**: Optimized for Replit development environment
- **Environment Configuration**: Development and production environment separation
- **Asset Management**: Static asset handling for images and media files