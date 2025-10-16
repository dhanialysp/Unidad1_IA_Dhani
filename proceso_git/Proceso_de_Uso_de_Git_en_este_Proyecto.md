Proceso de Uso de Git en este Proyecto de resúmenes

 Instalación y Configuración
- git config --global user.name "Dhani"
- git config --global user.email "tuemail@ejemplo.com"

 Inicialización
- mkdir Proyecto_Unidad_I_IA
- cd Proyecto_Unidad_I_IA
- git init (para iniciar el repositorio)

 Agregar Contenido y Commits
- git add para añadir archivos uno por uno y en caso de edición
- git add . (el punto (.) es para agregar todo para agregar todo)
- git commit -m "Agrego resúmenes iniciales"


## Subir a GitHub
- git remote add origin https://github.com/tuusuario/Proyecto_Unidad_I_IA.git
- git push -u origin main

Reorganizaciones
- mkdir resumenes
- move archivos resumenes/
- git add .
- git commit -m "Organizo en carpeta"
- git push 

Renombrar Carpeta
- move resumenes resumenes_dhani
- git add .
- git commit -m "Renombro carpeta"
- git push

Este es un pequeño registro de comandos para control de versiones que utilice para la creación de este repositorio. 