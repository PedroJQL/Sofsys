## DESCRIPCION DE PROYECTO
-El proyecto se basa en un apagina web estatica el cual tiene diversas pestañas para la interaccion con el usuario
-El proyecto se basa en HTML, CSS y JavaScript
-Con el objetivo de simular una venta de elementos tecnologicos en linea el cual cuenta con una pestaña principal
de productos destacados, una pestaña secundaria donde se encuentran todos los productos, una pestaña en la cual estan los productos por categorias y una pestaña de nosotros en la cual hay unas tarjeats de informacion de los desarrolladores y enlace a 
proyectos y un formulario de contacto.

## INSTRUCCIONES PARA CLONAR Y CONFIGURAR EL PROYECTO

--


## Flujo de Trabajo para Control de Versiones y Colaboración

Este proyecto utiliza un flujo de trabajo basado en Git para facilitar el desarrollo colaborativo, el control de versiones, y la integración continua. El objetivo es mantener una base de código estable mientras permitimos que los desarrolladores trabajen de manera independiente en nuevas funcionalidades, correcciones de errores, y mejoras.

### Creación de Nuevas Ramas

Para empezar a trabajar en una nueva funcionalidad o corrección, sigue estos pasos:

1. Asegúrate de estar en la rama  o `main` (dependiendo de tu flujo de trabajo):
   ```bash
   git checkout main o master

Crea una nueva rama:
git checkout -b feature/nueva-funcionalidad

Realiza los cambios en tu rama y haz commits regularmente.

### 4. **Commits y Mensajes de Commit**

Proporciona pautas sobre cómo escribir mensajes de commit claros y concisos, y con qué frecuencia hacer commits.

### Commits y Mensajes de Commit

Los commits deben ser atómicos y describir claramente el cambio realizado. Utiliza el siguiente formato para los mensajes de commit:

### Integración de Cambios (Pull Requests)

Cuando hayas terminado tu trabajo en una rama, sigue estos pasos para integrar los cambios:

1. Asegúrate de que tu rama esté actualizada con `develop` o `main`:
   ```bash
   git checkout develop
   git pull origin develop
   git checkout feature/nueva-funcionalidad

## Empuja tu rama al repositorio remoto:
git push origin feature/nueva-funcionalidad


2. Clonación de repositorio 
   
   pasos:  
   ## clonamos el repositorio remoto al local
          git clone https://github.com/Kristennssen/Sofsys.git
   ## creamos la rama en nuestro repositorio local
          git checkout -b rama_cc
   ## verificamos que se allá creado correctamente
          git branch 
   ## nos dirijimos a la carpeta donde fue creada
          cd /Sofsys
   ## despues de haber hechos cambios al repositorio realizamos un git add
          git add . 
   ## seguidamente de un commit 
          git commit -m " se clono el repositorio "
   ## y por ultimo realizamos un push para subir nuestros cambios al repositorio remoto 
          git push origin rama_cc 
   ## por ultimo verificamos en github y realizamos un pull request para subir los cambios
   ## y esperamos a que se realize un merge por parte de los colaboradores o el administardor del repositorio.

3. Deployment en azure 
   ##  creamos un grupo de recursos en azure 
   ##  seguidamente se crea una nueva aplicacion web estatica
   ##  procedemos a agregar nuestra cuenta de github
   ##  agregamos el repositorio a utilizar
   ##  procedemos a ubicarnos a la rama a utilizar la cual seria la master
   ##  creamos la apliacion y esperamos a que realize el workflow  de Actions en github
   