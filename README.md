## 🏡 GeoLotesSite

 El sistema online propuesto deberá satisfacer las necesidad de los dueños de los terrenos como la de obtención de datos actualizados en todo momento sobre sus bienes, como así también sobre las personas que adquirieron los mismos y/o están en proceso de ello. Así se propone una gestión total del mismo desde la página web. Así mismo también la gestión del marketing y los prospectos que ello pueda obtener.


---

## 🚀 Características

- Mapa interactivo con Leaflet
- Visualización de terrenos con estado (Disponible, Reservado, Vendido)
- Panel de administración para gestionar propiedades
- Vista pública con plantilla HTML
- Estructura lista para desplegar en cualquier entorno

---

## 📦 Requisitos

- Python 3.10+
- Git
- Navegador web moderno

---

## ⚙️ Instalación

## **Clonar el repositorio**

```bash
git clone https://github.com/tu_usuario/GeoLotesSite.git
cd GeoLotesSite

## **Crear y activar entorno virtual**
python -m venv venv
# En Windows:
venv\Scripts\activate
# En Linux/macOS:
source venv/bin/activate

## **Instalar dependencias**
pip install -r requirements.txt

## **Aplicar migraciones**
python manage.py migrate

## **Ejecutar el servidor**
python manage.py runserver

## **Acceder a la app**
Abrí tu navegador en: http://127.0.0.1:8000

