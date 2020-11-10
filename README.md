# Apunts_UF1_1  

<br>

## INTRODUCCIÓN

### Tipos de Software
- **De Sistema**(Sistema operativo, controladores)
- **De Aplicación**(Aplicaciones ofimáticas, navegador, editores de imagen,...)
- **De Desarrollo**(Editores, compiladores, intérpretes,...)

### Relación entre hardware y software
- **Disco duro**: almacena de forma permanente los archivos ejecutables y los archivos de datos.
- **RAM**: almacena de forma **temporal** el código binario de los archivos ejecutables y los archivos necesarios.
- **CPU**: lee y ejecuta las instrucciones almacenadas en la memoria RAM, así como los datos necesarios.
- **E/S**: recoge los datos nuevos desde la entrada, muestran los resultados, se leen/guardan a disco...

### Códigos fuente, objecto y ejecutable
- **Código Fuente**: archivo legible escrito en lenguaje de programación.
- **Código Objeto**(intermediario): archivo binario no ejecutable. 
- **Código ejecutable**: archivo binario ejecutable.

<br>

## DESARROLLO DE SOFTWARE

### Fases principales
#### Ánalisis: 
Se determinan y definen las necesidades del cliente y se especifíca los requisitos que ha de cumplir el software a desarrollar.

  Como ha de ser la especificación de requisitos?
  - Completa y sin omisiones
  - Ser concisa y sin trivialidades
  - Evitar ambigüidades
  - Evitar detalles de diseño o implementación
  - Entendible por el cliente
  - Separar rquisitos funcionales y no funcionales
  - Dividir y jerarquizar el model
  - Fijar criterios de validación
   

#### Diseño: 
Se descopmpone y ordena el sistema de componentes que pueden ser desarrollados por separado y se especifíca la interrelación/funcionaliad de los elementos componentes.

Cuales son las actividades habituales?
- Diseño arquitectónico
- Diseño detallado
- Diseño de datos
- Diseño de interfaz


#### Codificación: 
En esta fase se escribe el código fuente de cada componente.

Que tipos de lenguajes informáticos se pueden utilizar?
- De programación (C, C++, Java, JavaScript,...)
- De otro tipo (HTML, XML, JSON,...)
  

#### Pruebas: 
El principal objetivo de esta fase es conseguir que el programa funcione  de forma incorrecta para poder descubrir posibles defectos. Lo que se hace es someter al programa al máximo número de situaciones diferentes.


#### Mantenimiento: 
Durante la explotación de sistema software es necesario realizar cambios ocasionales, para conseguir eso se ha de rehacer la parte del trabajo realizado en las fases previas.
  
Que tipos de mantenimiento hay?
- Correctivo: sirve para corregir defectos.
- Perfectivo: se mejora la funcionalidad.
- Evolutivo: se añaden funcionalidades nuevas.
- Adaptativo: se adaptan a nuevos entornos.

## MODELOS DE DESARROLLO DE SOFTWARE

### MODELOS CLÁSICOS (PREDICTIVOS)

#### MODELO EN CASCADA

  - Modelo más antiguo.
  - Identifica las dases principales del desarrollo software.
  - Las fases han de realizarse en el orden indicado.
  - El resultado de una face de entrada a la siguiente fase.
  - Modelo bastante rígido que no se adapta bien a futuros cambios/actualizaciones.
  - Existen diferentes variantes.  

#### MODELO EN V

  - Modelo parecido al modelo de cascada
  - Visión jerarquizada en distintos niveles.
  - Mas abstraccion en niveles superiores
  - Niveles interiores mas detallados.
  - El resultado de una fase es la entrada de otra.
  - Existen diferentes variantes.  

### Modelo de construcción de prototipos

  - Los requisitos no están especificados claramente(a menudo):
    - Existencia previa nula.
    - Omisión o falta de concreción de usuario/cliente.
    
  - Proceso:
    - Se crea el prototipo durante la fase de análisis y es probado por el usuario/cliente.
    - El paso anterior se repite las veces necesarias.
  
  - Tipos de prototipos:
    - **Prototipos rápidos**: puede estar desarrollado usando otro lenguaje y/o herramientas i el prototipo al final se desecha.
    - **Prototipos evolutivos**: está diseñado en el mismo lenguaje y herramientas y se usa como base para desarrollar el proyecto.
    
### Modelos evolutivos o incrementales

#### Modelo en espiral (iterativos)
  
  - La actividad de ingeniería corresponde con las fases del modelo.
  - Se da gran importáncia a la reutilización de código.

#### Metodologías ágiles (adaptativos)

  - Métodos de ingeniería del software basados en el desarrollo iterativo e incremental.
  - Los requisitos y soluciones van evolucionando con el tiempo según las necesidades en el proyecto.
  - El trabajo se hace colaborativo mediante los equipos de trabajo.
  - Metdologías más conocidas:
    - Kanban
    - Scrum
    - XP (Programación Extrema)

#### XP (PROGRAMACIÓN EXTREMA): VALORES UTILIZADOS 
  - Simplicidad
  - Comunicación
  - Retroalimentación (comunicacion mútua)
  - Valentía o coraje ()/
  - Respeto o humildad (respetar trabajo entre mútuos)
 
 ## LENGUAJES DE PROGRAMACIÓN
