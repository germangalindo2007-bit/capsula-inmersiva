# Cápsula inmersiva — Prototipo

Experiencia web para una instalación inmersiva ambientada en una cápsula de eyección espacial.

## Primera etapa implementada
- Interfaz visual de emergencia espacial.
- Vista previa de cámara trasera desde el navegador.
- Botones para iniciar y detener la cámara.
- Cuatro espacios reservados para registros visuales.
- Diseño adaptable a móviles.

## Siguiente etapa
- Integrar MindAR para reconocer las imágenes impresas.
- Generar `targets/targets.mind` a partir de las imágenes elegidas.
- Asociar un audio MP3 a cada objetivo.
- Añadir elementos de realidad aumentada si el proyecto lo requiere.

## Publicar con GitHub Pages
1. Abre el repositorio y entra en **Settings**.
2. En el menú lateral, abre **Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama **main** y la carpeta **/(root)**.
5. Pulsa **Save** y espera a que GitHub publique el sitio.

URL esperada: https://germangalindo2007-bit.github.io/capsula-inmersiva/

## Probar
Abre la URL publicada en Safari o Chrome y pulsa **INICIAR MISIÓN · ACTIVAR CÁMARA**. Acepta el permiso de cámara. La cámara requiere HTTPS; no abras el archivo HTML directamente desde el disco.

## Carpetas
- `targets/`: contendrá el archivo de reconocimiento de MindAR.
- `audios/`: contendrá las grabaciones MP3.
