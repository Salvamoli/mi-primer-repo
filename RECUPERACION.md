# Recuperación de un archivo eliminado accidentalmente

## Qué error simulé

Simulé un error borrando accidentalmente el archivo `errores.sh` de mi repositorio. Este archivo contenía un pequeño script de Bash.

## Qué comandos utilicé para recuperar el archivo

Utilicé los siguientes comandos para recuperar el archivo:

1. **`git reflog`**: Este comando me permitió ver el historial de los cambios recientes en mi repositorio, incluyendo los commits previos.
2. **`git checkout HEAD@{1} errores.sh`**: Este comando me permitió recuperar el archivo `errores.sh` de un commit anterior utilizando la referencia que obtuve con `git reflog`.

## Qué aprendí de la experiencia

Aprendí que Git ofrece herramientas como `git reflog` y `git checkout` que me permiten recuperar archivos eliminados accidentalmente. Es importante saber cómo usar estas herramientas para evitar pérdidas de datos no deseadas en el trabajo con repositorios Git.
