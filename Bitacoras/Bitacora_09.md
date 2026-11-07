# S09 - Desarrollo Técnico y Planificación del Prototipo MyHub

**Semana:** 9  
**Fecha:** 20 de octubre de 2026   
**Proyecto:** MyHub – Hub Providencia  
**Equipo:** Agatha Meza, Deyanira Muñoz, Kevin Maicol Stuardo Miranda y Ruth Gómez

---

## 1. Objetivo de la sesión

Profundizar en los aspectos técnicos y operativos de nuestra propuesta MyHub, identificando los requerimientos necesarios para desarrollar un prototipo funcional y estableciendo cómo podría evaluarse su funcionamiento dentro del Hub Providencia.

## 2. Desarrollo de la propuesta

### A. Definición de los usuarios del sistema

Consideramos los diferentes tipos de personas que interactuarían con MyHub, ya que cada una tendría necesidades distintas.

**Usuarios principales:**
- Visitantes que ingresan al Hub para trabajar, emprender o participar en actividades.
- Personal de recepción encargado de orientar y asistir a los visitantes.
- Personal administrativo que necesita consultar registros e información sobre el uso de las instalaciones.

A partir de esto, planteamos que la plataforma debería contar con distintos niveles de acceso, de manera que cada usuario pueda utilizar únicamente las funciones que le correspondan.

### B. Funcionamiento del registro mediante código QR

Profundizamos en el proceso que seguiría un visitante desde su inscripción hasta el término de su visita.

La idea es que cada persona se registre una sola vez en la plataforma y obtenga una credencial digital con un código QR personal.

En sus siguientes visitas, podría utilizar esta credencial para registrar su ingreso mediante un tótem ubicado en recepción.

El sistema también permitiría seleccionar el espacio que utilizará y registrar su salida al finalizar la visita.

Para evitar inconsistencias, consideramos necesario contemplar situaciones como:

- Lectura repetida de un mismo código QR.
- Intentos de registrar una salida sin un ingreso previo.
- Usuarios que olviden registrar su salida.
- Problemas de conexión durante el proceso.

Estas situaciones deberán revisarse durante las pruebas del prototipo.

### C. Organización y almacenamiento de la información

Otro aspecto importante fue definir qué información necesitaría almacenar MyHub.

Para una primera versión, proponemos considerar:

- Identificador del usuario.
- Fecha y hora de ingreso.
- Fecha y hora de salida.
- Espacio utilizado.
- Estado del registro de visita.

Estos datos se almacenarían en una base de datos centralizada, permitiendo mantener un historial organizado de las visitas.

También consideramos importante limitar la recopilación de información personal a los datos necesarios y establecer medidas de seguridad para protegerlos.

## 3. Indicadores para evaluar el funcionamiento

Para comprobar si MyHub representa una mejora respecto al sistema actual, propusimos utilizar algunos indicadores.

| Indicador | ¿Qué permitiría evaluar? |
|---|---|
| Tiempo de registro | Rapidez del proceso de ingreso |
| Visitas registradas | Cobertura del sistema |
| Registros de salida | Cantidad de visitas con ingreso y salida completos |
| Errores del sistema | Problemas durante el registro |
| Frecuencia de visitas | Uso recurrente de las instalaciones |

Estos indicadores podrían visualizarse posteriormente mediante un panel administrativo.

## 4. Planificación de una prueba piloto

Como siguiente etapa, planteamos realizar una prueba inicial en un acceso o área del Hub, previa coordinación con su administración.

La finalidad sería observar cómo funciona el sistema en condiciones reales antes de considerar su implementación en todo el edificio.

**Etapas propuestas:**

1. Preparar una versión básica de la plataforma.
2. Configurar un dispositivo para la lectura de códigos QR.
3. Comprobar que los registros se almacenen correctamente.
4. Realizar pruebas de ingreso y salida.
5. Recopilar observaciones del personal y los usuarios.
6. Identificar errores y realizar mejoras.

La prueba permitiría evaluar tanto el funcionamiento técnico como la facilidad de uso.

## 5. Recursos y aspectos pendientes

Para avanzar hacia el desarrollo del prototipo, identificamos algunos elementos que sería necesario evaluar.

**Recursos tecnológicos:**
- Computador o tablet con cámara.
- Conexión a internet.
- Plataforma web.
- Sistema de generación y lectura de códigos QR.
- Base de datos.
- Panel administrativo.

**Aspectos por definir:**
- Herramientas de programación que se utilizarán.
- Disponibilidad de equipamiento en el Hub.
- Responsables del mantenimiento.
- Medidas de protección de datos.
- Costos asociados al desarrollo y funcionamiento.

En esta etapa no se ha establecido una tecnología definitiva, ya que primero será necesario evaluar las alternativas disponibles.

## 6. Aprendizaje de la sesión

Esta etapa nos permitió comprender que el desarrollo de una solución digital requiere considerar tanto su funcionamiento técnico como la experiencia de quienes la utilizarán.

También reconocimos la importancia de definir qué información se necesita recopilar y cómo se evaluará si la propuesta realmente contribuye a solucionar los problemas identificados.

## 7. Próximos pasos

- Continuar definiendo los requerimientos del prototipo.
- Investigar herramientas para desarrollar MyHub.
- Elaborar un esquema de la estructura del sistema.
- Evaluar la factibilidad técnica y económica.
- Preparar los avances para la siguiente revisión del proyecto.

---

[Volver al índice de sesiones](README.md) · [Inicio del proyecto](../README.md)
