# Front-end-Component-Library

## Microkernel Architecture (main architecture pattern)

- sometimes referred to as the plug-in architecture is a natural pattern for implementing product-based applications
- consists of two types of architecture components: core system and plug-in modules
- application logic is divided between independent plug-in models and the basic core system, providing extensibility, flexibility, and isolation of application features and custom logic

### Core System

- based on MVC (model-view-control)
- the core system of the microkernel architecture pattern traditionally contains only the minimal functionality required to make the system operational

### Plug-in Modules

- based on Atomic Design Pattern
- the plug-in modules are stand-alone, independent components that contain specialized processing, additional features, and custom code that is meant to enhance or extend the core system to produce additional business capabilities