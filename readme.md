1. Las ramas utilizadas son 
Ramas de desarrollo y maestra (develop, master, main)
Ramas de función (feature)
Ramas de publicación (release)
Ramas de corrección (hotfix)
2. El flujo general de Gitflow es el siguiente:
Se crea una rama de desarrollo a partir de la maestra.
Una rama de publicación se crea a partir de la de desarrollo.
Las ramas de función se crean a partir de la de desarrollo.
Cuando una función está completa, se fusiona en la rama de desarrollo.
Cuando la rama de publicación está lista, se fusiona en la de desarrollo y la maestra.
Si se detecta una incidencia en la maestra, se crea una rama de corrección a partir de la maestra.
Una vez que la corrección está completa, se fusiona tanto con la de desarrollo como con la maestra.
3. Adjunta un pantallazo del comando git log --oneline --decorate --graph --all
4. Una vez subido el repositorio CON TODAS SUS RAMAS, adjunta un pantallazo del apartado de GitHub "Insights"/"Network graph" 