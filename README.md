# Move-OUT — Análisis del Mercado Inmobiliario en Barcelona (2023–2025)

Este proyecto contiene el procesamiento, la limpieza de datos y la visualización de la evolución del mercado inmobiliario (compraventa y alquiler) en la ciudad de Barcelona para el período **2023–2025**.

---

## Guía de Instalación y Configuración

Sigue los pasos indicados a continuación en tu terminal para configurar el entorno virtual de Python, instalar las librerías necesarias y ejecutar el notebook de análisis.

---

### 1. Abrir la terminal y situarse en la carpeta del proyecto

Abre tu terminal (PowerShell, CMD o Terminal) y navega hasta el directorio raíz del proyecto:

```bash
cd ruta/hasta/Move-OUT
```

---

### 2. Crear el entorno virtual (`venv`)

Crea un entorno virtual de Python ejecutando:

* **En Windows:**
  ```bash
  python -m venv venv
  ```

* **En macOS / Linux:**
  ```bash
  python3 -m venv venv
  ```

---

### 3. Activar el entorno virtual

Activa el entorno virtual antes de instalar paquetes o ejecutar el proyecto:

* **En Windows (PowerShell):**
  ```powershell
  .\venv\Scripts\Activate.ps1
  ```


* **En Windows (Command Prompt / CMD):**
  ```cmd
  .\venv\Scripts\activate.bat
  ```

* **En macOS / Linux:**
  ```bash
  source venv/bin/activate
  ```

*(Sabrás que está activado cuando veas el prefijo `(venv)` al inicio de la línea de comandos).*

---

### 4. Instalar las dependencias (`requirements.txt`)

Con el entorno virtual activado, actualiza `pip` e instala todos los paquetes necesarios con el siguiente comando:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

### 5. Abrir y ejecutar `move-out.ipynb`

Para procesar los datos y visualizar los resultados:

1. Inicia Jupyter Notebook desde la terminal:
   ```bash
   jupyter notebook
   ```
   *(O abre tu entorno de desarrollo habitual, como VS Code, e indica que use el Kernel del entorno `venv`).*

2. Entra en el archivo del notebook: **`move-out.ipynb`** (o `Move-OUT.ipynb`).

3. Confirma que el Kernel de Python seleccionado corresponda al entorno virtual **`venv`**.

4. **Ejecuta las celdas una a una (de forma secuencial)** presionando `Shift + Enter` desde la primera celda hasta el final para cargar los datos, limpiarlos, construir las tablas agregadas y renderizar las gráficas.

