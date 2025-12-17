# Proyecto Flask – Sistema Web Biblioteca

Este proyecto es una aplicación web desarrollada con **Flask (Python)**. Incluye archivos **HTML** para el frontend y un archivo principal **app.py** para el backend.

---

## Requisitos

Antes de ejecutar el proyecto, asegurate de tener instalado:

* **Python 3.8 o superior**
* **Git Bash** (en Windows)
* **pip** (se instala junto con Python)

Para verificar que Python está instalado:

```bash
python --version
```

---

## Estructura del proyecto

```
Biblio-main/
│
├── app.py              # Archivo principal de Flask
├── templates/          # Archivos HTML
├── static/             # CSS, JS, imágenes (si aplica)
├── requirements.txt    # Dependencias del proyecto (si aplica)
└── README.md
```

---

## Pasos de ejecución (Git Bash)

### 1. Abrir Git Bash en la carpeta del proyecto

```bash
cd /c/Users/Usuario/Desktop/Biblio-main
```

---

### 2. Crear un entorno virtual

```bash
python -m venv venv
```

Activar el entorno virtual:

```bash
source venv/Scripts/activate
```

Si se activó correctamente, se verá `(venv)` al inicio de la línea.

---

### 3. Instalar Flask

```bash
pip install flask
```

---

### 4. Ejecutar la aplicación

```bash
python app.py
```

---

### 5. Abrir la aplicación en el navegador

Ingresar en el navegador a:

```
http://127.0.0.1:5000
```

---

## Notas

* El proyecto está pensado para ejecutarse en entorno local.
* El uso de `debug=True` permite ver errores en tiempo real durante el desarrollo.
