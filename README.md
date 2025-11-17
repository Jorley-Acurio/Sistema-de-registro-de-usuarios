# Sistema-de-registro-de-usuarios
## 📌 Descripción del Caso

El sistema de registro de usuarios es una plataforma que permite a las personas crear, administrar y mantener cuentas de acceso en una aplicación o sitio web. Su función principal es almacenar de forma segura los datos personales necesarios para identificar a cada usuario y asignarles los permisos correspondientes. Incluye funciones como registro, inicio de sesión, consulta y edición de perfil, recuperación de contraseñas y gestión administrativa de cuentas. Al operar sobre una base de datos segura, garantiza un acceso controlado y confiable, siendo esencial para la seguridad, personalización y correcta gestión de usuarios en cualquier plataforma digital.

## 🎯 Objetivo

El propósito del sistema de registro de usuarios es permitir que las personas se registren, accedan y gestionen su información personal de forma segura, confiable y eficiente. Su objetivo es identificar correctamente a cada usuario, asignar los niveles de acceso según su rol y asegurar que todas las acciones se realicen bajo procesos de autenticación y protección de datos. Además, busca ofrecer una experiencia sencilla que facilite tareas como registrarse, iniciar sesión, actualizar información y recuperar credenciales, garantizando que solo usuarios autorizados puedan acceder a los recursos de la plataforma.

# 🧪 Tabla de Pruebas – Casos de Prueba Unitaria

| **Requerimiento asociado** | **Datos de entrada** | **Resultado esperado** | **Resultado obtenido** |
|----------------------------|-----------------------|-------------------------|--------------------------|
| **Registro de nuevos usuarios** | **Nombre:** Jorley<br>**Apellido:** Acurio<br>**Correo:** jorleyk@gmail.com<br>**Contraseña:** 20604080 | Perfil creado exitosamente. | Creación de perfil exitosa. |
| **Consulta de la información del perfil** | **Dirección:** Villanueva<br>**Fecha de nacimiento:** 03 de septiembre de 2004 | Consulta de información. | Consulta exitosa. |
| **Inicio de sesión de usuarios** | **Correo:** jorleyk@gmail.com<br>**Contraseña:** 20604080 | Datos registrados. | Inicio de sesión exitoso. |

# 🧪 Tabla de Casos de Validación

| **Requerimiento asociado** | **Datos de entrada** | **Resultado esperado** | **Resultado obtenido** |
|----------------------------|-----------------------|-------------------------|--------------------------|
| **Eficiencia** | Datos del usuario. | Registrarse rápidamente. | Registro rápido exitoso. |
| **Sencillez de reparación** | Problemas con la contraseña. | Recuperación de contraseña. | Recuperación exitosa. |

## 🧩 Tipo de Mantenimiento Propuesto
### ✔️ **Mantenimiento Correctivo**

## 📌 Descripción del Caso
Se han encontrado defectos en el sistema de registro de usuarios que afectan funciones esenciales. Las dificultades de carga de datos del perfil, los errores en la validación de credenciales y las demoras durante el proceso de autenticación son algunos de los más relevantes.  
Estos inconvenientes se presentan ocasionalmente mientras el sistema se usa con normalidad, lo que obstaculiza a los usuarios y perjudica la estabilidad general de la plataforma.
Este mantenimiento se lleva a cabo para solucionar errores que fueron identificados mientras el sistema estaba en funcionamiento.  
La autenticación, la recuperación de datos y la experiencia del usuario se ven afectadas por los errores, por lo que es necesario actuar de inmediato para restablecer la funcionalidad y estabilidad del sistema sin agregar nuevas características.rma.


## 🎯 Objetivos del Mantenimiento Correctivo
- Corregir los fallos que obstaculizan el correcto funcionamiento del módulo de autenticación.   - Garantizar que el acceso, la consulta de datos y los procedimientos de registro sean estables y coherentes.  
- Rectificar errores que causen retrasos o datos incompletos al obtener información de los usuarios.
- Asegurar que los datos guardados permanezcan íntegros y no provoquen conflictos mientras se emplean.  
- Perfeccionar la experiencia del usuario a través de la rectificación de conductas imprevistas.


## 📋 Requerimientos para el Mantenimiento

### **Requerimientos Técnicos**
- Limpiar y revisar el código del módulo responsable de la sesión de inicio.  
- Estudiar la comunicación entre el backend y el frontend para identificar errores en la validación.  
- Comprobar la condición de la base de datos, en particular los índices y las relaciones en la tabla correspondiente a los usuarios.  
- Examinar los endpoints o controladores vinculados a la autenticación y restauración de datos.  
- Modificar los mensajes de error para que sean más precisos y claros.

### **Requerimientos Operativos**
- Hacer un respaldo total de seguridad antes de introducir cualquier modificación.  
- Registrar de manera detallada las alteraciones implementadas y los errores subsanados.  
- Antes de poner en producción la corrección, realizar pruebas en un ambiente de desarrollo.  
- Para prevenir que los cambios se dupliquen, es importante mantener comunicación con el equipo.


## 🧪 Tabla de Pruebas Funcionales

| Caso de Prueba | Resultado Esperado | Validación |
|----------------|--------------------|------------|
| **Corrección en la validación de credenciales** | El sistema debe identificar correctamente si el usuario existe y si su contraseña es válida. | El sistema autentica sin errores y permite el ingreso del usuario. |
| **Revisión de carga del perfil** | Los datos del perfil deben mostrarse completos y sin inconsistencias. | La información se despliega correctamente y coincide con la almacenada. |
| **Prueba de recuperación de contraseña** | El sistema debe enviar un método seguro de recuperación al usuario. | El sistema genera un código de recuperación y lo envía correctamente. |



## 🔄 Reflexión sobre el Control de Versiones

Es imprescindible el control de versiones para llevar a cabo el proceso de mantenimiento.  Su empleo posibilita:

 - Controlar y anotar cada modificación realizada en el código.  
 - Hacer más fácil la comparación entre versiones para detectar el origen de un error.  
 - Crear ramas específicas para cada modificación, con el fin de no alterar el código estable.  
 - Garantizar una integración regulada a través de revisiones previas.  
 - Conservar un registro minucioso que permita la realización de auditorías y análisis en el futuro.

Un sistema de control de versiones que se utiliza de manera adecuada favorece un mantenimiento más ordenado, fiable y seguro, especialmente cuando hay que subsanar errores críticos.


## 🏁 Conclusión

El mantenimiento correctivo propuesto hará que el sistema de registro de usuarios vuelva a funcionar correctamente.  
Si se corrigen las fallas detectadas en la recuperación de credenciales, la verificación y la consulta de datos, la plataforma brindará una experiencia más confiable y estable.  
Si se utiliza correctamente el control de versiones, se asegurarán los cambios y será más sencillo hacerle un seguimiento al proceso mientras se reducen los riesgos..

