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

### Otención de código ejecutable

Para obtener un código binario ejecutable, tenemos 2 opciones:
  - Compilar
  - Interpretar
 
#### Compliar

  Compilar significa que el código que escribimos, lo transformamos a un código
  que entienden las máquinas y de esta forma, obtener un programa ejecutable
  que se pueda leer fácilmente entre ordenadores y máquinas
  
#### Ejemplos lenguajes compilados
  - C, C++
  - Principal ventaja: La ejecución de estos, es muy eficiente.
  - Principal desventaja: Es necesaria la compilación cada vez que modifiquemos el código fuente

#### Interpretar

  En programación, interpretar, és analizar y ejecutar otros programas mediante
  a un programa informático (intérprete).
  
#### Ejemplos lenguajes compilados

  - PHP, Javascript
  - Principal ventaja: El código guente se interpreta de forma directa
  - Principal desventaja: Su ejecución es menos eficiente.
  
### ¿Cual es el proceso de compilación / interpretación?

  - La compilación/interpretación del código se lleva a cabo en 2 tipos de fases:
    - Análisis léxico
    - Análisis sintáctico
  - Si no hay ninguna existencia de errores, se genera el código objeto correspondiente.
  - Un código fuente correctamente escrito no quiere significar que funcione según lo deseado.
  - No se realiza un análisis semántico.
  
### JAVA

  - Lenguajes compilado e interpretado
  - El código fuente Java se compila y se obtiene un código binario intermedio que se denomina **bytecode.
  - Se puede considerar como un código objeto pero destinado a la máquina virtual de Java en lugar de código objeto nativo.
  - Después, el **Bytecode** se interpreta para ejecutarlo.
  - Ventajas:
    - Estructurado y orientado a objetos.
    - Relativamente su aprendizaje es fácil.
    - Buena documentación y base de usuarios
  - Desventajas:
    - Menos eficiente que los lenguajes compilados

### Tipos
  - Según la forma en la que operan:
    - **Declarativos**: indicamos el resultado sin especificar préviamente los pasos a realizar.
    - **Imperativos**: indicamos los pasos a seguir para obtener un resultado a cabo.
  
  - Tipos de lenguajes **declaratvos**:
    - Lógicos: Utilizan reglas
    - Funcionales: Utilizan funciones
    - Algebráicos: Utilizan sentencias
  - Normalmente son lenguajes interpretados.<br>

  - Tipos de lenguajes **imperativos**:
    - Son estructurados
    - Están orientados a objetos
    - Son multiparadigma
  - Los lenguajes orientados  a objetos son también lenguajes estructurados.
  - Muchos de estos lenguajes son compilados.<br>

  - Tipos de lenguajes según su nivel de **abstacción**:
    - Bajo nivel: ensamblador
    - Medio nivel: C
    - Alto nivel: C++, Java
    
### Criterios para la selección de un lenguaje de programación

  A la hora de elegir un lenguaje de programación para hacer desarrollo de software, hemos de tener en cuenta unos criterios básicos, estos són:

  - En que campo aplicación se encuentra.
  - Tener experiéncia previa.
  - Que herramienta de desarrollo se utilitza.
  - Mirar si hay una documentación disponible.
  - Tener una base de usuarios.
  - Si el lenguaje es reusable i portable.
  - Iposición de nuestro cliente.
