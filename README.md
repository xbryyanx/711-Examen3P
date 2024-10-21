# Examen Parcial: Despliegue de Infraestructura con Terraform
> [!NOTE]
Este proyecto despliega una infraestructura de nube utilizando Terraform. La infraestructura incluye una máquina virtual que, cuando se crea, instala Docker y ejecuta un archivo docker-compose.yml para obtener varios servicios. La implementación y destrucción de la infraestructura se gestiona a través de GitHub Actions, y el estado de Terraform se almacena en un contenedor de almacenamiento de Azure.


## Contenidos del repositorio:

•	Archivo main.tf donde se define la infraestructura Terraform

•	El docker-compose.yml donde está la configuración de los contenedores.

•	Y  el  .github/workflows/deploy.yml donde se configuraron los Github Actions para automatizar el despliegue y destrucción de la infraestructura 
