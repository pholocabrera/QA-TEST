# Prueba Técnica - Programador (Back-end)
La siguiente es una prueba para evaluar a los postulantes para un perfil de **Tester**.

## INTRODUCCIÓN
Este repositorio contiene una serie de requerimientos de un Caso Práctico, que busca evaluar las capacidades técnicas del candidato con respecto a las principales funciones y responsabilidades que se requieren dentro del área de Desarrollo de software de Neology.

#### ¿Qué se busca evaluar?
Principalmente los siguientes aspectos:
* Creatividad para resolver los requerimientos,
* Uso de experiencia y conocimiento en base a metodologías para creación de los casos de prueba,
* Eficiencia de los algoritmos entregados,
* Mostrar la experencía y la manera de poder salir de la caja para romper o identificar cualquier falla o mejora,
* Familiaridad con Frameworks y plataformas de pruebas.

## IMPORTANTE
1. Realizar los casos de prueba en jherkin.
2. Recomendamos emplear un máximo de **3 (tres) horas** y enviar todo lo que puedas, se podrá validar con lso registros de Github.
4. Se requiere de una **cuenta de GitHub** para realizar este ejercicio.
5. **Antes de comenzar a contestar:**
    * Realizar un `Fork` de este repositorio
    * Clonar el fork a su máquina local  `git clone git@github.com:USERNAME/FORKED-PROJECT.git`
    * Crear un `branch` en su cuenta de GitHub utilizando su nombre completo.
6. **Al finalizar**, existen 2 (dos) opciones para entregar su proyecto:
    * 1) Realizar un `Commit` de su proyecto, **enviar un `Pull Request` al branch con su NOMBRE**, y notificar a la siguiente dirección de correo electrónico  [vmiranda@neology.mx](mailto:vmiranda@neology.mx).
    * 2) Crear un archivo comprimido (_.zip_ o _.rar_) de su proyecto y enviar a la siguiente dirección de correo electrónico  [vmiranda@neology.mx](mailto:vmiranda@neology.mx).

  NOTA:Como tester buscamos a alguien minucioso por lo que siéntete libre de agregar los comentarios que veas oportunos :D .

## EJERCICIOS

###PARTE 1 - Creación de casos de uso #

Recuerda que en cada escenario de prueba Gherkin debes proporcionar pasos claros, condiciones y resultados esperados. Este examen evalúa tu capacidad para diseñar casos de uso exhaustivos para la aplicación de movilidad, considerando la integración entre el backend, back office y las aplicaciones móviles, agrega los casos de prueba que consideres importante por validar las funcionalidades primordiales.

**Examen de Tester - Casos de Uso con Gherkin para Compañía de Movilidad**

**Instrucciones:**
- Este examen se centra en la creación de casos de uso utilizando jherkin para probar un sitio web que gestiona transacciones reportadas por usuarios desde aplicaciones móviles en iOS y Android, integrando backend, back office y aplicaciones móviles.
- Cada pregunta requiere que escribas escenarios de prueba en formato Gherkin para el caso de uso indicado. Por favor, asegúrate de incluir pasos, condiciones y resultados esperados.
- Se espera que consideres la minuciosidad en las pruebas, especialmente en la integración entre el backend, back office y las aplicaciones móviles, dada la alta carga de transacciones esperadas.

**Pregunta 1: Registro de Usuario desde la Aplicación Móvil (iOS y Android)**

Escribe un escenario de prueba Gherkin para verificar el proceso de registro de un nuevo usuario desde ambas aplicaciones móviles (iOS y Android). Asegúrate de incluir condiciones y resultados esperados.

**Pregunta 2: Reporte de Transacciones desde la Aplicación Móvil (iOS)**

Escribe un escenario de prueba Gherkin para verificar la capacidad de la aplicación móvil en iOS para reportar transacciones. Asegúrate de considerar la integración con el backend y el procesamiento en el back office.

**Pregunta 3: Integración de Backend y Back Office para Procesar Transacciones**

Escribe un escenario de prueba Gherkin para asegurar que las transacciones reportadas desde las aplicaciones móviles (iOS y Android) se procesen correctamente en el backend y el back office.

**Pregunta 4: Visualización de Historial de Transacciones en el Sitio Web**

Escribe un escenario de prueba Gherkin para verificar la funcionalidad que permite a los usuarios ver su historial de transacciones en el sitio web. Asegúrate de considerar la integración entre el frontend del sitio web y el backend.

**Pregunta 5: Pruebas de Rendimiento para Manejar Alta Carga de Transacciones**

Escribe un escenario de prueba Gherkin para evaluar el rendimiento del sistema al manejar una carga alta de transacciones simultáneas. Asegúrate de considerar la integración entre todas las partes del sistema.

**Pregunta 6: Actualización de Estado de Transacción desde la Aplicación Móvil (Android)**

Escribe un escenario de prueba Gherkin para verificar la capacidad de la aplicación móvil en Android para actualizar el estado de una transacción. Asegúrate de incluir pasos, condiciones y resultados esperados.

----

### PARTE 2 Ejercicios técnicos #

**EJERCICIO 1 Escribe un programa en Java que verifique si una palabra es un palíndromo. Un palíndromo es una palabra que se lee igual de izquierda a derecha que de derecha a izquierda.**


**EJERCICIO 2 Crea una clase en Java que represente una cuenta bancaria. La clase debe tener métodos para depositar, retirar y obtener el saldo actual. También, implementa un programa que utilice esta clase para realizar algunas operaciones bancarias básicas.**


**EJERCICIO 3 Genera los referentes identificadores para un mismo elemento en selenium y appium**

---
### PARTE 3 Prreguntas abiertas #

**Pregunta 1: ¡Cuál es la diferencia entre pruebas de carga y estrés?**
Las pruebas de carga son aquellas que nos permite medir la capacidad de respuesta tipo PCR donde se valida el volumen de procesos de un tarea en espeficico, como consultas sumultaneas, accesos o registros.
Las pruebas de estres son aquellas que validan la respuesta ante ataques o errores de captura por parte del usuario que tan vulnerable es el sistema y como mitigar ese tipo de accesos

**Pregunta 2: ¿Qué probarías si tuvieras que probar una nueva versión que solventa un bug crítico en producción?**
Se prueba un test set de regresión para asegurar la no afectación de la nueva versión sobre la existente, se debe validar la corrección del defectos en ambientes previas versionadas, para no afectar a los usuarios finales, se debe probar cada escenario que replica el defecto critico y posterior liberar el fixed y volver a probar en PRO, asegurando que se ha corregido el issue, en caso de que se replique se realiza un rollback para evitar la afectación de otros componentes

**Pregunta 3: ¿Cómo reportarías los bugs encontrados hacía los desarrolladores?**
Se levantan los defectos en las herramientas de administración de preubas y se asignan a la persona responsable de la atención y seguimiento para realizar el fixed

**Pregunta 4: ¿Cómo le darías seguimiento a bugs reportados a Desarrollo?**
Existen herramientas de seguimiento de los defectos, donde por medio de un ticket se reportan los escenarios que han fallado junto con los pasos para replicar el defecto, se agrega una descripción junto con la evidencia que nos permite ver que esta fallando o que se esta incumpliendo dentro de la entrega de SW que se esta validando, una de las herramientas agiles son jira, o ALM defects

**Pregunta 5: ¿Cuál serían los niveles de severidad que manejarías para reportar bugs y con base en qué?**
Alta, media y baja

**Pregunta 6: ¿Puedes explicar qué es la metodología de pruebas Ágil y cuáles son sus principios fundamentales?**
Agil es un marco de trabajo que permite entrgas pequeñas que son MVP, de las cuales se van integrando de manera paulatina, hasta completar el features por spring, se llevan acabo ceremonias de agilidad como los diarios de 15 minutos, los PI plan, las cereminias de planeacions de sprint y retrospectivas y demos al final de cada sprint y PI

**Pregunta 7: ¿Cuál es la diferencia entre pruebas funcionales y pruebas no funcionales? Proporciona ejemplos de cada una.**
Las pruebas funcionales se basan en validar y verificar las features de un requerimiento o historias de usuario, que nos permite confirmar que no existen defectos y que se estan cubriendo todos los criterios establecidos por el usuario
Las pruebas no funcionales son todas aquellas que validan la segurdad, la complejidas, la capacidad de procesos de carga y sobre todo la fiabilidad del sistema

**Pregunta 8: ¿Qué es la automatización de pruebas y cuáles serían algunos casos donde sería más beneficioso automatizar pruebas en lugar de realizar pruebas manuales?
Herramientas y Técnicas de Pruebas:**
Las pruebas que se deben automatizar son todas aquellas que ya fueron identificadas como parte de una test set de regresión de pruebas para validar la no afectación de nuevas implementaciones o integraciones en el sistema
Las pruebas manuales nos permite validad y verificar los nuevos criterios de aceptación de nuevas features
Las herramientas para automatizar depende de lo que se requiere validar, si es una micro service se recomienda utilizar postman, soap o cucumber con lenguaje Gherkin, de las tecnicas de prueba existen las de back end tipo caja negra y blanca (se tiene acceso al codigo), pruebas de estres pruebas de confiabilidad y pruebas de seguridad

**Pregunta 9: ¿Puedes mencionar algunas herramientas populares de automatización de pruebas y describir en qué escenarios podrían ser más útiles?**

**Pregunta 10: ¿Qué casos no automatizarías?**
Features de nueva integración

En Neology somos fieles creyentes de la transparencia, honestidad, crecimiento y aprendizaje  por lo que agradecemos se pueda llevar a cabo la prueba sin ayuda de terceros o herramientas adicionales. 




