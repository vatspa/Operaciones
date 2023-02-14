# Control de AIRAC

## Trabajar con el proyecto
1. Instalar Github Desktop: https://desktop.github.com/
2. instalar Sublime Text: https://www.sublimetext.com/
3. Clonar Repositorio en github desktop.
4. Mover el fichero ``pre-commit.file`` a ``.git/hooks/``
5. Seleccionar la rama correcta. En caso contrario no nos dejará subir los cambios.
6. Click Derecho en el Repositorio Operaciones y "Open in Sublime Text".

</br>


## Forma de trabajo.


![image](https://user-images.githubusercontent.com/68125167/218854356-ced7c7b8-ade7-4cb0-8f2b-6780e749ed0c.png)


### 1. Semana post-AIRAC-release.
- Coger requisitos del AIRAC siguiente + 1 (Si el siguiente es 2302, trabajar en el 2303).
- Crear Milestone por cada FIR y AIRAC (ej. 2303-LECB).
- Crear Issue por cada cambio a hacer (Especificar Milestone y Labels).

### 2. Una vez obtenidos requisitos.
- Trabajar sobre la rama por cada airac (ej. 2302) y nunca sobre **ESTABLE**.
- Hacer "Push" vinculando **siempre** una issue con # y el id de la issue -> #32.

### 3. Dia previo salida AIRAC
- Pull Request rama proximo airac a **ESTABLE**.
