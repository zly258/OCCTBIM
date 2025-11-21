# OCCTBIM Architecture Documentation

## Documentation Overview

This documentation collection provides a detailed description of the complete architecture design of the OCCTBIM system. Based on actual code analysis, it offers detailed design specifications, class diagrams, architecture diagrams, and implementation details for each module of the system.

## 📚 Architecture Documentation

### 🏛️ System Architecture Documents

1. **[System Overall Architecture](system-overview.md)** - System hierarchy and module relationships
2. **[Document System](document-system.md)** - Document management and lifecycle
3. **[Entity System](entity-system.md)** - Entity system, property architecture, and editor extension mechanisms
4. **[Extended Data System](extend-data-system.md)** - Extended data system and custom data management
5. **[Tool System](tool-system.md)** - Tool system and interaction logic
6. **[Action System](action-system.md)** - Action configuration and management system
7. **[UI User Interface System](ui-system.md)** - Interface components and docking panel system
8. **[BIM Professional Modules](bim-system.md)** - HVAC, piping, structural, PID and other professional modeling systems
9. **[Data Storage System](data-storage.md)** - Database and file IO system
10. **[Extension Mechanism Design](extension-mechanism.md)** - Plugin and extension architecture

## 🎯 Core Features

### 📐 Modeling Functions
- **2D Drawing**: Points, lines, circles, arcs, rectangles, polygons and other basic graphics
- **3D Modeling**: Cubes, spheres, cylinders and other basic solids and feature modeling
- **Annotation**: Text, tables, various dimension annotations
- **Block System**: Block definition, block reference and nested block support

### 🏗️ BIM Professional Modules
- **HVAC**: Air duct system, equipment modeling, system management
- **Piping System**: Pipeline modeling, pipe fittings library, intelligent connections
- **Structural Modeling**: Steel structures, section steel library, component management
- **PID Symbols**: Process flow diagram symbol definition and management

### 🔧 System Architecture
- **Layered Architecture**: Clear separation of presentation, application, business, and core layers
- **Modular Design**: Independent functional modules with plugin support
- **Extension Mechanism**: Multi-dimensional extension support for entities, tools, actions, and data
- **Property System**: Complete property definition, editor and validation mechanisms

### 💾 Data Management
- **SQLite Storage**: Efficient local database storage
- **Multi-format Support**: JSON, DXF, STEP, IGES and other formats
- **Extended Data**: Flexible custom attribute system
- **Transaction Management**: Complete undo/redo and transaction support

### 🎨 User Interface
- **Modern Interface**: Ribbon interface and docking panel system
- **Responsive Design**: Adaptive layout and toolbars
- **Theme Support**: Light/dark theme switching
- **Property Editor**: Powerful property editor system

## 🏗️ Technology Stack

- **Geometric Kernel**: OpenCASCADE 7.9.x
- **UI Framework**: Qt 5.14.x + SARibbon
- **Data Storage**: SQLite + JSON
- **Build System**: CMake + Unity Build
- **File Formats**: DXF(libdxfrw), STEP, IGES, glTF, etc.

## 📖 Learning Path

### 🚀 Quick Start
1. Read [System Overall Architecture](system-overview.md) to understand system overview
2. Choose relevant module documentation for in-depth study based on development needs
3. Refer to extension mechanism documentation for custom development

### 👨‍💻 Developer Guide
- **Core Development**: Read all architecture documents in sequence
- **Entity Development**: Focus on Entity and ExtendData systems
- **Tool Development**: Focus on Tool and Action systems
- **Interface Development**: Focus on UI system and property editors
- **BIM Development**: Focus on BIM modules and professional systems

### 🔧 Extension Development
- Add new entity types using registration mechanism
- Extend interaction tools through factory pattern
- Add user operations through action system
- Add custom attributes through extended data system
- Develop custom property editors

## 📋 Documentation Features

- **Code-based**: All content based on real code analysis
- **Detailed Class Diagrams**: Complete architecture diagrams drawn with Mermaid
- **Implementation Notes**: Include key interfaces and design pattern descriptions
- **Extension Guide**: Provide complete extension development guidance
- **Bilingual Documentation**: Full Chinese and English technical documentation

## 📝 Version Information

- **Documentation Version**: 1.0
- **System Version**: OCCTBIM 1.3.0
- **Creation Date**: October 2024
- **Based on Code**: Strictly based on actual project code structure

---

**Note**: This documentation is strictly written based on actual project code content, without any fictional functions. All architecture designs, class diagrams, and implementation details come from real code analysis.