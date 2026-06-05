# Trabajo-Algoritmia-y-programacion

# 1. Integrantes
| Nombre | Rol en el proyecto |
|---|---|
| Óscar Andrés Madrid Vergara | Líder del equipo / Desarrollo principal |
| Sharon Vanesa Trujillo Muñoz | Desarrollo de módulos / Documentación |
| Diana Isabela Gómez Vera | Pruebas y validación / Documentación |

Somos tres estudiantes de **Ingeniería Industrial** de la **Universidad de Antioquia, Seccional Medellín y Carmen de Viboral**. Este proyecto hace parte del curso de Algoritmia y Programación (2026-1) y representa nuestra primera experiencia construyendo un sistema de software orientado a objetos en Python.

---
# 2. Vínculos académicos

**Óscar Andrés Madrid Vergara**

- **Programa:** Ingeniería Industrial
- **Universidad:** Universidad de Antioquia — Seccional Carmen de Viboral
- **Semestre:** 1
- **Edad:** 25 años
- **Descripción:** Estudiante con interés en la automatización de procesos industriales y el análisis de datos. En este proyecto asume el rol de líder del equipo, coordina las entregas, gestiona el repositorio y lidera el desarrollo del código principal.
- **Fortalezas:** Autocrítico · Autónomo · Empático · Líder · Disciplinado · Responsable

**Sharon Vanesa Trujillo Muñoz**

- **Programa:** Ingeniería Industrial
- **Universidad:** Universidad de Antioquia — Seccional Carmen de Viboral
- **Semestre:** 3
- **Edad:** 19 años
- **Descripción:** Soy una chica apasionada por aprender cosas nuevas y encontrar soluciones prácticas a los problemas. Me interesa mejorar procesos y usar la tecnología como apoyo para hacer las cosas de manera más eficiente. Me considero una persona responsable, creativa y analítica, además de alguien comprometida con sus metas. También disfruto temas relacionados con la tecnología, la naturaleza y la creatividad, lo que me ayuda a tener una visión más amplia tanto en lo académico como en lo personal.
- **Fortalezas:** Resilencia · Autoconfianza · Empatía · Versatilidad · Liderazgo · Determinación

**Diana Isabela Gómez Vera** 

- **Programa:** Ingeniería Industrial
- **Universidad:** Universidad de Antioquuia - Seccional Medellín
- **Semestre:** 3
- **Edad:** 18 años
- **Descripción:** Soy una estudiante de Ingeniería Industrial apasionada por aprender, crecer y enfrentar nuevos desafíos. Me interesa encontrar soluciones prácticas a los problemas y mejorar procesos de manera eficiente e innovadora. Me considero una persona responsable, inteligente, creativa y analítica, comprometida con cada meta que me propongo. 

Programa: Ingeniería industrial

Fortalezas:
- Responsabilidad
- Disciplina
- Creatividad 
- Proactividad
- Empatía
- Adaptabilidad

---

# 3. Nombre del proyecto
# **PrestApp**

## Descripción
PrestApp es un sistema desarrollado en Python diseñado para gestionar de manera eficiente el préstamo de objetos personales entre amigos o conocidos. Surge como solución a la problemática de pérdida de control sobre los objetos prestados, permitiendo llevar un registro organizado, automatizado y confiable de cada transacción realizada.

El software permite administrar información de usuarios (amigos), registrar préstamos y devoluciones, controlar tiempos de uso de los objetos, y generar alertas o documentos importantes como recordatorios, facturas de venta y certificados de devolución. Todo esto con el fin de evitar pérdidas, olvidos y conflictos derivados de la falta de seguimiento.

![PrestApp](https://github.com/user-attachments/assets/4a1abdb2-a78e-43a9-859b-0d62a4dbb808)

---

# 4. Licencia 
Este proyecto está licenciado bajo **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**, generada con los datos del equipo a través del enlace oficial proporcionado en las indicaciones del proyecto.

**Datos de la licencia:**
- **Autores:** Óscar Andrés Madrid Vergara, Sharon Vanessa Trujillo, Diana Isabela Gómez Vera
- **Título del proyecto:** PrestApp — Gestor de Préstamos Personales
- **Fecha de creación:** Mayo 2026
- **Tipo:** Attribution-NonCommercial 4.0 International

**¿Qué permite esta licencia?**
- Compartir: copiar y redistribuir el material en cualquier medio o formato.
- Adaptar: mezclar, transformar y construir a partir del material.
- Uso comercial: no se permite usar el material con fines comerciales.
- Atribución: siempre se debe dar crédito a los autores originales.

🔗 Ver licencia completa: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

---

# 5. Visión del proyecto

PrestApp es una herramienta de gestión de préstamos personales desarrollada en Python que funciona a través de la consola. Su propósito es resolver un problema cotidiano pero real: la dificultad de llevar un control claro sobre qué objetos se han prestado, a quién y por cuánto tiempo.

El sistema está pensado para usuarios que prestan objetos de forma frecuente entre amigos o conocidos, y que necesitan un mecanismo confiable para no perder de vista sus pertenencias, establecer límites de tiempo y actuar cuando un préstamo se extiende más de lo acordado.

### Objetivos del software

- Registrar amigos (usuarios) con su información básica de contacto y condiciones de préstamo acordadas.
- Gestionar el inventario de objetos disponibles para préstamo, clasificados por categoría.
- Registrar préstamos activos con control automático de fechas y fechas de vencimiento.
- Registrar devoluciones y emitir certificados de devolución automáticamente en archivo de texto plano.
- Generar notificaciones de recordatorio cuando un préstamo supera los 20 días.
- Generar facturas de venta automáticas cuando un préstamo supere los 30 días.

### Beneficios esperados
- Elimina la posibilidad de olvidar qué objetos se prestaron y a quién.
- Reduce conflictos entre amigos derivados de la falta de seguimiento a los préstamos.
- Automatiza la generación de documentos como certificados de devolución y facturas de venta.
- Centraliza la información de usuarios e ítems en archivos planos consultables en cualquier momento.
- Facilita la toma de decisiones sobre a quién prestar y bajo qué condiciones, con base en el historial registrado.

---

# 6. Especificación de requisitos

## Requisitos funcionales 
Los requisitos funcionales describen las acciones concretas que el sistema debe ser capaz de realizar para satisfacer las necesidades del usuario:

| ID | Nombre | Descripción detallada | Criterio de verificación |
|---|---|---|---|
| RF-01 | Registrar usuario | El sistema solicita y valida: **Nombre** (mínimo 3 caracteres, no permite números); **Apellido** (mínimo 3 caracteres, no permite números); **Documento** (solo números, entre 3 y 15 dígitos); **Correo electrónico** (debe contener `@` y terminar en `.com`); **Tiempo de préstamo** (solo acepta valores 5, 10, 15 o 30 días, cualquier otro valor es rechazado). Si algún campo no cumple la validación, el sistema muestra un mensaje de error específico y solicita ingresar el dato nuevamente. | El sistema rechaza entradas inválidas en todos los campos y almacena el registro correctamente en archivo plano cuando todos los datos son válidos. |
| RF-02 | Registrar ítem | El sistema permite registrar un objeto con: **Nombre** (mínimo 3 caracteres, permite números); **Categoría** (menú de selección con las opciones: Videojuegos, Libros, Música y video, Herramientas, Dinero, Misceláneo y varios); **Precio de compra** (valor numérico positivo); **ID único** generado automáticamente combinando letras de la categoría y un número secuencial; **Estado del ítem** evaluado mediante lógica difusa con escala de calidad (Excelente, Bueno, Regular, Malo). | El sistema genera un ID único por categoría, almacena el ítem en el inventario y rechaza registros con campos inválidos. |
| RF-03 | Registrar préstamo | El sistema lista los ítems disponibles en inventario. El usuario selecciona el ítem por ID y luego ingresa el documento del usuario al que se prestará. Si el usuario **no está registrado**, el sistema muestra el mensaje: *"El usuario no existe. Debe registrarlo antes de continuar."* y retorna al menú principal. Si el usuario **existe**, se registra el préstamo con fecha de inicio, fecha límite calculada según el tiempo pactado con el usuario, e ID del préstamo. | El sistema impide crear préstamos a usuarios no registrados, registra la fecha automáticamente y almacena el préstamo en archivo plano. |
| RF-04 | Registrar devolución y certificado | El sistema consulta los préstamos activos del usuario ingresado. Si **no tiene préstamos activos**, muestra: *"Este usuario no tiene préstamos activos registrados."* Si **tiene préstamos activos**, el usuario selecciona el ítem a devolver. Al confirmar la devolución, el sistema genera automáticamente un certificado de devolución en archivo `.txt` con nombre: `{NombrePrestador}_{FechaDevolucion}_{IDPrestamo}.txt`, que incluye toda la información del préstamo (usuario, ítem, fecha de préstamo, fecha de devolución, estado del ítem). | El sistema genera el archivo de certificado con el nombre correcto y lo almacena en la carpeta de documentos. El préstamo queda marcado como devuelto. |
| RF-05 | Generar factura de venta | El sistema identifica automáticamente todos los préstamos con más de 30 días activos. Para cada uno, genera una factura de venta en archivo `.txt` con nombre: `{NombrePrestador}_{IDPrestamo}_factura.txt`. La factura incluye: descripción del ítem, precio de adquisición (subtotal), impuesto del 23% por incumplimiento, y total a pagar. La motivación de la venta debe estar redactada en el documento. | El sistema calcula correctamente subtotal, impuesto (23%) y total. Genera el archivo con el nombre y contenido requeridos. |
| RF-06 | Consultar préstamos activos | El sistema muestra una lista de todos los ítems actualmente prestados, ordenada de mayor a menor por cantidad de días transcurridos desde el préstamo. Incluye estadísticas generales: total de préstamos activos, ítem prestado hace más tiempo, e ítem prestado más recientemente. La información se lee desde archivos planos. | La lista se muestra ordenada correctamente y las estadísticas corresponden a los datos almacenados. |
| RF-07 | Módulo administrador | El acceso está protegido por usuario y contraseña almacenados en un archivo de credenciales. Si los datos son incorrectos, el sistema muestra un error y no permite el ingreso. Si son correctos, muestra un submenú con los siguientes reportes: total de préstamos registrados, total de ítems devueltos, total de ventas realizadas, total recaudado por ventas, lista completa de usuarios registrados, y usuario con mayor y menor cantidad de préstamos históricos. | El sistema deniega acceso con credenciales incorrectas. Todos los reportes muestran datos coherentes con los archivos planos almacenados. |
  
## Requisitos no funcionales
Los requisitos no funcionales definen las condiciones de calidad bajo las cuales el sistema debe operar:

| ID | Nombre | Descripción detallada | Criterio de verificación |
|---|---|---|---|
| RNF-01 | Usabilidad | El menú principal debe tener exactamente 7 opciones numeradas. Cada opción debe tener un mensaje de confirmación o error claro. El sistema no debe cerrarse inesperadamente ante entradas inválidas del usuario. | Un usuario sin conocimientos técnicos puede navegar el menú sin asistencia en menos de 2 minutos. |
| RNF-02 | Persistencia de datos | Toda la información (usuarios, ítems, préstamos, devoluciones, ventas) debe almacenarse en archivos planos `.txt` o `.csv`. Los datos deben mantenerse disponibles entre sesiones del programa. | Al cerrar y volver a abrir el programa, todos los registros anteriores están disponibles y sin alteraciones. |
| RNF-03 | Exportación a CSV | El sistema debe permitir exportar los reportes del módulo administrador en formato `.csv` usando las librerías estándar de Python. | El archivo `.csv` generado puede abrirse correctamente en Excel o LibreOffice Calc sin errores de formato. |
| RNF-04 | Compatibilidad | El programa debe ejecutarse en Windows, macOS y Linux con Python 3.8 o superior instalado, sin necesidad de librerías externas adicionales (solo librería estándar de Python). | El programa se ejecuta correctamente desde consola con el comando `python main.py` en los tres sistemas operativos. |
| RNF-05 | Seguridad de acceso | Las credenciales del administrador deben almacenarse en un archivo separado. El módulo de administración solo es accesible con usuario y contraseña correctos. El sistema tiene máximo 3 intentos fallidos antes de bloquear el acceso temporalmente. | El acceso al módulo administrador es imposible sin credenciales válidas. |
| RNF-06 | Mantenibilidad del código | El código debe estar organizado usando clases y objetos. La clase de préstamos debe llamarse `clsPrestamo` y la clase de usuarios `clsUsuarios`. Todo el código debe incluir documentación interna con el código `pf_Algoritmos` en los encabezados de las clases y funciones. | El código puede ser modificado por cualquier integrante del equipo sin romper otras funcionalidades. Las clases tienen los nombres exactos requeridos. |

# 7. Plan de proyecto

## Cronograma de actividades (Diagrama de gantt)

![Diagrama de gantt]<img width="1033" height="1094" alt="Diagrama de Gantt" src="https://github.com/user-attachments/assets/67d9e440-c610-4249-90dd-19038797d0b2" />




## Presupuesto

**Base del cálculo:**
- Salario Mínimo Legal Vigente (SMLV) Colombia 2026: **$1.750.905 COP**
- Horas laborales: **50 horas**
- Valor hora de práctica profesional: $1.750.905 ÷ 50 = **$35.018 COP/hora**

**Detalle por integrante:**

| Integrante | Horas invertidas | Valor hora | Costo individual |
|---|---|---|---|
| Óscar Andrés Madrid Vergara | 17 horas | $35.018 COP | $595.306 COP |
| Sharon Vanessa Trujillo | 17 horas | $35.018 COP | $595.306 COP |
| Diana Isabela Gómez Vera | 16 horas | $35.018 COP | $560.288 COP |
| **TOTAL EQUIPO** | **50 horas** | — | **$1.750.905 COP** |

  
