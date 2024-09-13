# 3.1 To-Be Scenario Mapping

**Personal Administrativo**
<br>
<img src="/Report/images/tobe-scenario-personaladmi.jpg"/>
<br>


**Profesores**
<br>
<img src= "/Report/images/tobe-scenario-profesor.jpg" />
<br>

# 3.2 User Stories

Para desarrollar las User Stories (US) más relevantes para el sistema de gemelo digital de la escuela John F. Kennedy, podemos enfocarnos en aquellas que tienen un impacto directo en los usuarios finales, como los administradores y profesores. Dejaré de lado las que son puramente técnicas o relacionadas con la API RESTful y priorizaré las que se relacionan con el monitoreo en tiempo real, simulacros, y alertas.

<table>
	<tbody>
		<tr>
			<td>Story ID</td>
			<td>Título</td>
			<td>Descripción</td>
			<td>Criterios de Aceptación</td>
			<td>Relacionado con Epic ID</td>
		</tr>
		<tr>
			<td>US001</td>
			<td>Monitoreo en tiempo real</td>
			<td>Como administrador<br>Quiero monitorear en tiempo real el estado estructural del colegio<br>Para tomar decisiones informadas en caso de emergencia</td>
			<td>--- Scenario1: <br>Given que la aplicación está activa y conectada a los sensores, <br>When se detecta una anomalía estructural,<br>Then el sistema genera una notificación automática para el administrador.</td>
			<td>EP001</td>
		</tr>
		<tr>
			<td>US002</td>
			<td>Planificación de simulacros</td>
			<td>Como administrador,<br>Quiero planificar simulacros de evacuación basados en las rutas de evacuación más seguras,<br>Para asegurar que el personal y los estudiantes sepan cómo actuar en una emergencia.</td>
			<td>--- Scenario: <br>Given que el administrador accede al sistema de planificación,<br>When selecciona las rutas y condiciones del simulacro,<br>Then el sistema genera un plan detallado que puede ser ejecutado por el personal.</td>
			<td>EP002</td>
		</tr>
		<tr>
			<td>US003</td>
			<td>Alertas en tiempo real para profesores</td>
			<td>Como profesor,<br>Quiero recibir alertas tempranas sobre situaciones peligrosas,<br>Para guiar a los estudiantes a las zonas seguras lo más rápido posible.</td>
			<td>--- Scenario: <br>Given que se detecta una situación peligrosa,<br>When el sistema envía una alerta al profesor,<br>Then este puede visualizar la alerta y las rutas seguras en tiempo real.<br></td>
			<td>EP001</td>
		</tr>
		<tr>
			<td>US004</td>
			<td>Visualización de áreas de riesgo</td>
			<td>Como administrador,<br>Quiero visualizar las áreas de riesgo del colegio en un mapa,<br>Para identificar zonas peligrosas y planificar evacuaciones más seguras.</td>
			<td>--- Scenario: <br>Given que el sistema ha procesado los datos de riesgo, <br>When el administrador consulta el mapa de riesgos,<br>Then se muestran en tiempo real las áreas de riesgo basadas en los datos más recientes.<br></td>
			<td>EP003</td>
		</tr>
		<tr>
			<td>US005</td>
			<td>Evaluación continua de seguridad en aulas</td>
			<td>Como profesor,<br>Quiero tener acceso a una evaluación continua del estado de seguridad en mi aula,<br>Para estar al tanto de cualquier situación que afecte la integridad del espacio.</td>
			<td>--- Scenario: <br>Given que el sistema realiza evaluaciones periódicas,<br>When se completa una evaluación,<br>Then se actualiza automáticamente el estado de seguridad en el panel del profesor.</td>
			<td>EP003</td>
		</tr>
		<tr>
			<td>US006</td>
			<td>Generación automática de reportes de seguridad</td>
			<td>Como administrador,<br>Quiero generar reportes automáticos sobre el estado de seguridad estructural,<br>Para tener un historial documentado y tomar decisiones basadas en datos.</td>
			<td>--- Scenario: <br>Given que el sistema ha recopilado datos durante un período de tiempo,<br>When el administrador solicita un reporte,<br>Then el sistema genera un informe detallado con las áreas críticas y las acciones recomendadas.</td>
			<td>EP003</td>
		</tr>
		<tr>
			<td>US007</td>
			<td>Integración con sistemas de alerta temprana nacionales</td>
			<td>Como administrador<br>Quiero que el sistema esté integrado con el sistema de alerta temprana nacional,<br>Para recibir advertencias automáticas de terremotos en tiempo real.</td>
			<td>--- Scenario: <br>Given que se activa una alerta temprana nacional,<br>When el sistema recibe la alerta,<br>Then notifica automáticamente al personal y profesores para activar los protocolos de evacuación.</td>
			<td>EP001</td>
		</tr>
		<tr>
			<td>US008</td>
			<td>Mantenimiento predictivo</td>
			<td>Como administrador,<br>Quiero recibir recomendaciones de mantenimiento predictivo basadas en la condición actual de las estructuras,<br>Para prevenir fallas antes de que ocurran.</td>
			<td>--- Scenario: <br>Given que los sensores detectan cambios en la estructura,<br>When el sistema analiza los datos,<br>Then genera una recomendación de mantenimiento específica para las áreas afectadas.</td>
			<td>EP004</td>
		</tr>
		<tr>
			<td>US009</td>
			<td>Evaluación de capacidad de las rutas de evacuación</td>
			<td>Como profesor,<br>Quiero saber cuántas personas pueden evacuar por cada ruta de salida,<br>Para evitar aglomeraciones y optimizar el flujo durante emergencias.</td>
			<td>--- Scenario: <br>Given que el sistema analiza las rutas de evacuación,<br>When el profesor selecciona una ruta,<br>Then el sistema muestra la capacidad máxima de personas que pueden usar esa ruta sin congestión.</td>
			<td>EP004</td>
		</tr>
		<tr>
			<td>US010</td>
			<td>Entrenamiento interactivo para profesores y personal</td>
			<td>Como administrador,<br>Quiero implementar entrenamientos interactivos a través de la plataforma,<br>Para que los profesores y personal se familiaricen con los procedimientos de emergencia y las rutas de evacuación.</td>
			<td>--- Scenario: <br>Given que el administrador programa un entrenamiento,<br>When los profesores acceden al sistema,<br>Then pueden completar ejercicios interactivos basados en situaciones de emergencia.</td>
			<td>EP005</td>
		</tr>
		<tr>
			<td>US011</td>
			<td>Registro de participación en simulacros</td>
			<td>Como administrador,<br>Quiero llevar un registro de la participación en los simulacros de evacuación,<br>Para asegurar que todo el personal y los estudiantes estén preparados.</td>
			<td>--- Scenario: <br>Given que se ejecuta un simulacro,<br>When se completa el evento,<br>Then el sistema registra automáticamente la participación de cada usuario (profesor, estudiante).</td>
			<td>EP002</td>
		</tr>
		<tr>
			<td>US012</td>
			<td>Acceso remoto al gemelo digital</td>
			<td>Como administrador,<br>Quiero poder acceder al gemelo digital de forma remota,<br>Para monitorear la seguridad del colegio desde cualquier lugar en caso de emergencia.</td>
			<td>--- Scenario: <br>Given que el administrador está fuera del colegio,<br>When accede a la aplicación desde un dispositivo remoto,<br>Then puede monitorear el estado del colegio en tiempo real.</td>
			<td>EP005</td>
		</tr>
		<tr>
			<td>US013</td>
			<td>Alertas basadas en condiciones climáticas</td>
			<td>Como administrador,<br>Quiero recibir alertas automáticas si las condiciones climáticas podrían aumentar el riesgo estructural (lluvias, vientos fuertes),<br>Para poder anticipar posibles problemas de seguridad.</td>
			<td>--- Scenario: <br>Given que se presentan condiciones climáticas adversas,<br>When el sistema detecta que aumentan el riesgo en áreas vulnerables,<br>Then envía una alerta al administrador para que se tomen precauciones.</td>
			<td>EP001</td>
		</tr>
		<tr>
			<td>US014</td>
			<td>Evaluación de condiciones antes de iniciar clases</td>
			<td>Como profesor,<br>Quiero recibir una evaluación de las condiciones estructurales y de seguridad antes de comenzar el día,<br>Para asegurar que no existen riesgos antes de que ingresen los estudiantes.</td>
			<td>EP003</td>
		</tr>
	</tbody>
</table>

# 3.3 Impact Mapping

**Personal Administrativo**
<br>
<img src="/Report/images/impact-admi.png"/>
<br>

**Profesores**
<br>
<img src="/Report/images/impact-profesor.png"/>
<br>

# 3.4 Product backlog

En el desarrollo del Product Backlog para nuestro proyecto, hemos clasificado y priorizado las User Stories en función de su impacto en los objetivos del negocio y su valor para los usuarios finales. Este enfoque asegura que el equipo se enfoque primero en las funcionalidades más críticas y valiosas para el éxito del proyecto. Para estimar el esfuerzo y la complejidad de cada User Story, hemos utilizado la secuencia de Fibonacci (1, 2, 3, 5, 8) en lugar de una escala lineal

<table>
	<tbody>
		<tr>
			<td>Story ID</td>
			<td>Título</td>
			<td>Descripción</td>
			<td>Story Points</td>
		</tr>
		<tr>
			<td>US003</td>
			<td>Alertas en tiempo real para profesores</td>
			<td>Como profesor,<br>Quiero recibir alertas tempranas sobre situaciones peligrosas,<br>Para guiar a los estudiantes a las zonas seguras lo más rápido posible.</td>
			<td>8</td>
		</tr>
		<tr>
			<td>US001</td>
			<td>Monitoreo en tiempo real</td>
			<td>Como administrador,<br>Quiero monitorear en tiempo real el estado estructural del colegio,<br>Para tomar decisiones informadas en caso de emergencia</td>
			<td>8</td>
		</tr>
		<tr>
			<td>US007</td>
			<td>Integración con sistemas de alerta temprana nacionales</td>
			<td>Como administrador,<br>Quiero que el sistema esté integrado con el sistema de alerta temprana nacional,<br>Para recibir advertencias automáticas de terremotos en tiempo real.</td>
			<td>5</td>
		</tr>
		<tr>
			<td>US004</td>
			<td>Visualización de áreas de riesgo</td>
			<td>Como administrador,<br>Quiero visualizar las áreas de riesgo del colegio en un mapa,<br>para identificar zonas peligrosas y planificar evacuaciones más seguras.</td>
			<td>5</td>
		</tr>
		<tr>
			<td>US005</td>
			<td>Evaluación continua de seguridad en aulas</td>
			<td>Como profesor,<br>Quiero tener acceso a una evaluación continua del estado de seguridad en mi aula,<br>Para estar al tanto de cualquier situación que afecte la integridad del espacio.</td>
			<td>5</td>
		</tr>
		<tr>
			<td>US002</td>
			<td>Planificación de simulacros</td>
			<td>Como administrador,<br>Quiero planificar simulacros de evacuación basados en las rutas de evacuación más seguras,<br>Para asegurar que el personal y los estudiantes sepan cómo actuar en una emergencia.</td>
			<td>5</td>
		</tr>
		<tr>
			<td>US010</td>
			<td>Entrenamiento interactivo para profesores y personal</td>
			<td>Como administrador,<br>Quiero implementar entrenamientos interactivos a través de la plataforma,<br>Para que los profesores y personal se familiaricen con los procedimientos de emergencia y las rutas de evacuación.</td>
			<td>3</td>
		</tr>
		<tr>
			<td>US009</td>
			<td>Evaluación de capacidad de las rutas de evacuación</td>
			<td>Como profesor,<br>Quiero saber cuántas personas pueden evacuar por cada ruta de salida,<br>Para evitar aglomeraciones y optimizar el flujo durante emergencias.</td>
			<td>3</td>
		</tr>
		<tr>
			<td>US011</td>
			<td>Registro de participación en simulacros</td>
			<td>Como administrador,<br>Quiero llevar un registro de la participación en los simulacros de evacuación,<br>Para asegurar que todo el personal y los estudiantes estén preparados.</td>
			<td>3</td>
		</tr>
		<tr>
			<td>US013</td>
			<td>Alertas basadas en condiciones climáticas</td>
			<td>Como administrador,<br>Quiero recibir alertas automáticas si las condiciones climáticas podrían aumentar el riesgo estructural (lluvias, vientos fuertes),<br>Para poder anticipar posibles problemas de seguridad.</td>
			<td>2</td>
		</tr>
		<tr>
			<td>US012</td>
			<td>Acceso remoto al gemelo digita</td>
			<td>Como administrador,<br>Quiero poder acceder al gemelo digital de forma remota,<br>Para monitorear la seguridad del colegio desde cualquier lugar en caso de emergencia.</td>
			<td>2</td>
		</tr>
		<tr>
			<td>US008</td>
			<td>Mantenimiento predictivo</td>
			<td>Como administrador,<br>Quiero recibir recomendaciones de mantenimiento predictivo basadas en la condición actual de las estructuras,<br>Para prevenir fallas antes de que ocurran.</td>
			<td>2</td>
		</tr>
		<tr>
			<td>US014</td>
			<td>Evaluación de condiciones antes de iniciar clases</td>
			<td>Como profesor,<br>Quiero recibir una evaluación de las condiciones estructurales y de seguridad antes de comenzar el día,<br>Para asegurar que no existen riesgos antes de que ingresen los estudiantes.</td>
			<td>2</td>
		</tr>
    <tr>
			<td>US006</td>
			<td>Generación automática de reportes de seguridad</td>
			<td>Como administrador,<br>Quiero generar reportes automáticos sobre el estado de seguridad estructural,<br>Para tener un historial documentado y tomar decisiones basadas en datos.</td>
			<td>1</td>
		</tr>
	</tbody>
</table>