# Ejercicio en parejas: Codespaces, Forks y Pull Requests

## Objetivo
Aprender a colaborar en un repositorio de GitHub usando Codespaces, aplicando los pasos típicos de trabajo en equipo:
- Creación de repositorio
- Fork
- Desarrollo
- Commits
- Pull Requests
- Merge

## Roles
- Alumno A: dueño del repositorio.
- Alumno B: colaborador que hará un fork y propondrá cambios.

---

## Instrucciones

### 1. Alumno A – Crear el repositorio
1. Crear un repositorio en GitHub llamado `colaboracion-codespaces`.
2. Dentro del repositorio, crear este archivo `README.txt` con las instrucciones del ejercicio.
3. Subirlo con commit y push.

---

### 2. Alumno B – Hacer un fork y trabajar en Codespaces
1. Ir al repositorio de Alumno A y hacer **Fork**.
2. Abrir el fork en **GitHub Codespaces**.
3. Crear un archivo `saludo.py` con el siguiente código en Python:

```python
nombre = input("¿Cuál es tu nombre? ")
print(f"¡Hola {nombre}, bienvenido/a al repositorio colaborativo!")

3.-Ejecutar el programa en Codespaces para verificar que funciona.

4.-Guardar cambios, hacer commit y push. sugerencia(feature/tu-nombre)

5.-Desde GitHub, crear un Pull Request (PR) hacia el repositorio original de Alumno A.
