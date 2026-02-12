# Minutas

## 2026-02-11

Repaso del plan, meses febrero-marzo.

### Tareas:

#### Stack de Métricas

- Quique y Diego C.: Unifican métricas de mirror para mostrarse públicamente.

#### Stack de logs

- Quique: Busca unificar logs dentro de cluster para avisos de errores, problemas, etc.

#### Nodo de almacenamiento

- Diego C. y Uriel: Planean el estado y flujo de nodo de almacenamiento/respaldos.

#### Mirors de distribuciones Linux

- Mau, Christian F. y Brent: Consolidar mirrors de Fedora y Rocky Linux.

## 2026-01-05

Repaso del plan de trabajo semestral de infraestructura para el primer semestre de 2026.

- Una junta al mes obligatoria la primera semana del mes. Segunda junta opcional para seguimiento la tercera semana del mes.
- Horario de las juntas por definir (después de inscripciones).
- Asignación de trabajos por proyecto.

### Tareas:

#### Cluster de kubernetes

- Quique y Diego C.: Recuperar nodo beta y restaurar alta disponibilidad. **HECHO**

#### Red y conectividad

- Quique y Luis S.: Solucionar intermitencia en mirrors públicos. **HECHO**

## 2025-12-15

### Espejos de distribuciones Linux

- Mau: Ya terminó el fedora sync y se va a contactar a fedora.org mediante correo
- Sandra: Empieza con el sync de mirror de Rocky Linux
- Luis: Reintentará comunicación con Linux Mint para el mirror

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Quique: Pide a gunnar subdominio wiki.lidsol.unam.mx
- Quique: Configura github actions en cluster
- Luis S. y David E.C. : Leen y empiezan a migrar de lidsol/servidor a lidsol/infra

### Monitoreo centralizado

- Luis S.: Ya vió como integrar en grafana el dashboard integrando a prometheus
- Quique: Empezar con instalación de Prometheus y Grafana
- Javier: Crea PR para configuración inicial de Elastic Search para logs
- Quique: Configura lidsol.unam.mx:9000 para elasticsearch

### Cluster de despliegue y pruebas

- PANIC: El cluster perdió nodo beta, se arregla el siguiente año D:

### Plataforma de backups automatizados

- Diego: Diseña sistema de respaldo con longhhorn + restic + restic-server y brtfs en RAID1. 

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Tiene que arreglar una vulnerabilidad.

## 2025-12-08

### Espejos de distribuciones Linux

- Mau: Ya terminó el fedora sync y se va a contactar a fedora.org mediante correo
- Sandra: Empieza con el sync de mirror de Rocky Linux
- Luis: Publicó en el foro buscando medios de contacto para Linux Mint, seguimos esperando respuesta relacionada con el mirror

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Quique: Pide a gunnar subdominio wiki.lidsol.unam.mx
- Quique: Configura github actions en cluster
- Luis S. y David E.C. : Leen y empiezan a migrar de lidsol/servidor a lidsol/infra

### Monitoreo centralizado

- Luis S.: Ya vió como integrar en grafana el dashboard integrando a prometheus
- Quique: Empezar con instalación de Prometheus y Grafana
- Javier: Crea PR para configuración inicial de Elastic Search para logs
- Quique: Configura lidsol.unam.mx:9000 para elasticsearch

### Cluster de despliegue y pruebas

- Quique: Busca remplazar almacenamiento de nodo beta por un disco de mayor capacidad

### Plataforma de backups automatizados

- Diego: Diseña sistema de respaldo con longhhorn + restic + restic-server y brtfs en RAID1. 

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Sigue chambeando.

## 2025-12-01

### Espejos de distribuciones Linux

- Mau: Ya terminó el fedora sync y se va a contactar a fedora.org mediante correo
- Sandra: Empieza con el sync de mirror de Rocky Linux
- Luis: Publicó en el foro buscando medios de contacto para Linux Mint, seguimos esperando respuesta relacionada con el mirror

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Quique: Pide a gunnar subdominio wiki.lidsol.unam.mx
- Quique: Configura github actions en cluster
- Luis S. y David E.C. : Leen y empiezan a migrar de lidsol/servidor a lidsol/infra

### Monitoreo centralizado

- Luis S.: Ya vió como integrar en grafana el dashboard integrando a prometheus
- Quique: Empezar con instalación de Prometheus y Grafana
- Javier: Crea PR para configuración inicial de Elastic Search para logs
- Quique: Configura lidsol.unam.mx:9000 para elasticsearch

### Cluster de despliegue y pruebas

- Diego: Diego se intenta conectar mediante wireguard para arreglar cluster
- Quique: Busca remplazar almacenamiento de nodo beta por un disco de mayor capacidad

### Plataforma de backups automatizados

- Diego: Va a investigar sobre restic, restic-server, btrfs (dedeuplicado y compresion)

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Sigue chambeando.

## 2025-11-03

### Espejos de distribuciones Linux

- Mau: Ya terminó el fedora sync y se va a contactar a fedora.org mediante correo
- Sandra: Empieza con el sync de mirror de Rocky Linux
- Luis: No contestaron desde el correo de Linux Mint, se intentará por otros medios.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Quique: Instala speedtest server en nat
- Agregar una wiki (wiki.js)
- Hostear github actions en cluster
- Luis S. y David E.C. : Leen y empiezan a migrar de lidsol/servidor a lidsol/infra

### Monitoreo centralizado

- Luis S.: Ya vió como integrar en grafana el dashboard integrando a prometheus
- Quique: Empezar con instalación de Prometheus y Grafana
- Javier: Investiga sobre Elastic Search para logs

### Cluster de despliegue y pruebas

- Diego: Diego se intenta conectar mediante wireguard para arreglar cluster
- Quique: Checa almacenamiento distribuido (longhorn)

### Plataforma de backups automatizados

- Diego: Va a investigar sobre restic, restic-server, btrfs (dedeuplicado y compresion)

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Sigue chambeando.

## 2025-10-27

### Espejos de distribuciones Linux

- Mau: Ya terminó el fedora sync y se va a contactar a fedora.org mediante correo
- Sandra: Empieza con el sync de mirror de Rocky Linux
- Luis: No contestaron desde el correo de Linux Mint, se intentará por otros medios.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Agregar una wiki (wiki.js)
- Hostear github actions en cluster
- Luis S. y David E.C. : Leen y empiezan a migrar de lidsol/servidor a lidsol/infra

### Monitoreo centralizado

- Luis S.: Ya vió como integrar en grafana el dashboard integrando a prometheus
- Quique: Empezar con instalación de Prometheus y Grafana
- Javier: Investiga sobre Elastic Search para logs

### Cluster de despliegue y pruebas

- Diego: Diego se intenta conectar mediante wireguard para arreglar cluster
- Quique: Checa almacenamiento distribuido (longhorn)

### Plataforma de backups automatizados

- Diego: Va a investigar sobre restic, restic-server, btrfs (dedeuplicado y compresion)

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Sigue chambeando.

## 2025-10-22

### Espejos de distribuciones Linux

- Mau: Ya terminó el fedora sync y se va a contactar a fedora.org mediante correo
- Sandra: Empieza con el sync de mirror de Rocky Linux
- Luis: Esperando a que nos responda sobre el mirror, en caso de no responder se buscará otro medio de contacto (la siguiente semana)

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Agregar una wiki (wiki.js)
- Hostear github actions en cluster
- Luis S. y David E.C. : Leen y empiezan a migrar de lidsol/servidor a lidsol/infra

### Monitoreo centralizado

- Luis S.: Ya vió como integrar en grafana el dashboard integrando a prometheus
- Quique: Empezar con instalación de Prometheus y Grafana
- Javier: Investiga sobre Elastic Search para logs

### Cluster de despliegue y pruebas

- Diego: Checa el deployment de Nextcloud para implementar el ingress
- Quique: Checa almacenamiento distribuido (longhorn)

### Plataforma de backups automatizados

- Diego: Va a investigar sobre restic, restic-server, btrfs (dedeuplicado y compresion)

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Sigue chambeando.

## 2025-10-13

### Espejos de distribuciones Linux

- Mau: Se realizó el sync inicial del mirror de Fedora, se continúa con el sync incremental y se va a contactar a fedora.org.
- Sandra: Empieza con el sync de mirror de Rocky Linux.
- Luis: Se realizó el deploy de mirror de Linux Mint, se espera la comunicación con la distro para ser listado en su página oficial.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Agregar una wiki (wiki.js)
- Hostear github actions en cluster

### Monitoreo centralizado

- Luis S.: Sigue probando con grafana.
- Quique: Empezar con instalación de Prometheus y Grafana.
- Javier: Investiga sobre Elastic Search para logs.

### Cluster de despliegue y pruebas

- Diego: Se hace deploy de ingress el jueves.

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Agregó proyectos en el github.

## 2025-10-06

### Espejos de distribuciones Linux

- Mau: Se realizó el sync inicial del mirror de Fedora, se continúa con el sync incremental y se va a contactar a fedora.org.
- Sandra: Investiga sobre mirror de Rocky Linux.
- Luis: Se realizó el deploy de mirror de Linux Mint, se espera la comunicación con la distro para ser listado en su página oficial.
- Quique: Va a checar que está ocupando el espacio en /.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Agregar una wiki
- Hostear github actions en cluster

### Monitoreo centralizado

- Luis S.: Investiga sobre los dashboards en grafana.
- Quique: Empezar con instalación de Prometheus y Grafana.
- Javier: Investiga sobre Elastic Search para logs.

### Cluster de despliegue y pruebas

- Diego: Ya tiene deployment de ingress, creará un README para documentar.

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Agregó proyectos en el github.

## 2025-09-29

### Espejos de distribuciones Linux

- Mau: Empieza con el deploy de mirror de Fedora.
- Sandra: Investiga sobre mirror de Rocky Linux.
- Luis: Investiga sobre mirror de Linux Mint.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Agregar una wiki
- Hostear github actions en cluster

### Monitoreo centralizado

- Luis S.: Investiga sobre los dashboards en grafana.
- Quique: Empezar con instalación de Prometheus y Grafana.

### Cluster de despliegue y pruebas

- Diego: Investiga reverse proxy para cluster.
- Quique: Reacondiciona nodo de storage.

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Quique: Agregó proyectos en el github.

## 2025-09-22

### Espejos de distribuciones Linux

- Mau: Empieza con el deploy de mirror de Fedora.
- Sandra: Investiga sobre mirror de Rocky Linux.
- Luis: Investiga sobre mirror de Linux Mint.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Agregar una wiki
- Hostear github actions en cluster

### Monitoreo centralizado

- Quique: Agrega el plan a github projects.

### Cluster de despliegue y pruebas

- Diego: Investiga reverse proxy para cluster.
- Quique: Reacondiciona nodo de storage.

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Sin cambios

## 2025-09-08

### Espejos de distribuciones Linux

- Mau: Empieza con el deploy de mirror de Fedora.
- Sandra: Empieza con el deploy de mirror de Rocky Linux.
- Luis: Investigar sobre mirror de Linux Mint.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Quique: Checa docs de drawDB

### Monitoreo centralizado

- Quique: Investiga sobre opciones de monitoreo (Prometheus, Grafana, Loki, etc).

### Cluster de despliegue y pruebas

- Diego: Investiga e instala devops tools (argoCD, flux, etc).
- Quique: Reacondiciona nodo de storage.

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Todos: Leer reporte de Quique y pensar en que se puede mejorar

## 2025-09-01

### Espejos de distribuciones Linux

- Mau: Investigar sobre mirror de Fedora.
- Sandra: Investigar sobre mirror de Rocky Linux.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Mau: PR para Iac del router con VPN.

### Monitoreo centralizado

- Sin cambios

### Cluster de despliegue y pruebas

- Diego C, Javier y Quique: Pruebas físicas en cluster el jueves (11 - 13)

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

### Apache Beam

- Todos: Leer reporte de Quique y pensar en que se puede mejorar

## 2025-08-18

### Espejos de distribuciones Linux

- Mau: Investigar sobre mirror de Fedora.
- Sandra: Investigar sobre mirror de Rocky Linux.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Mau: PR para Iac del router con VPN.

### Monitoreo centralizado

- Sin cambios

### Cluster de despliegue y pruebas

- Diego C y Javier: Pruebas físicas en cluster el jueves (11 - 13)

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios

## 2025-08-11

### Espejos de distribuciones Linux

- Mau: Investigar y crear un Ansible role para mirror void.
- Diego B: Propone participar en distro de monitoreo.

### Nodo Tor público

- Sin cambios

### Servicios internos del laboratorio

- Sin cambios

### Monitoreo centralizado

- Sin cambios

### Cluster de despliegue y pruebas

- Diego C y Uriel: Instalan cluster k3s HA

### Plataforma de backups automatizados

- Sin cambios

### Infraestructura para ciencia de datos y Machine Learning

- Sin cambios
