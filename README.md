# Fire Browser Portable

Navegador para Windows con asistente de IA local, desarrollado por Santiago Nobile.
Incluye Ollama y el modelo Qwen3.5:4b. No requiere instalar Ollama por separado ni pagar por cada consulta al modelo local.

## Descargar Fire Browser 0.10

La descarga completa está en [Releases](https://github.com/santiagonobileseia/firebrowser-portable/releases/latest), dividida en tres partes por el límite de tamaño de GitHub:

1. [Parte 1](https://github.com/santiagonobileseia/firebrowser-portable/releases/download/v0.10/Fire-Browser-Portable-0.10-Windows-x64.zip.001)
2. [Parte 2](https://github.com/santiagonobileseia/firebrowser-portable/releases/download/v0.10/Fire-Browser-Portable-0.10-Windows-x64.zip.002)
3. [Parte 3](https://github.com/santiagonobileseia/firebrowser-portable/releases/download/v0.10/Fire-Browser-Portable-0.10-Windows-x64.zip.003)
4. [Reunir-ZIP.cmd](https://github.com/santiagonobileseia/firebrowser-portable/releases/download/v0.10/Reunir-ZIP.cmd), para reunir las partes usando Windows.

Guardá los cuatro archivos en una misma carpeta y ejecutá Reunir-ZIP.cmd. Este archivo únicamente reúne las tres partes en un ZIP; no instala ni inicia el navegador. Después extraé el ZIP y abrí **Fire Browser.exe** dentro de la carpeta Fire-Browser-Portable. También podés extraer directamente el archivo .001 usando un descompresor compatible con archivos divididos.

**El ZIP de “Code > Download ZIP” contiene estas instrucciones, no el navegador. Usá los archivos de Releases.**

## Requisitos y uso

- Windows x64 compatible con Ollama (Windows 10 22H2 o Windows 11).
- Memoria suficiente para ejecutar el modelo y el navegador; 16 GB de RAM son recomendables. El rendimiento depende del equipo y puede ser lento sin aceleración gráfica.
- Reservá aproximadamente 20 GB libres si vas a conservar las partes, reconstruir el ZIP y extraerlo en el mismo disco.
- Mantené toda la carpeta junta. Para mejor velocidad, copiala del pendrive a un SSD.
- Iniciá sesión en tus cuentas desde el navegador. La distribución pública no contiene sesiones, historial ni credenciales del creador.
- Las páginas web requieren internet. El modelo incluido funciona localmente.

## Funciones

- Navegador Chromium con favoritos y perfiles separados por PC/usuario de Windows.
- Asistente que lee páginas y opera controles de formularios según tus indicaciones.
- Chat con respuestas útiles y detalles técnicos opcionales.
- Perfil de agente y memoria de procedimientos que confirmás expresamente.
- Herramientas para contraseñas cifradas, actualización de Ollama y exportación portable.

## Límites

Versión inicial: la IA puede equivocarse o no completar una tarea. Revisá textos y cambios antes de confirmarlos. Algunos sitios pueden bloquear navegadores integrados. Los controles dibujados en un canvas no son interpretables por el modelo de texto. No se eluden CAPTCHA ni bloqueos de seguridad. No incluye generador de imágenes.

## Integridad y componentes

Los archivos SHA256SUMS.txt de cada versión permiten comprobar las partes descargadas. Se conserva la documentación de licencias incluida de los componentes de terceros dentro del paquete. Este repositorio distribuye el paquete portable; no declara una licencia de código abierto para el código propio de Fire Browser.
