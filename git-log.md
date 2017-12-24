### git log
Muestra el historial de commits.

`git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indiquemos.

### Limitar la salida del historial
`git log -n`: Cambiando la `n` por cualquier número entero, por ejemplo: `git log -2` nos mostrará los 2 commits más recientes.

`git log --after="2017-12-23 20:30:12"`: Muestra los commits realizados después de la fecha especificada.

`git log --before="2017-12-23 20:30:12"`: Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas según sean convenientes, por ejemplo: `git log --after="2017-12-23 12:00:00" --before="2017-12-23 13:30:00" --oneline`
