# Trabajo Práctico: Exploración del Sistema de Archivos en Linux

**Estudiante:** Tiago Enriquez  
**Curso:** Mantenimiento de Software (E.E.T. N° 3139)  
**Entorno:** Kali Linux (WSL)

---

## Consignas y Evidencias

### 1. Exploración del directorio raíz (`/`)
Se ejecutó el comando para listar de forma detallada los directorios del sistema raíz.
)
> **Descripción:** Permite visualizar los directorios esenciales del sistema operativo (como `/bin`, `/etc`, `/home`, `/proc`, `/sys`) junto con sus permisos y metadatos.

### 2. Sensibilidad a mayúsculas y minúsculas (*Case Sensitivity*)
Se crearon archivos utilizando distintas capitalizaciones mediante el comando `touch`.

> **Descripción:** Demuestra que Linux diferencia entre mayúsculas y minúsculas, permitiendo que coexistan archivos como `ejercicios.txt` y `Ejercicios.txt` de forma independiente.

### 3. Archivos Ocultos
Se trabajó con la creación y visualización de ficheros ocultos.

> **Descripción:** Se comprobó que los archivos que comienzan con un punto (`.`) son omitidos por el comando `ls` estándar y solo se revelan al utilizar el modificador `-la`.

### 4. Creación de Directorios
Se estructuró el directorio de trabajo bajo buenas prácticas.

> **Descripción:** Organización de directorios sin espacios ni caracteres especiales para asegurar la compatibilidad en entornos Linux.

### 5. Exploración de directorios virtuales (`/proc` y `/dev`)
Se inspeccionaron los directorios del kernel y dispositivos.

> **Descripción:** `/proc` refleja información dinámica de los procesos en la memoria RAM y el núcleo, mientras que `/dev` agrupa las interfaces para la abstracción del hardware.


------------------------------------------------------------------------------------------------
tp n°2 


ls	Lista archivos y carpetas.
ls -l	Lista archivos y carpetas con información detallada.
ls -a	Muestra también archivos ocultos.
ls -la	Muestra archivos ocultos y toda su información detallada.

<img width="1907" height="922" alt="image" src="https://github.com/user-attachments/assets/12cbf0c0-e418-43f9-8972-5d224e7ae0f7" />


<img width="1270" height="937" alt="image" src="https://github.com/user-attachments/assets/fa4fa6c0-0236-48fc-a5a3-0096f748fe4a" />

------------------------------------------------------------------------------------------------
 <img width="1906" height="957" alt="image" src="https://github.com/user-attachments/assets/72c80554-7a2c-4385-82d2-90fb4bc63dda" />

 -----------------------------------------------------------------------------------------------
 uso del kill

luego de usar el comando top, nos va a decir el PDI y luego para usar el comando kill para terminar un proceso colocamos el comando kill y el pdi 
si vemos que con esto no funciona colocamos kill -9 PDI para forzar el cierre de el proceso 

 -----------------------------------------------------------------------------------------------
 1<img width="1917" height="757" alt="image" src="https://github.com/user-attachments/assets/3ef17483-e16c-4e74-8c03-cad6a7e774c6" />

 2<img width="1891" height="240" alt="image" src="https://github.com/user-attachments/assets/c3c5b97b-6251-4cef-9490-73d0bcbe0459" />
 username-a
 Muestra información general del sistema operativo y de su núcleo (kernel). Por ejemplo, permite conocer el nombre del sistema, la versión del núcleo, el tipo de máquina y la arquitectura del procesador.
 free
 Muestra información sobre la memoria RAM de la computadora, indicando cuánta memoria está utilizada, cuánta está libre y cuánta está disponible. También muestra información sobre la memoria de intercambio (swap).

--------------------------------------------------------------------------------------------
espacio en el disco 
<img width="1486" height="512" alt="image" src="https://github.com/user-attachments/assets/d56ffe08-1c18-4b29-b520-bde161e30483" />
uso del comando ping 
<img width="1170" height="517" alt="image" src="https://github.com/user-attachments/assets/152bf0db-eb8c-4a7b-9dfd-359771acc963" />

El comando ping se utiliza para comprobar si hay conexión entre nuestra computadora y otro dispositivo dentro de una red o Internet. También permite saber cuánto tarda en llegar y volver la información, ayudando a detectar posibles problemas de conexión.
