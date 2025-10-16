# 🏡 GeoLotesSite

**GeoLotesSite** es una aplicación web desarrollada con Django que permite visualizar terrenos disponibles en Encarnación, Paraguay, mediante un mapa interactivo basado en Leaflet. Ideal para inmobiliarias que desean mostrar sus propiedades de forma dinámica y accesible.

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

