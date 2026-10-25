# 🗂️ SyntaxSanctuary File Manager (Genesis)

<div align="center">

![Version](https://img.shields.io/badge/version-v0.1.0-blue.svg)
![PHP Version](https://img.shields.io/badge/PHP-%3E%3D8.1-777BB4.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

</div>

**SyntaxSanctuary File Manager** es un administrador de archivos web minimalista, ultraligero y robusto, empaquetado en un **monolito de un solo archivo PHP** (`index.php`). Diseñado bajo la filosofía Mobile First, ofrece una interfaz limpia con modo claro y oscuro automáticos, priorizando la seguridad y la velocidad sin dependencias complejas.

---

## ✨ Características Principales

* **Monolito Autónomo:** Todo el sistema operativo y la lógica residen en un único script PHP fácil de desplegar.
* **Seguridad Robusta:** Protección integrada contra ataques de *Path Traversal*, vulnerabilidades *CSRF* y aislamiento estricto del directorio raíz.
* **Auto-Protección:** El sistema bloquea de forma inteligente cualquier intento de eliminar, sobrescribir o editar el propio archivo del gestor (`index.php`).
* **Gestión Completa de Archivos:**
  * Exploración de carpetas y navegación fluida por niveles.
  * Creación, subida y descarga individual de archivos y directorios.
  * Eliminación recursiva segura con confirmación.
  * Editor de texto integrado en línea con control de tamaños máximos.
* **Interfaz Moderna (Mobile First):** Diseño adaptable desde pantallas móviles de 320px hasta escritorios de gran formato, con soporte nativo para **Tema Claro y Oscuro**.

---

## 🚀 Instalación Rápida

1. Asegúrate de tener instalado **PHP 8.1** o superior en tu servidor web (Apache, Nginx o servidor embebido de PHP).
2. Descarga o clona este repositorio en el directorio de tu elección:
   ```bash
   git clone [https://github.com/tu-usuario/syntaxsanctuary-file-manager.git](https://github.com/tu-usuario/syntaxsanctuary-file-manager.git)
