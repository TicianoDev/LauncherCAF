# Chaos at Fazbear's Launcher

### El launcher oficial para el juego *Chaos at Fazbear's*.

[![Licencia](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![PyQt6](https://img.shields.io/badge/Frontend-PyQt6-green?logo=qt)](https://www.riverbankcomputing.com/software/pyqt/)

Bienvenido al repositorio oficial del launcher de **Chaos at Fazbear's**. Este launcher está diseñado para gestionar la instalación, actualización y ejecución del juego, ofreciendo una experiencia centralizada y fluida para todos los jugadores.


---

## ✨ Características Principales

* ✅ **Instalador Integrado:** Descarga e instala el juego con un solo clic.
* 🔄 **Actualizaciones Automáticas:** El launcher verifica si hay nuevas versiones tanto del juego como de sí mismo para que siempre tengas lo último.
* 📋 **Visor de Notas de Parche:** Entérate de todas las novedades y correcciones directamente desde el launcher.
* ⚙️ **Gestión del Juego:** Desinstala, localiza una instalación existente o abre el directorio del juego desde un práctico menú.
* 🌍 **Soporte Multilenguaje:** Interfaz disponible en Español e Inglés.
* 💬 **Sistema de Feedback:** ¿Tienes una sugerencia o encontraste un error? Envía tus comentarios directamente a los desarrolladores desde la aplicación.
* 💜 **Integración con Discord:** Muestra tu estado de juego a tus amigos con Discord Rich Presence.
* 🔧 **Panel de Ajustes:** Configura el idioma, el inicio con Windows, los límites de ancho de banda y más.

---


## ⚠️ Advertencias Importantes

Antes de descargar y utilizar el launcher, por favor, lee los siguientes puntos.

### 🛡️ Aviso de Falso Positivo (Antivirus)

> **Resumen: Tu antivirus podría detectar el launcher como una amenaza. Es un falso positivo.**
>
> **¿Por qué ocurre esto?**
> El ejecutable del launcher (`.exe`) se genera con herramientas como PyInstaller. Como no está "firmado digitalmente" (un proceso costoso que certifica la identidad del desarrollador), algunos programas de antivirus utilizan heurísticas para analizarlo. A veces, este análisis puede interpretar erróneamente el código del instalador como sospechoso, generando una alerta de virus.
>
> **¿Es seguro?**
> **Sí.** El archivo es completamente seguro y no contiene ningún tipo de malware. Puedes revisar todo el código fuente en este mismo repositorio para verificarlo.
>
> **¿Qué debo hacer?**
> Si tu antivirus bloquea o elimina el archivo, deberás ir a la configuración de tu antivirus y **añadir una excepción** para el archivo `ChaosAtFazbearsLauncher.exe` o para la carpeta donde lo instales.

### 🔑 Acceso Beta Requerido

> Este launcher gestiona el acceso a una versión beta del juego. Para poder descargar e instalar el juego, **necesitas estar en la lista de usuarios autorizados**.
>
> 1.  Al intentar instalar, el launcher te mostrará tu **Identificador de Acceso** (tu dirección MAC).
> 2.  Debes proporcionar este identificador a los administradores del proyecto.
> 3.  Una vez que tu acceso sea aprobado, podrás usar tu contraseña personalizada para descargar el juego.

---

## 🚀 Instalación

1.  Ve a la sección de **Releases** de este repositorio.
2.  Descarga el archivo `ChaosAtFazbearsLauncher.exe` de la última versión.
3.  Ejecuta el archivo. ¡No requiere instalación!

## 🛠️ Creado Con

* **Python:** El lenguaje principal del proyecto[cite: 1].
* **PyQt6:** Para toda la interfaz gráfica de usuario[cite: 1].
* **Requests:** Para la comunicación con los servidores y la API de GitHub[cite: 1].
* **pypresence:** Para la integración con Discord Rich Presence[cite: 1].

---

## ✍️ Créditos

* Launcher desarrollado por: **TicianoM**
* Juego *Chaos at Fazbear's* creado por: **Astrion Studios**
