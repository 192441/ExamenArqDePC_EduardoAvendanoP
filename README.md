# Examen Final Arquitectura de Computadores

## Objetivo

Automatizar el despliegue y eliminación de infraestructura en AWS utilizando CloudFormation y GitHub Actions.

## Tecnologías Utilizadas

* AWS EC2
* AWS CloudFormation
* GitHub Actions
* Git Flow
* Amazon Linux

## Deploy

El workflow Deploy realiza:

* Validación del template CloudFormation.
* Creación del Security Group.
* Creación de la instancia EC2.
* Configuración automática de Apache.
* Publicación de una página web.

## Destroy

El workflow Destroy elimina:

* Stack CloudFormation.
* Instancia EC2.
* Security Group asociado.

## Template EC2

El template despliega:

* Una instancia Amazon Linux.
* Security Group con puerto 80 habilitado.
* UserData para instalar Apache.
* Página web personalizada con HTML, CSS y JavaScript.
