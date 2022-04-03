# Git
```sh
# descagar cambios
git pull origin master

# subir cambios

git add . # agregar los cambios antes de hacer el commit
git add 04_exercise.ipynb # Si queremos agregar un archivo en particular
git status -s # ves los cambios

git commit -m "[mi comentario]" # se hace el commit de los cambios
git push origin master # subir los cambios al repositorio
```

# Initial
```sh
jupyter notebook
```

# Env

```sh
conda search --full-name python # vemos las versiones de python disponibles
conda create -n python3_7_1 python=3.7.1 # creamos un env

conda env list # vemos los env disponibles
conda activate python3_7_1 # activamos el env
```
