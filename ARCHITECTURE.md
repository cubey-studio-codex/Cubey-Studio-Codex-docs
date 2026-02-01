# Cubey Studio Architecture

Cubey Studio is built using a layered architecture.

## High-Level Overview
Cubey Studio (MAUI) 
└── WebView 
    └── Cubey Web Editor (Monaco) 
        └── Language Server (LSP) 
            └── Cubey Engine (C++)

## Components

### Cubey Studio (IDE)
- User interface
- Project management
- Plugin loader
- Tool orchestration

### Cubey Web Editor
- Code editing
- Syntax highlighting
- IntelliSense
- Themes and keybindings

### Language Server
- Code analysis
- Autocomplete
- Diagnostics
- Refactoring

### Cubey Engine
- Native build system
- Runtime services
- Debug tools
