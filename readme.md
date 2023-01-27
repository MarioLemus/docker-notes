# Comandos necesarios para trabajar con Docker

**docker run "nombre-imagen":** corre una imagen existente en docker, y si no existe la descarga y la corre automaticamente

**docker run -d "nombre-imagen":** corre una imagen existente de docker en el background

**docker pull "nombre-imagen":** descarga una imagen

**docker images:** lista todas las imagenes disponibles

**docker images | head:** lista solo las primeras images disponibles (sirve en caso de tener muchas)

**docker ps:** muestra todos los contenedores que estan corriendo

**docker ps -a:** muestra algunos de los contenedores que corrieron hace un tiempo

**docker start "container ID":** reutiliza un contenedor con data existente en especifico

**docker logs "container ID or container NAME":** corre los logs de un contenedor, [finaliza la ejecucion]

**docker logs -f "container ID or container NAME":** corre los logs de un contenedor, [se queda esperando por nuevos logs]

**docker stop "container ID":** finaliza la ejecucion de un contenedor

**docker build -t "custom name" . :** construye un contenedor en la ruta de un proyecto especifico (configurar el Dockerfile primero)

**docker rmi "container ID":** elemina un contenedor
