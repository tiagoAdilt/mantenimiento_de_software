# Trabajo Práctico: Exploración del Sistema de Archivos en Linux

**Estudiante:** Tiago Enriquez  
**Curso:** Mantenimiento de Software (E.E.T. N° 3139)  
**Entorno:** Kali Linux (WSL)

---

## Consignas y Evidencias

### 1. Exploración del directorio raíz (`/`)
Se ejecutó el comando para listar de forma detallada los directorios del sistema raíz.
![Directorio Raíz](assets/01_raiz_ls.png)
> **Descripción:** Permite visualizar los directorios esenciales del sistema operativo (como `/bin`, `/etc`, `/home`, `/proc`, `/sys`) junto con sus permisos y metadatos.

### 2. Sensibilidad a mayúsculas y minúsculas (*Case Sensitivity*)
Se crearon archivos utilizando distintas capitalizaciones mediante el comando `touch`.
![Case Sensitivity](assets/02_case_sensitivity.png)
> **Descripción:** Demuestra que Linux diferencia entre mayúsculas y minúsculas, permitiendo que coexistan archivos como `ejercicios.txt` y `Ejercicios.txt` de forma independiente.

### 3. Archivos Ocultos
Se trabajó con la creación y visualización de ficheros ocultos.
![Archivos Ocultos](assets/03_archivos_ocultos.png)
> **Descripción:** Se comprobó que los archivos que comienzan con un punto (`.`) son omitidos por el comando `ls` estándar y solo se revelan al utilizar el modificador `-la`.

### 4. Creación de Directorios
Se estructuró el directorio de trabajo bajo buenas prácticas.
![Creación de Directorios](assets/04_creacion_directorio.png)
> **Descripción:** Organización de directorios sin espacios ni caracteres especiales para asegurar la compatibilidad en entornos Linux.

### 5. Exploración de directorios virtuales (`/proc` y `/dev`)
Se inspeccionaron los directorios del kernel y dispositivos.
![Directorio Proc y Dev](assets/05_proc_dev.png)
> **Descripción:** `/proc` refleja información dinámica de los procesos en la memoria RAM y el núcleo, mientras que `/dev` agrupa las interfaces para la abstracción del hardware.
