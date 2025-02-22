# Application-Web-Design

**Nombre:** Julio Cesar Santos Martinez  
**Matrícula:** 3063416
**Carrera:** Ingeniería en Desarrollo de Software  
**Semestre:** Sexto semestre 

**Materia:** Diseño de aplicaciones web  
**Profesor:** Jose Antonio Leon Borges

## **Opciones de Etiquetado en Markdown**

---

- **Encabezados:** Se crean usando `#` (Ejemplo: `# Encabezado 1`, `## Encabezado 2`, etc.).
- **Énfasis:** 
  - *Itálicas* se escriben con un asterisco o guion bajo (`*texto*` o `_texto_`).
  - **Negritas** se logran con dos asteriscos o guiones bajos (`**texto**` o `__texto__`).
- **Listas:** 
  - Listas ordenadas se crean con números (1., 2., 3., ...).
  - Listas desordenadas se crean con guiones, asteriscos o signos más (`-`, `*`, `+`).
- **Enlaces:** Se crean con el formato `[texto](URL)`.
- **Imágenes:** Se insertan similar a los enlaces pero con un signo de exclamación al inicio (`![texto alternativo](URL-de-la-imagen)`).
- **Citas:** Se utilizan el símbolo mayor que (`>`) para generar bloques de cita.
- **Código:** 
  - En línea: Se enmarca el texto con una comilla invertida (`` `código` ``).
  - Bloques de código: Se utilizan tres comillas invertidas (```` ``` ````) antes y después del bloque.

---

## Comandos de Git Utilizados

A continuación se enlistan algunos comandos de Git básicos y avanzados, junto con una breve descripción de su uso:

- **Comprobar el estado del repositorio local:**
  ```sh
  git status
  ```

- **Agregar un archivo individual:**
```sh
git add nombre_del_archivo.ext
```

- **agregar todos los archivos modificados:**
```sh
- git add .
```

- **Crear un commit con un mensaje descriptivo:**
```sh
- git commit -m "Descripcion del commit"
```

- **Subir los cambios al repositorio remoto:**
```sh
- git push -u origin main
```
- **Crear y eliminar ramas-->**
    - **Crear nueva rama:**
    ```sh
    - git branch nombre-de-la-rama
    ```
    - **Cambiar a otra rama:**
    ```sh
    - git checkout nombre-de-la-rama
    ```
    - **Ver todas las ramas:**
    ```sh
    -git branch
    ```
    - **Eliminar una rama:**
    ```sh
    -git branch -d nombre-de-la-rama
    ```
- **Retroceder el repositorio a un commit especifico-->**
    - **Para visualizar el repositorio en el estado de un commit anterior (sin modificar la rama actual):**
    ```sh
    - git checkout <commit_hash>
    ```
    - **Para mover la rama actual a un commit anterior (deshaciendo commits posteriores):**
    ```sh
    - git reset --hard <commit_hash>
    ```