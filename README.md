README.md

Plataforma Educativa sobre la lengua Otomí y su cultura de la comunidad de las Moras.
Proyecto integración de la carrera de programación 3er Semestre grupo 304

-Página principal *Videojuegos* Las 6 casas de resguardo* lecciones interactivas.

#Tecnologías

-Backend:Django + Django REST Framework (carpeta backend/)
-Frontend: React + VIte ( carpeta frontend/)



##Instalacion del backend

cd backend
python -m venv env
.\env\Scripts\Activate.ps1
pip inistall -r requiriments.txt
copy .env.example .env  #y llenar los valores 
python manage.py migrate
python manage.py runserver

##Instalación del frontend
cd forntend
npm install
copy .env.example .env
npm run dev