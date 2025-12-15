## 📄 Documentación LaTeX (Generación de PDF)

Si deseas trabajar con la documentación en formato LaTeX (por ejemplo, `docs/outlier_analysis.tex`) y generar el PDF correspondiente, sigue estas instrucciones.

### 1. Instalar MiKTeX (Distribución LaTeX para Windows)

MiKTeX es una distribución de LaTeX esencial para compilar archivos `.tex` a `.pdf` en Windows.

*   **Descargar MiKTeX:** Visita el sitio web oficial de MiKTeX y descarga el instalador recomendado:
    [https://miktex.org/download](https://miktex.org/download)
*   **Instalación:** Ejecuta el instalador y sigue las instrucciones. Se recomienda una instalación "Completa" para asegurar que todas las librerías necesarias estén disponibles. Asegúrate de permitir que MiKTeX instale paquetes "on the fly" (cuando sea necesario).

### 2. Instalar la Extensión LaTeX Workshop en VS Code

La extensión "LaTeX Workshop" para VS Code facilita enormemente la edición y compilación de documentos LaTeX.

*   **Abrir VS Code.**
*   Ve a la vista de Extensiones (Ctrl+Shift+X).
*   Busca "LaTeX Workshop" e instálala.

### 3. Compilar `outlier_analysis.tex` desde VS Code

Una vez que tengas MiKTeX instalado y la extensión de LaTeX Workshop en VS Code, puedes compilar el archivo:

*   **Abrir el proyecto:** Abre la carpeta `diabetes-predictor` en VS Code.
*   **Navegar al archivo:** Abre el archivo `docs/outlier_analysis.tex`.
*   **Compilar:**
    *   Haz clic en el icono del "Biberón" (LaTeX Workshop) en la barra de actividades de VS Code.
    *   En la sección "Build LaTeX Project", haz clic en "Build LaTeX project".
    *   Alternativamente, puedes usar el atajo de teclado por defecto: `Ctrl+Alt+B`.
*   **Ver el PDF:**
    *   Una vez compilado, puedes ver el PDF generado haciendo clic en el icono "View LaTeX PDF" (una lupa con un archivo PDF) en la barra de herramientas de LaTeX Workshop o usando el atajo `Ctrl+Alt+V`.
    *   El archivo `outlier_analysis.pdf` se generará en la carpeta `docs/`.

---
