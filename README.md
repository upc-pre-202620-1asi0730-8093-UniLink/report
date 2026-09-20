# UniLink — Aplicación web de soporte técnico empresarial

Universidad: Universidad Peruana de Ciencias Aplicadas (UPC)  
Curso: Aplicaciones Web  
Profesor: Efraín Ricardo Bautista Ubillus  
Sección: 1ASI0730
Grupo: 3
Startup: UniLink  
Nombre del producto: CompuCare 

## Integrantes

| Nombre completo | Código de estudiante |
|---|---|
|Matthew Shinko Okuhama Diaz|u202419311|
|Fernando André Condezo Pacheco|u202411324|
|Sergio Luis Miranda Romero| u20231b331|
|Antony David Yauri Barrios| u202214499|

# Capítulo I: Introducción

## 1.1. Presentación de la startup

UniLink es una startup académica orientada al desarrollo de soluciones
digitales que faciliten la gestión de servicios para empresas. Su propuesta
actual se enfoca en el mantenimiento y reparación de computadoras mediante
un modelo de suscripción mensual.

La startup propone centralizar la contratación y organización del soporte
técnico a través de una aplicación web. Desde esta plataforma, las empresas
podrán registrar solicitudes, consultar al técnico asignado, conocer el
estado de las atenciones y acceder al historial de sus equipos.

UniLink se encargará de seleccionar, capacitar y coordinar a los técnicos
responsables de brindar el servicio. Asimismo, gestionará su pago mediante
los ingresos provenientes de las suscripciones y los servicios adicionales
aprobados por las empresas.

### 1.1.1. Misión

Brindar a las empresas una forma organizada y accesible de gestionar el
mantenimiento y reparación de sus computadoras, mediante una plataforma
web que permita solicitar soporte técnico, dar seguimiento a las
atenciones y conocer la cobertura de su suscripción.

### 1.1.2. Visión

Consolidarnos como una alternativa de soporte técnico empresarial que
destaque por la transparencia de sus planes, la organización de sus
atenciones y el seguimiento del estado de los equipos informáticos.

### 1.1.3. Presentación del equipo

El equipo está integrado por estudiantes de la Universidad Peruana de
Ciencias Aplicadas que colaboran en el análisis, diseño y desarrollo de
una aplicación web para la gestión de soporte técnico empresarial.

Cada integrante contribuye con sus conocimientos y habilidades en las
actividades del proyecto. El trabajo se organiza mediante la distribución
de responsabilidades y el uso de un repositorio compartido en GitHub.

| Integrante | Presentación y contribución |
|---|---|
| [Nombre completo] | [Breve presentación, habilidades y responsabilidad en el proyecto] |
| Yauri Barrios, Antony David | Soy estudiante de Ingeniería de Software, tengo 22 años y trabajo con los stacks MERN y PERN. Me gusta trabajar en equipo, compartir conocimientos y seguir aprendiendo de mis compañeros para mejorar constantemente. |
| [Nombre completo] | [Breve presentación, habilidades y responsabilidad en el proyecto] |
| [Nombre completo] | [Breve presentación, habilidades y responsabilidad en el proyecto] |

## 1.2. Descripción de la problemática

Las computadoras son herramientas necesarias para las actividades
cotidianas de muchas empresas. Su funcionamiento permite realizar tareas
administrativas, gestionar información y mantener la comunicación con
clientes y colaboradores.

Cuando un equipo presenta una falla, el trabajador puede tener dificultades
para continuar sus actividades. En las empresas que no cuentan con personal
propio de soporte técnico, atender estos problemas requiere buscar un
especialista externo y coordinar su disponibilidad.

La problemática que se propone investigar es la dificultad para organizar
estas atenciones cuando las solicitudes, coordinaciones y antecedentes de
los equipos se encuentran dispersos en llamadas, mensajes u otros medios.

Esta situación puede dificultar la identificación del responsable de cada
atención, el seguimiento del trabajo realizado y la consulta de
reparaciones anteriores. Asimismo, la empresa puede tener poca claridad
sobre los servicios que tiene contratados y los costos adicionales que
podría asumir.

Estas necesidades constituyen el punto de partida del proyecto y deberán
validarse mediante la investigación con representantes y trabajadores de
las empresas del segmento objetivo.

### 1.2.1. Formulación del problema

¿Cómo facilitar la gestión del mantenimiento y reparación de computadoras
en empresas que no cuentan con un área propia de soporte técnico,
permitiendo organizar solicitudes, dar seguimiento a las atenciones y
conocer la cobertura y el consumo de los servicios contratados?

## 1.3. Descripción de la solución propuesta

Se propone desarrollar una aplicación web que permita a las empresas
contratar servicios de mantenimiento y reparación de computadoras mediante
una suscripción mensual.

La plataforma permitirá que los empleados registren solicitudes indicando
el equipo afectado, su ubicación y una descripción del problema. El
administrador de UniLink revisará la solicitud y asignará un técnico
responsable de atenderla.

Durante la atención, el técnico podrá registrar el diagnóstico, actualizar
el estado de la solicitud e indicar las actividades realizadas. La empresa
podrá consultar esta información y conservar un historial de las
intervenciones de cada equipo.

Las atenciones podrán ser remotas o presenciales, según las características
del problema y la cobertura contratada.

### 1.3.1. Modelo de suscripción

La empresa pagará una mensualidad que incluirá una cantidad determinada
de horas de soporte correctivo y mantenimientos preventivos, según el
plan contratado.

Como propuesta inicial para el proyecto académico, se consideran los
siguientes planes:

| Plan | Horas de soporte correctivo por mes | Mantenimientos preventivos por mes |
|---|---:|---:|
| Básico | 4 horas | 1 equipo |
| Empresarial | 8 horas | 2 equipos |
| Integral | 16 horas | 4 equipos |

Todos los planes incluirán el registro y seguimiento de solicitudes, la
consulta del consumo de beneficios y el historial de atención por equipo.

Las cantidades presentadas son referenciales y deberán validarse durante
el desarrollo del proyecto. Los precios se establecerán considerando los
costos de personal técnico, traslados, herramientas y operación de la
plataforma.

El registro de solicitudes no implicará soporte ilimitado. El tiempo
utilizado en las intervenciones correctivas se descontará de las horas
disponibles en el plan. Los mantenimientos preventivos se descontarán de
su cupo correspondiente y no consumirán horas de soporte correctivo.

### 1.3.2. Servicios adicionales

Cuando la empresa agote las horas de soporte o los mantenimientos
incluidos, podrá solicitar servicios adicionales mediante una cotización.

Los repuestos y componentes necesarios para una reparación tampoco
estarán incluidos en la mensualidad. Su costo será informado por separado.

El responsable de la empresa deberá aprobar la cotización antes de que
se realice el trabajo que genere un cobro adicional. De esta manera,
podrá conocer y autorizar los gastos que excedan su suscripción.

### 1.3.3. Usuarios de la plataforma

La aplicación contará con los siguientes usuarios y responsabilidades:

| Usuario | Funciones principales |
|---|---|
| Responsable de la empresa | Consultar el plan y su consumo, gestionar empleados y equipos, revisar solicitudes y aprobar cotizaciones adicionales. |
| Empleado | Registrar problemas en los equipos y consultar el estado de sus solicitudes. |
| Técnico | Consultar las solicitudes asignadas, registrar diagnósticos, actualizar avances y documentar el tiempo y trabajo realizado. |
| Administrador de UniLink | Gestionar empresas, planes y técnicos; asignar solicitudes; validar consumos y supervisar las atenciones. |

Cada empresa accederá únicamente a su propia información. Los técnicos
podrán consultar la información necesaria para atender las solicitudes
que les hayan sido asignadas.

## 1.4. Segmentos objetivo

### 1.4.1. Segmento principal: pequeñas y medianas empresas

La solución estará dirigida a pequeñas y medianas empresas que utilizan
computadoras en sus actividades y no cuentan con un área propia de
soporte técnico.

Entre los posibles clientes se encuentran oficinas administrativas,
estudios contables, agencias y otros negocios que requieren mantener
operativos sus equipos informáticos.

Estas empresas contratarán y pagarán la suscripción para que sus
trabajadores puedan solicitar atención dentro de la cobertura del plan.

### 1.4.2. Usuarios dentro de la empresa

Los responsables administrativos o encargados de los equipos necesitarán
consultar las solicitudes de su organización, supervisar las atenciones,
revisar el consumo de la suscripción y aprobar gastos adicionales.

Los empleados utilizarán la plataforma para reportar fallas y conocer
el avance de sus solicitudes sin tener que coordinar directamente la
contratación de un técnico externo.

### 1.4.3. Usuarios operativos del servicio

Los técnicos y el administrador de UniLink utilizarán la plataforma para
organizar y ejecutar las atenciones.

Los técnicos registrarán el diagnóstico y los trabajos realizados,
mientras que el administrador coordinará la asignación de solicitudes y
verificará su correspondencia con los beneficios contratados.

## 1.5. Objetivos del proyecto

### 1.5.1. Objetivo general

Desarrollar una aplicación web que permita gestionar servicios de
mantenimiento y reparación de computadoras para empresas mediante
suscripciones mensuales, centralizando las solicitudes, la asignación
de técnicos, el seguimiento de las atenciones y el control de los
beneficios contratados.

### 1.5.2. Objetivos específicos

- Permitir que los empleados registren solicitudes de soporte indicando
  el problema, el equipo afectado y su ubicación.

- Facilitar la asignación de técnicos y la actualización del estado de
  cada solicitud.

- Permitir a las empresas consultar las horas de soporte y los
  mantenimientos disponibles en su suscripción.

- Gestionar cotizaciones adicionales por excedentes de servicio o
  repuestos, sujetas a la aprobación de la empresa.

- Conservar un historial de diagnósticos e intervenciones por equipo.

- Proporcionar accesos y permisos según las responsabilidades de cada
  usuario.

## 1.6. Propuesta de valor

La propuesta de valor de UniLink consiste en ofrecer soporte técnico
empresarial con una cobertura mensual definida y un proceso de atención
que pueda ser consultado desde una misma plataforma.

La empresa podrá conocer qué incluye su suscripción, cuánto ha utilizado,
quién atiende cada solicitud y qué trabajos se realizaron en sus equipos.

La combinación de seguimiento de solicitudes, historial por equipo y
aprobación de cobros adicionales busca brindar mayor organización y
transparencia en la gestión del soporte técnico.

## 1.7. Alcance inicial de la solución

La primera versión de la solución contemplará:

- Una landing page para presentar el servicio, los planes y la startup.
- Registro e inicio de sesión con permisos según el rol.
- Gestión de empresas, empleados y equipos.
- Consulta de planes y registro de suscripciones.
- Creación y seguimiento de solicitudes.
- Asignación de técnicos.
- Registro del tiempo de atención y consumo de beneficios.
- Elaboración y aprobación de cotizaciones adicionales.
- Consulta del historial de atención por equipo.

Para la demostración académica se propone simular los pagos de
suscripciones y servicios adicionales. La incorporación de una pasarela
de pagos real dependerá del alcance establecido para el curso.

No se contemplan inicialmente una aplicación móvil nativa,
geolocalización de técnicos en tiempo real, atención permanente durante
las 24 horas ni servicios de otras especialidades.

Este alcance corresponde a la solución propuesta para el proyecto.
Las funcionalidades que se implementen en cada entrega se organizarán
según el cronograma y los requisitos del curso.


