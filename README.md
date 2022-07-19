# Proyecto final

## Descripción

Crear un sistema que a través de un trigger de Jenkins o Cloud Bluid realice lo siguiente dentro del proyecto `crp-dev-iac-testing`. 

1. Generar Service Accounts para reservar IPs, generar VMs, crear resource policies, crear Buckets, reglas de Firewall y usar Cloud Build. (Una SA por componente).
2. Reservar tres IPs.
3. Tres VMs con recursos mínimos y network tag de libre elección asociada, una de las cuales tendrá que ser un nodo de Ansible. 
4. Política de respaldos para las VMs anteriores.
5. Política de encendido / apagado automático para las VMs. 
6. Un Bucket de Google Cloud Storage, especificaciones libres a elegir. 
7. Una regla de Firewall para abrir tunel IAP (puertos 3389 y 22). 

## Forma de trabajo

Se dividirán en equipos para programar por funcionalidad de acuerdo a su área de especialidad. Lo anterior lo deberán tomar en cuenta para la forma en que se utilizará el versionador. 

## Tooling

Deberán asegurarse de tener las herramientas y permisos necesarios sobre el proyecto de la descripción. 

P.ej. Si requieren de un nodo de Jenkins, uno de los equipos deberá asegurarse de desplegarlo y hacerlo disponible a los demás. 

- GitHub
- Ansible
- Jenkins
- Terraform
