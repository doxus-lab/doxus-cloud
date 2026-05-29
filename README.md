# 🗂️ Panel Central & Bitácora Web

Este repositorio funciona como un ecosistema web centralizado y dinámico. En lugar de gestionar múltiples repositorios dispersos, este espacio unifica diferentes interfaces, herramientas y bitácoras bajo una sola arquitectura modular accesible a través de **GitHub Pages**.

---

## 🛠️ Arquitectura del Repositorio

El proyecto utiliza un sistema de enrutamiento estático simple. El archivo raíz actúa como el nodo central (Dashboard / Portada), mientras que cada módulo independiente se aloja en su respectiva subcarpeta para evitar conflictos de estilos (`CSS`) o lógicas (`JS`).

```text
├── index.html                 # Panel de control principal (Menú y navegación)
├── README.md                  # Documentación del sistema
│
├── [modulo-o-entrada-1]/      # Módulo independiente aislado
│   ├── index.html             # Interfaz del módulo
│   ├── style.css              # Estilos específicos del módulo
│   └── main.js                # Lógica específica
│
└── [modulo-o-entrada-2]/      # Clonar esta estructura para nuevos despliegues
    └── index.html
