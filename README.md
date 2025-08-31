# Tarea-3
# Tarea 3 – Práctica en Linux: Manejo de Archivos, Directorios y Procesos

Este repositorio contiene el desarrollo de la práctica de manejo básico de **archivos, directorios, permisos, procesos y scripts en Linux**, realizada mediante la terminal.

---

## 📌 Actividades realizadas

### 🔹 Navegación
- Abrir terminal, ubicarse en el directorio personal (`cd ~`).
- Verificar ubicación con `pwd`.
- Listar archivos y directorios con `ls -l`.

![pwd](images/pwd.png)
![ls](images/ls.png)

---

### 🔹 Creación de directorios y archivos
- Crear carpeta principal `Practica_Linux` con subdirectorios `Documentos` y `Backup`.
- Crear archivo `nota.txt` dentro de `Documentos` con `touch`.
- Editar con `nano` y escribir: *Hola, este es mi primer archivo en Linux*.

![mkdir](images/mkdir.png)
![nano](images/nano.png)

---

### 🔹 Copiar y renombrar
- Copiar `nota.txt` a `Backup` usando `cp`.
- Renombrar a `nota_final.txt` con `mv`.

![cp](images/cp.png)
![mv](images/mv.png)

---

### 🔹 Eliminar y ver contenido
- Eliminar carpeta `Backup` (si está vacía con `rmdir`, si no con `rm -r`).
- Mostrar contenido de `nota_final.txt` con `cat`.

![cat](images/cat.png)

---

### 🔹 Permisos
- Cambiar permisos de `nota_final.txt` con `chmod 600`.
- Verificar con `ls -l`.

![chmod](images/chmod.png)

---

### 🔹 Buscar y filtrar
- Buscar archivo con `find ~ -name "nota_final.txt"`.
- Buscar palabra "Linux" dentro de los documentos con `grep`.

![find](images/find.png)
![grep](images/grep.png)

---

### 🔹 Procesos
- Ver procesos con `top` o `htop`.
- Ejecutar `sleep 300 &` y finalizar con `kill [PID]`.

![top](images/top.png)

---

### 🔹 Paquetes
- Actualizar repositorios con `sudo apt update`.
- Instalar `cowsay` con `sudo apt install cowsay`.
- Ejecutar:  
  ```bash
  cowsay "Ejercicio completado!"
