# DOCUMENTO DE REQUERIMIENTOS FUNCIONALES

## Proyecto: PetGrow

**Asignatura:** INF-4334 - Gestión de Configuración de Software  
**Estudiante:** Nicol Ortiz  
**Proyecto:** PetGrow

---

## 1. Descripción del proyecto

PetGrow es una aplicación diseñada para ayudar a los propietarios a cuidar y dar seguimiento al desarrollo de sus mascotas. Su propósito es facilitar la organización de aspectos importantes como la alimentación, hidratación, salud, actividad física y hábitos, ofreciendo herramientas y recomendaciones que contribuyan al bienestar de los animales.

## 2. Objetivo

Desarrollar una aplicación que permita a los propietarios llevar un mejor control del cuidado de sus mascotas, registrar información importante y consultar recomendaciones que les ayuden a mantener una buena calidad de vida para sus animales.

## 3. Historias de usuario y requerimientos funcionales

Las siguientes historias de usuario describen las funcionalidades que se esperan implementar en PetGrow. Cada una incluye criterios de aceptación y prioridad.

### Módulo 1. Registro y perfil de mascotas

#### HU-01 - Registrar una mascota

**Historia de usuario:** Como propietario, quiero registrar a mi mascota en la aplicación, para guardar su información y llevar un seguimiento de sus cuidados.

**Criterios de aceptación:**
- El sistema debe permitir ingresar el nombre de la mascota.
- Debe permitir seleccionar el tipo de animal.
- Debe permitir registrar raza, edad, sexo y peso.
- Debe permitir agregar una fotografía.
- Los datos deben guardarse correctamente.

**Prioridad:** Alta.

#### HU-02 - Visualizar el perfil de mi mascota

**Historia de usuario:** Como propietario, quiero visualizar el perfil de mi mascota, para consultar fácilmente su información.

**Criterios de aceptación:**
- El sistema debe mostrar los datos registrados.
- Debe mostrar la fotografía de la mascota cuando exista.
- Debe permitir consultar su edad, raza y peso.
- La información debe corresponder a la mascota seleccionada.

**Prioridad:** Alta.

#### HU-03 - Editar información de la mascota

**Historia de usuario:** Como propietario, quiero modificar los datos de mi mascota, para mantener su perfil actualizado.

**Criterios de aceptación:**
- El sistema debe permitir editar los datos registrados.
- Debe permitir guardar los cambios.
- Debe mostrar la información actualizada.
- No debe guardar cambios vacíos en los campos obligatorios.

**Prioridad:** Alta.

#### HU-04 - Registrar varias mascotas

**Historia de usuario:** Como propietario, quiero registrar varias mascotas en mi cuenta, para administrar el cuidado de todos mis animales desde una misma aplicación.

**Criterios de aceptación:**
- El sistema debe permitir agregar más de una mascota.
- Cada mascota debe tener su propio perfil.
- Debe permitir seleccionar la mascota que se desea consultar.
- La información de cada mascota debe mantenerse separada.

**Prioridad:** Media.

#### HU-05 - Eliminar el perfil de una mascota

**Historia de usuario:** Como propietario, quiero eliminar el perfil de una mascota, para retirar información que ya no necesito mantener en mi cuenta.

**Criterios de aceptación:**
- El sistema debe mostrar una opción para eliminar el perfil.
- Debe solicitar confirmación antes de eliminarlo.
- No debe eliminar el perfil sin autorización del propietario.
- Debe actualizar la lista de mascotas después de eliminarlo.

**Prioridad:** Media.

### Módulo 2. Alimentación e hidratación

#### HU-06 - Consultar recomendaciones de alimentación

**Historia de usuario:** Como propietario, quiero consultar recomendaciones de alimentación, para conocer qué tipo de comida puede ser adecuada para mi mascota.

**Criterios de aceptación:**
- El sistema debe mostrar recomendaciones según el tipo de mascota.
- Debe presentar información fácil de comprender.
- Debe permitir consultar recomendaciones relacionadas con su edad.
- La información debe estar organizada por categorías.

**Prioridad:** Alta.

#### HU-07 - Calcular la cantidad de alimento

**Historia de usuario:** Como propietario, quiero calcular la cantidad aproximada de alimento que necesita mi mascota según su peso, para organizar mejor sus porciones diarias.

**Criterios de aceptación:**
- El sistema debe permitir ingresar el peso de la mascota.
- Debe utilizar la información disponible para realizar el cálculo.
- Debe mostrar una cantidad estimada de alimento.
- Debe indicar que la cantidad puede variar según las necesidades individuales del animal.

**Prioridad:** Alta.

#### HU-08 - Registrar las comidas de la mascota

**Historia de usuario:** Como propietario, quiero registrar las comidas de mi mascota, para llevar un control de su alimentación diaria.

**Criterios de aceptación:**
- El sistema debe permitir registrar el tipo de alimento.
- Debe permitir indicar la cantidad suministrada.
- Debe guardar la fecha y hora del registro.
- Debe permitir consultar los registros anteriores.

**Prioridad:** Media.

#### HU-09 - Consultar alimentos permitidos y no recomendados

**Historia de usuario:** Como propietario, quiero consultar qué alimentos son seguros y cuáles pueden ser perjudiciales para mi mascota, para evitar ofrecerle alimentos inadecuados.

**Criterios de aceptación:**
- El sistema debe mostrar alimentos organizados por categorías.
- Debe identificar los alimentos permitidos.
- Debe señalar los alimentos que pueden resultar peligrosos.
- Debe ofrecer información clara sobre los riesgos.

**Prioridad:** Alta.

#### HU-10 - Registrar el consumo de agua

**Historia de usuario:** Como propietario, quiero registrar el consumo de agua de mi mascota, para llevar un seguimiento de su hidratación.

**Criterios de aceptación:**
- El sistema debe permitir registrar la cantidad de agua consumida.
- Debe guardar la fecha del registro.
- Debe permitir consultar los registros anteriores.
- Debe mostrar un resumen del consumo registrado.

**Prioridad:** Media.

#### HU-11 - Calcular las necesidades de hidratación

**Historia de usuario:** Como propietario, quiero consultar una estimación de las necesidades diarias de agua de mi mascota según su peso, para ayudar a mantener una hidratación adecuada.

**Criterios de aceptación:**
- El sistema debe permitir ingresar o utilizar el peso registrado.
- Debe calcular una cantidad estimada de agua.
- Debe mostrar el resultado de manera sencilla.
- Debe aclarar que las necesidades pueden variar según la actividad, alimentación y condiciones del animal.

**Prioridad:** Alta.

### Módulo 3. Salud y prevención

#### HU-12 - Registrar vacunas

**Historia de usuario:** Como propietario, quiero registrar las vacunas de mi mascota, para mantener un historial de su vacunación.

**Criterios de aceptación:**
- El sistema debe permitir registrar el nombre de la vacuna.
- Debe permitir indicar la fecha de aplicación.
- Debe permitir registrar la próxima fecha, si corresponde.
- Debe guardar la información en el historial de salud.

**Prioridad:** Alta.

#### HU-13 - Registrar visitas al veterinario

**Historia de usuario:** Como propietario, quiero registrar las visitas de mi mascota al veterinario, para conservar un historial de sus consultas.

**Criterios de aceptación:**
- El sistema debe permitir registrar la fecha de la consulta.
- Debe permitir ingresar el motivo de la visita.
- Debe permitir agregar observaciones.
- Debe guardar los datos para futuras consultas.

**Prioridad:** Alta.

#### HU-14 - Consultar enfermedades comunes

**Historia de usuario:** Como propietario, quiero consultar información sobre enfermedades comunes en las mascotas, para conocer sus posibles síntomas y medidas de prevención.

**Criterios de aceptación:**
- El sistema debe mostrar información organizada por enfermedad.
- Debe presentar síntomas generales.
- Debe incluir medidas preventivas.
- Debe recomendar acudir a un veterinario ante síntomas preocupantes.

**Prioridad:** Alta.

#### HU-15 - Consultar cuidados preventivos

**Historia de usuario:** Como propietario, quiero consultar recomendaciones de prevención, para reducir los riesgos que puedan afectar la salud de mi mascota.

**Criterios de aceptación:**
- El sistema debe mostrar recomendaciones de cuidado.
- Debe incluir información sobre higiene y vacunación.
- Debe ofrecer recomendaciones según el tipo de mascota.
- La información debe ser clara y comprensible.

**Prioridad:** Media.

#### HU-16 - Registrar medicamentos

**Historia de usuario:** Como propietario, quiero registrar los medicamentos indicados para mi mascota, para mantener organizada la información de sus tratamientos.

**Criterios de aceptación:**
- El sistema debe permitir registrar el nombre del medicamento.
- Debe permitir indicar las instrucciones proporcionadas por el veterinario.
- Debe permitir registrar las fechas del tratamiento.
- Debe guardar la información para consultarla posteriormente.

**Prioridad:** Alta.

#### HU-17 - Consultar el historial de salud

**Historia de usuario:** Como propietario, quiero consultar el historial de salud de mi mascota, para tener acceso a sus registros médicos en un solo lugar.

**Criterios de aceptación:**
- El sistema debe mostrar las vacunas registradas.
- Debe mostrar las visitas veterinarias.
- Debe incluir los medicamentos registrados.
- Debe organizar la información por fecha.

**Prioridad:** Alta.

### Módulo 4. Hábitos y entrenamiento

#### HU-18 - Registrar hábitos diarios

**Historia de usuario:** Como propietario, quiero registrar los hábitos diarios de mi mascota, para conocer y organizar mejor sus rutinas.

**Criterios de aceptación:**
- El sistema debe permitir registrar actividades habituales.
- Debe permitir indicar la frecuencia de cada actividad.
- Debe guardar los hábitos registrados.
- Debe permitir consultar la información posteriormente.

**Prioridad:** Media.

#### HU-19 - Consultar consejos de entrenamiento

**Historia de usuario:** Como propietario, quiero consultar consejos de entrenamiento, para mejorar el comportamiento de mi mascota.

**Criterios de aceptación:**
- El sistema debe mostrar consejos organizados por tema.
- Debe incluir instrucciones sencillas.
- Debe presentar recomendaciones según el tipo de mascota.
- Debe facilitar la consulta de los consejos.

**Prioridad:** Media.

#### HU-20 - Registrar avances de entrenamiento

**Historia de usuario:** Como propietario, quiero registrar los avances del entrenamiento de mi mascota, para observar su progreso con el tiempo.

**Criterios de aceptación:**
- El sistema debe permitir registrar una actividad entrenada.
- Debe permitir agregar observaciones sobre los resultados.
- Debe guardar la fecha del registro.
- Debe permitir consultar los avances anteriores.

**Prioridad:** Media.

#### HU-21 - Crear rutinas de cuidado

**Historia de usuario:** Como propietario, quiero crear rutinas de cuidado para mi mascota, para organizar las actividades que debo realizar diariamente.

**Criterios de aceptación:**
- El sistema debe permitir crear actividades.
- Debe permitir asignar días y horarios.
- Debe guardar las rutinas creadas.
- Debe permitir consultar y modificar las rutinas.

**Prioridad:** Media.

#### HU-22 - Consultar recomendaciones de comportamiento

**Historia de usuario:** Como propietario, quiero consultar recomendaciones sobre el comportamiento de mi mascota, para aprender a identificar y manejar diferentes conductas.

**Criterios de aceptación:**
- El sistema debe mostrar información sobre comportamientos comunes.
- Debe incluir recomendaciones prácticas.
- Debe organizar la información por categorías.
- Debe indicar cuándo es recomendable buscar ayuda profesional.

**Prioridad:** Media.

### Módulo 5. Actividad física y bienestar

#### HU-23 - Registrar actividades físicas

**Historia de usuario:** Como propietario, quiero registrar las actividades físicas de mi mascota, para llevar un control de su ejercicio.

**Criterios de aceptación:**
- El sistema debe permitir registrar el tipo de actividad.
- Debe permitir indicar su duración.
- Debe guardar la fecha de la actividad.
- Debe permitir consultar las actividades anteriores.

**Prioridad:** Media.

#### HU-24 - Consultar recomendaciones de ejercicio

**Historia de usuario:** Como propietario, quiero consultar recomendaciones de ejercicio según las características de mi mascota, para mantenerla activa de manera adecuada.

**Criterios de aceptación:**
- El sistema debe mostrar recomendaciones de actividad física.
- Debe considerar el tipo de mascota.
- Debe presentar sugerencias según su edad y características.
- Debe incluir recomendaciones de seguridad.

**Prioridad:** Alta.

#### HU-25 - Llevar un seguimiento de paseos

**Historia de usuario:** Como propietario, quiero registrar los paseos de mi mascota, para conocer la frecuencia y duración de sus caminatas.

**Criterios de aceptación:**
- El sistema debe permitir registrar cada paseo.
- Debe permitir indicar la duración.
- Debe guardar la fecha del paseo.
- Debe mostrar un historial de paseos.

**Prioridad:** Baja.

#### HU-26 - Consultar consejos de bienestar

**Historia de usuario:** Como propietario, quiero consultar consejos para el bienestar de mi mascota, para mejorar sus condiciones de vida.

**Criterios de aceptación:**
- El sistema debe mostrar consejos de bienestar.
- Debe incluir recomendaciones de descanso y actividad.
- Debe presentar información organizada.
- Debe permitir consultar los consejos fácilmente.

**Prioridad:** Media.

### Módulo 6. Desarrollo y seguimiento

#### HU-27 - Registrar el crecimiento de la mascota

**Historia de usuario:** Como propietario, quiero registrar el crecimiento de mi mascota, para observar sus cambios físicos a lo largo del tiempo.

**Criterios de aceptación:**
- El sistema debe permitir registrar el peso.
- Debe permitir guardar la fecha de cada medición.
- Debe conservar los registros anteriores.
- Debe permitir consultar la evolución del peso.

**Prioridad:** Alta.

#### HU-28 - Consultar las etapas de desarrollo

**Historia de usuario:** Como propietario, quiero consultar información sobre las etapas de desarrollo de mi mascota, para conocer los cambios y cuidados que necesita durante su crecimiento.

**Criterios de aceptación:**
- El sistema debe mostrar información por etapas.
- Debe presentar características generales de cada etapa.
- Debe incluir recomendaciones de cuidado.
- Debe permitir consultar la información según la edad de la mascota.

**Prioridad:** Media.

#### HU-29 - Consultar estadísticas de cuidado

**Historia de usuario:** Como propietario, quiero consultar estadísticas sobre el cuidado de mi mascota, para conocer cómo ha sido su seguimiento durante un período determinado.

**Criterios de aceptación:**
- El sistema debe recopilar los registros disponibles.
- Debe mostrar resúmenes de alimentación, hidratación y actividad.
- Debe permitir consultar la información por períodos.
- Los resultados deben presentarse de forma comprensible.

**Prioridad:** Media.

#### HU-30 - Comparar registros de crecimiento

**Historia de usuario:** Como propietario, quiero comparar las mediciones de mi mascota, para identificar cambios en su crecimiento y peso.

**Criterios de aceptación:**
- El sistema debe permitir consultar diferentes mediciones.
- Debe mostrar las fechas de cada registro.
- Debe facilitar la comparación de los valores.
- Debe presentar los cambios de manera clara.

**Prioridad:** Media.

#### HU-31 - Consultar recomendaciones según la edad

**Historia de usuario:** Como propietario, quiero recibir recomendaciones según la edad de mi mascota, para adaptar sus cuidados a su etapa de vida.

**Criterios de aceptación:**
- El sistema debe utilizar la edad registrada.
- Debe mostrar recomendaciones relacionadas con su etapa.
- Debe incluir información sobre alimentación, actividad y cuidado.
- Debe actualizar las recomendaciones cuando cambie la edad registrada.

**Prioridad:** Alta.

### Módulo 7. Recordatorios y emergencias

#### HU-32 - Crear recordatorios de cuidado

**Historia de usuario:** Como propietario, quiero crear recordatorios para las actividades de cuidado de mi mascota, para no olvidar tareas importantes.

**Criterios de aceptación:**
- El sistema debe permitir crear recordatorios.
- Debe permitir establecer fecha y hora.
- Debe permitir indicar el motivo del recordatorio.
- Debe mostrar los recordatorios registrados.

**Prioridad:** Alta.

#### HU-33 - Recibir recordatorios de vacunación

**Historia de usuario:** Como propietario, quiero recibir recordatorios sobre las fechas de vacunación de mi mascota, para mantener al día su calendario de vacunas.

**Criterios de aceptación:**
- El sistema debe permitir registrar fechas de vacunación.
- Debe identificar las próximas fechas registradas.
- Debe mostrar un aviso cuando se acerque la fecha.
- Debe permitir consultar los recordatorios.

**Prioridad:** Alta.

#### HU-34 - Consultar información de primeros auxilios

**Historia de usuario:** Como propietario, quiero consultar información básica de primeros auxilios para mascotas, para saber cómo actuar inicialmente ante una situación de emergencia.

**Criterios de aceptación:**
- El sistema debe mostrar información organizada por situaciones.
- Debe presentar instrucciones generales y fáciles de comprender.
- Debe indicar cuándo se necesita atención veterinaria inmediata.
- Debe aclarar que la información no sustituye la atención profesional.

**Prioridad:** Alta.

#### HU-35 - Registrar contactos de emergencia

**Historia de usuario:** Como propietario, quiero registrar contactos veterinarios de emergencia, para tener disponible su información cuando mi mascota necesite atención urgente.

**Criterios de aceptación:**
- El sistema debe permitir registrar el nombre del centro veterinario.
- Debe permitir guardar un número de teléfono.
- Debe permitir registrar la dirección.
- Debe permitir consultar los contactos guardados.

