# FOD Manager

Es una aplicación Android desarrollada como Trabajo de Fin de Grado (TFG) de DAM para la gestión de inspecciones, incidencias FOD y control operativo 
en entorno aeronáutico.

## Descripción del proyecto

FOD Manager es una aplicación móvil orientada a mejorar el control y seguimiento de elementos relacionados con la seguridad en plataforma, 
permitiendo registrar inspecciones, gestionar incidencias FOD, administrar usuarios según su rol y consultar información operativa.

La aplicación está diseñada para funcionar en dispositivos Android y utiliza Supabase como backend para la autenticación, la base de datos y 
la lógica de integración con servicios remotos.

## Objetivos

Los principales objetivos del proyecto son:

- centralizar la gestión de usuarios, aeronaves, inspecciones e incidencias FOD
- controlar el acceso a la información en función del rol del usuario
- facilitar el registro de incidencias con información estructurada y evidencia visual
- mejorar el seguimiento operativo mediante paneles de resumen y consulta
- disponer de una solución móvil adaptada a un entorno técnico y profesional

## Funcionalidades principales

- inicio de sesión y control de acceso
- gestión de usuarios por roles
- asignación de usuarios a aeronaves
- alta y consulta de inspecciones
- registro y seguimiento de incidencias FOD
- visualización de dashboard con información resumida
- integración con Supabase para autenticación y persistencia de datos

## Roles de usuario

La aplicación contempla distintos perfiles de usuario con permisos diferenciados:

- Administrador
- Head Plant
- Focal Point FOD
- Mando GP4
- Operario
- Quality

Cada rol dispone de un nivel de acceso distinto en función de sus responsabilidades dentro del sistema.

## Tecnologías utilizadas

- **Kotlin**: desarrollo de la aplicación Android
- **Android Studio**: entorno de desarrollo
- **Supabase**: backend, autenticación y base de datos
- **PostgreSQL**: base de datos relacional gestionada a través de Supabase
- **Git**: control de versiones
- **GitHub**: alojamiento del repositorio



