# **1.- ¿Cómo se inicializa un repositorio en Git?**
```bash 
git init
```
> **Esto desde la terminal que nos ofrece nuestro programa de codigo como es nuestro caso de Visual Studio.**
# **2.- ¿Cómo creas un repositorio en GitHub?**
**_1.- Entrar al siguiente link que es la pagina oficial de
[Github](https://github.com/)_**

**_2.- Crear/Iniciar cuenta de Github esto para que se guarden los repositorios creados._**

**_3.- En la parte superior derecha esta el signo "+" seleccionas y le das a crear nuevo repositorio._**

**_4.- Sigue los pasos que te ofrecen en la propia pagina y listo._**

#  **3.- ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?**

**1.- Primero que todo inicias/creas en tu repositorio local despues usas el comando**
```bash 
git init
```
**2.- Ya que tengas tus archivos listos haces tu commit**
```bash 
git commit -m "nombre de tu commit" 
```
**3.- Ya creado tu commit sigue el vincular con el repositorio de Github usando el comando**
```bash 
git remote add origin "Link de tu repositorio creado al inicio"
```
**4.- Ya vinculado lo que sigue es hacer el push a la rama main con el comando**

```bash
git push -u origin main
```
**5.- Y listo ya quedaría tu repositorio vinculado a Github.**

# **¿Cuál es el flujo básico de trabajo en Git y GitHub?**
### **Clonación de repositorio:**
```bash 
git clone URL del repositorio
```
### **Inicializar un repositorio en Git:**
```bash 
git init
```
### **Mandar archivos al stage:**
```bash 
git add .
```
### **Hacer un Commit**
```bash 
git commit -m "Nombre del commit"
```
### **Hacer push a main:**
```bash 
git push origin main
```
### **Crear ramas:**
```bash 
git checkout -b nombre-de-la-rama (usando "-")
```
### **Fusionar Cambios**
```bash 
git checkout main

git merge nombre-de-la-rama
```
# **¿Para qué sirve el archivo .gitignore?**
### El archivo .gitignore especifica qué archivos y carpetas Git debe ignorar en un proyecto, evitando que se incluyan en el control de versiones.

# **¿Cuál es el propósito de una rama?**
### Las ramas son herramientas clave para gestionar el código, permitiendo crear nuevos caminos para el desarrollo y trabajar en paralelo con otras. Este artículo explora su función y cómo utilizarlas en un proyecto.

# ¿Qué es una fusión?
### Una fusión en programación es el proceso de combinar cambios de diferentes ramas en sistemas de control de versiones como puede ser Git. Puede ser automática, sin conflictos, o requerir resolución manual si hay conflictos.

# Explica los diferentes tipos de fusiones que existen.
###  
**1.- Fast-forward: Cuando no hay conflictos.**

**2.- Merge commit: Crea un nuevo commit de fusión.**

**3.- Squash: Combina todos los commits en uno solo.**

# ¿Cómo puedes ver el historial de tu repositorio?

```bash 
git log
```
# ¿Cuál es el propósito de una etiqueta?

### Marca puntos específicos en el historial del repositorio, como versiones o hitos. Su función incluye identificar versiones, ser inmutable, facilitar la navegación y ayudar en el despliegue.





