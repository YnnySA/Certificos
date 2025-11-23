# 🏗️ Generador de Certificados de Obras

Una aplicación web desarrollada con Streamlit para automatizar la gestión, creación y archivo de certificados de facturas de servicios de la construcción. Permite generar informes en Excel, gestionar facturas y mantener un registro centralizado y persistente de toda la documentación para facilitar análisis versátiles y realizar estimados certeros de las producciones.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://generador-de-certificos-3vjv3il7vlh9p2nbjxjppz.streamlit.app/?page=crear)


## 📋 Características

-   🏢 **Gestión Centralizada:** Crea, edita y elimina certificados para múltiples obras de forma sencilla.
-   📊 **Base de Datos Integrada:** Utiliza SQLite para almacenar de forma persistente toda la información de certificados, obras y facturas.
-   📄 **Generación de Informes:** Crea informes profesionales en formato Excel basados en una plantilla predefinida, incluyendo detalles del contrato, facturas y estado.
-   📋 **Gestión de Facturas Dinámica:** Agrega o elimina facturas dinámicamente para cada certificado.
-   🔍 **Búsqueda Avanzada:** Filtra certificados por obra, estado, rango de fechas o contratista para encontrar rápidamente la información que necesitas.
-   ✏️ **Edición Completa:** Permite editar todos los campos de un certificado existente, incluyendo su estado (Activo, Revertido, Cancelado) y comentarios.
-   🎨 **Interfaz Intuitiva:** Diseñada con Streamlit para una experiencia de usuario amigable y eficiente.

## 🛠️ Stack Tecnológico

-   **Frontend:** [Streamlit](https://streamlit.io/)
-   **Backend:** [Python](https://www.python.org/)
-   **Base de Datos:** [SQLite](https://www.sqlite.org/index.html)
-   **Manipulación de Datos:** [Pandas](https://pandas.pydata.org/)
-   **Manejo de Excel:** [Openpyxl](https://openpyxl.readthedocs.io/en/stable/)

## 🚀 Cómo Ejecutar el Proyecto Localmente

Sigue estos pasos para tener una copia del proyecto funcionando en tu máquina local.

### Prerrequisitos

Asegúrate de tener [Python](https://www.python.org/downloads/) instalado en tu sistema.

### Instalación

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/YnnySA/Generador-de-Certificados.git
    cd Generador-de-Certificados
    ```

2.  **Crea un entorno virtual (recomendado):**
    ```bash
    python -m venv venv
    ```

3.  **Activa el entorno virtual:**
    *   En Windows:
        ```bash
        venv\Scripts\activate
        ```
    *   En macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4.  **Instala las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

### Ejecución

1.  Asegúrate de que los archivos `logo.png` y la carpeta `data/ejemplo.xlsx` están en la raíz del proyecto.
2.  Ejecuta la aplicación con Streamlit:
    ```bash
    streamlit run certificos.py
    ```

3.  Abre tu navegador web y ve a la dirección local que se mostrará en la terminal (usualmente `http://localhost:8501`).




## ✍️ Autor

**Yenny Sánchez Aguilar**

*   [GitHub](https://github.com/YnnySA)
*   [LinkedIn](https://www.linkedin.com/in/yenny-sánchez-aguilar-665b26242/)

---




