# Bono académico · Demostraciones de Machine Learning

**Autor: Edwin Yunis**  
**Curso:** Machine Learning · Maestría en Ingeniería Industrial  
**Profesor:** Dr. Lihki Rubio

Compilación individual de varios ejercicios matemáticos para bono académico, basada en el documento `Demostraciones Tarea (1).docx`. Incluye correcciones fundamentadas al material de consulta y figuras tomadas del documento de consignas.

## Ver versión web

Una vez habilitado GitHub Pages, estará en `https://edwiny23.github.io/bono-demostraciones-ml-edwin/` si el repositorio se llama exactamente `bono-demostraciones-ml-edwin`. El enlace no estará activo hasta que exista el repositorio y se complete el despliegue.

## Publicar en GitHub

1. Crear un repositorio **público**, por ejemplo `bono-demostraciones-ml-edwin`, bajo `EdwinY23`.
2. Subir **los archivos y carpetas extraídos** de este ZIP a la rama `main`; no subir el ZIP comprimido como único archivo.
3. GitHub → **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Abrir **Actions** y comprobar que `Publicar Jupyter Book - Edwin Yunis` finalice con éxito.

En caso de no ejecutar el workflow, el directorio `docs/` contiene una **copia HTML independiente** que puede publicarse desde `main` / `docs` usando la opción *Deploy from a branch* de Pages. El workflow, si está habilitado, genera la apariencia nativa del Jupyter Book.

## Compilación reproducible

```bash
python -m pip install -r requirements.txt
jupyter-book build .
```

El HTML se produce en `_build/html/`.

## Material de referencia

- Notas de clase: https://lihkir.github.io/MachineLearning/
- Documento de consignas del profesor.
- Libro de referencia compartido por compañero: https://jserrano3010.github.io/demostraciones-tarea1/intro.html

El material de referencia no se presenta como coautoría; la solución individual identifica y corrige expresamente un error sustancial en el ejercicio del árbol de decisión, además de desarrollar las demostraciones solicitadas.
