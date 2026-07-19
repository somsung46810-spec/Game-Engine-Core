# Game-Engine-Core

A modern game engine starter platform built with **Vite**, featuring a modular architecture where controller logic is extracted from UI components into isolated TypeScript/JavaScript modules (similar to **React Hooks** or **Vue Composables**). This separation keeps data fetching, validation, business logic, and rendering independent for improved scalability and maintainability.

---

## Overview

Game-Engine-Core is designed as a production-ready foundation for creating browser-based game engines, interactive 3D applications, AI-assisted content generation, and asset management workflows.

The project combines modern frontend technologies, a high-performance Three.js editor, AI-assisted generation tools, and backend API

---

# Features

## Modular Architecture

- Built with **Vite**
- Loose coupling between presentation and controller logic
- Controller modules separated from UI components
- Reusable business logic
- Clean TypeScript/JavaScript architecture
- Scalable project structure

---

# Application Pages

## Landing (`/`)

Marketing landing page featuring:

- REDPARSON branding
- Crimson & Orange gradient theme
- Animated feature cards
- Modern responsive layout
- Product highlights

---

## Dashboard (`/dashboard`)

Real-time development dashboard displaying:

- Project statistics
- FPS gauge
- Performance analytics chart
- Recent projects
- Live application metrics

---

## 3D Editor (`/editor`)

A full WebGL editor powered by **Three.js**.

### Features

- WebGL viewport
- OrbitControls camera
- Drag & Drop objects
- Cube creation
- Sphere creation
- Light placement
- Physics simulation
- Collision detection
- Web Audio API integration
- Collision sounds mapped to impact intensity
- Material editor

### Material Controls

- Color
- Roughness
- Metalness
- Wireframe mode

### Performance Metrics

Real-time display of:

- FPS
- Draw calls
- Triangle count
- Render statistics

### Logging

Automatically logs:

- Performance metrics
- Rendering statistics
- Scene activity

to the backend API.

---

## Asset Library (`/assets`)

Centralized asset management.

### Search

- Keyword search

### Filters

- Texture
- Mesh
- Audio
- Material
- Script
- Prefab

---

## AI Generation Lab (`/ai-lab`)

Integrated AI workspace, generates engine assets and coding pipeline

### Supported Providers

- GPT-4o
- Claude
- Gemini
- Custom providers

### Generation Modes

- Code
- Shader
- Scene
- Material
- Level

### Features

- Prompt input
- Provider selector
- Terminal-style streaming output
- Generation history
- Extensible AI provider registry

---

Visual representation of the engine development workflow

### Architecture Flow
```

Pipeline
   ↓
Sandbox Zones
   ↓
Asset Registry
   ↓
Safety Bounds
   ↓
Safe Render
   ↓
Active Viewport
```

### Additional Features

- Visual workflow graph
- Kanban sprint board
- Workflow import/export
- Pipeline visualization

---

# Backend

Powered by:

- Express.js
- PostgreSQL

### Includes

- Modular route groups
- AI provider registry
- Physics/audio synchronization
- Performance logging
- Asset management
- Scene management
- REST API

---

# Seed Data

The project ships preloaded with:

| Resource | Count |
|----------|------:|
| Projects | 3 |
| Assets | 10 |
| Scenes | 2 |
| Performance Logs | 15 |

---

# Engine Features

- Three.js rendering
- WebGL viewport
- OrbitControls
- Physics 
- Audio collision feedback
- Material editing
- Real-time rendering statistics
- Asset management
- AI-assisted content generation
- Performance analytics
- Modular architecture
- REST backend
- PostgreSQL persistence
- 4K rendering support

---

# Technology Stack

## Frontend

- Vite
- TypeScript
- JavaScript
- Three.js
- Web Audio API
- HTML5
- CSS3

## Backend

- Express.js
- PostgreSQL

## AI

- GPT-4o
- Claude
- Gemini
- Custom AI Providers

---

# Project Structure

```
Game-Engine-Core/
│
├── src/
│   ├── components/
│   ├── controllers/
│   ├── composables/
│   ├── hooks/
│   ├── editor/
│   ├── assets/
│   ├── ai/
│   ├── pipeline/
│   ├── dashboard/
│   └── shared/
│
├── server/
│   ├── api/
│   ├── routes/
│   ├── services/
│   ├── providers/
│   └── database/
│
├── public/
├── package.json
└── vite.config.ts
```

---

# Design Goals

- High performance
- Loose coupling view controller
- Modular architecture
- Maintainable codebase
- AI-first workflows
- Production-ready backend
- Real-time rendering
- Extensible provider system
- Scalable asset management

---

# Future Roadmap From Pre-processed Phase

- Multiplayer collaboration
- ECS (Entity Component System)
- Plugin marketplace
- Visual scripting
- GPU compute shaders
- Asset versioning
- Cloud rendering
- Multiplayer scene editing
- VR/AR support
- WebGPU renderer
- Automated testing pipeline

---

# License

This project is provided as a sample architecture for modern browser-based game engine development and may be adapted to fit your project's licensing requirements.
