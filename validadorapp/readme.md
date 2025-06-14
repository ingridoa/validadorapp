##### Práctico: Análisis Estático de Código con SonarQube y Maven

Integrantes grupo N°10. Ingrid Oñate A
			Gabriel Balbontín
			Víctor Diaz

### 1. ¿Qué tipo de errores detectó SonarQube que podrían haber pasado desapercibidos?
SonarQube detectó errores como código duplicado, malas prácticas de programación, uso de variables no inicializadas, y potenciales vulnerabilidades de seguridad. También señaló problemas de formato y legibilidad del código, los cuales no habrían sido detectados fácilmente con pruebas manuales o dinámicas.

### 2. ¿Qué ventajas tiene el análisis estático respecto al dinámico?
El análisis estático (como el que realiza SonarQube) permite detectar errores antes de ejecutar la aplicación, revisando el código fuente directamente. Esto ayuda a encontrar fallos tempranamente y reduce el costo de corrección. A diferencia del análisis dinámico, no necesita un entorno de ejecución ni casos de prueba para funcionar.

### 3. ¿Cómo impacta SonarQube en la calidad del software antes del despliegue?
SonarQube mejora la calidad del software al identificar errores, code smells, problemas de seguridad y deuda técnica antes del despliegue. Esto permite al equipo aplicar correcciones tempranas, mantener estándares de codificación y asegurar que el código sea más limpio, robusto y mantenible.

### 4. ¿Qué políticas o reglas personalizarías según el tipo de proyecto?
Personalizaría reglas según el tipo de aplicación. Por ejemplo:

En proyectos backend críticos, reforzaría reglas de seguridad y manejo de errores.

En proyectos frontend, priorizaría la legibilidad, uso de nombres significativos y evitar lógica compleja en componentes.

En aplicaciones con alto rendimiento, prestaría atención a reglas de optimización y uso eficiente de recursos.

## ![Evidencia ejecución en SonarQube](./src/image/Validadorapp_sonar1.jpg)

