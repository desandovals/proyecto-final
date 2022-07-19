# Proyecto final

Proyecto final de capacitaciones

## Tooling 

- GitHub
- Ansible
- Jenkins
- Terraform

## Descripción

Crear un sistema que a través de un trigger de Jenkins o Cloud Bluid realice lo siguiente dentro del proyecto `crp-dev-iac-testing`. 

1. Reservar tres IPs.
2. Tres VMs con recursos mínimos y network tag de libre elección asociada, una de las cuales tendrá que ser un nodo de Ansible. 
3. Política de respaldos para las VMs anteriores.
4. Política de encendido / apagado automático para las VMs. 
5. Un Bucket de Google Cloud Storage, especificaciones libres a elegir. 
6. Una regla de Firewall para abrir tunel IAP (puertos 3389 y 22). 
7. Añadir una SA con un rol de lectura.

## Forma de trabajo

Se dividirán en equipos para programar por funcionalidad de acuerdo a su área de especialidad. Lo anterior lo deberán tomar en cuenta para la forma en que se utilizará el versionador. 

## Tooling

Deberán asegurarse de tener las herramientas y permisos necesarios sobre el proyecto de la descripción. 

P.ej. Si requieren de un nodo de Jenkins, uno de los equipos deberá asegurarse de desplegarlo y hacerlo disponible a los demás. 

