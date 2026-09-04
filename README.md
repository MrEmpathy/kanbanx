# kanbanx

Instrucciones rápidas para preparar el entorno, instalar dependencias y poner en marcha la aplicación Django.

**Requisitos**
- Python 3.8+ instalado en el sistema (se recomienda usar un entorno virtual).

**Crear y activar un entorno virtual (Linux / macOS)**
1. Crear el entorno:

```bash
python3 -m venv env
```

2. Activar el entorno:

```bash
source env/bin/activate
```

**Activación en Windows (PowerShell)**
```powershell
.\env\Scripts\Activate.ps1
```

Una vez activado, el prompt mostrará el nombre del entorno (por ejemplo `(env)`).

**Actualizar pip y herramientas de empaquetado**

```bash
pip install --upgrade pip 
```

**Instalar Django y dependencias**

Si existe `requirements.txt` en el proyecto:

```bash
pip install -r requirements.txt
```

Si no existe, instalar Django directamente:

```bash
pip install django
```

**Preparar la base de datos y ejecutar la aplicación**

1. Aplicar migraciones:

```bash
python manage.py runserver
```

Accede a la app en `http://127.0.0.1:8000/`.

**Desactivar el entorno virtual**

```bash
deactivate
```
