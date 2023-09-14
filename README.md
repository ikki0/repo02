# repo02

## <span style="color:blue">Comandos Últiles de git</span>, 




| Comando                                            | Funcionalidad                                                                                                                                                        |
| :------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. git init                                        | Inicializa un directorio que aún no tenga un sistema control de versiones, tras usarlo, se debería de ver un archivo .git                                            |
| 1. git add nombreArchivo                           | Agregar el archivo específico  untracked o con cambios al area del staged                                                                                            |
| 2. git add .                                       | Agregar todos los archivos untracked o con cambios al area del staged                                                                                                |
| 3. git commit -am                                  | Agrega todos los ficheros del directorio de trabajo hacía el staged y a continuación hacemos un commit para envíarlo al repositorio local aligned                    |
| 4. git push                                        | Envíamos todos los arhivos commiteados (repositorio local) al repositorio remoto                                                                                     |
| 5. git status                                      | Muestra el estado actual del repositorio                                                                                                                             |
| 6. git config --global user.name  'usuario github' | Agregamos un usuario                                                                                                                                                 |
| 7. git config --global user.email 'email github'   | Agregamos un email de git                                                                                                                                            |
| 8. git rm --cached nombreArchivo                   | Elimina el archivo indicado del staged                                                                                                                               |
| 9. git restore .                                   | Elimina todos los archivos del area del staged                                                                                                                       |
| 10. git log                                        | muestra todos los cambios que existen enel repositorio remoto                                                                                                        |
| 11. git log --oneline                              | muestra todos los cambios en el repositorio remoto en una sola línea, sin el autor ni la fecha                                                                       |
| 12. git fetch origin  nombreRama                   | Descarga todos los cambios de la rama indicada sin reemplazar los cambios en el repositorio local                                                                    |
| 13. git pull                                       | Descarga todos los cambios del repositorio remoto y reemplaza todos los cambios en el repositorio local                                                              |
| 13. git pull --rebase origin nombreRama            | Descarga todos los cambios del repositorio remoto y reemplaza todos los archivos del repositorio local y además mantiene el historial de cambios (todos los commits) |
| git rebase                                         | Sirve para     Sirve para fusionar dos ramas , se conserva el historial de cambios                                                                                   |
| 14. git rebase --continue                          | Sirve para continuar después de haber resuleto un conflicto manuealmente                                                                                             |
| 15. git push origin+nombreRama                     | Esto fuerza a hacer un git push independiemente de los conflictos que existan ⚠️                                                                                      |
| 16. git restore --staged nombreArchivo             | Elimina los archivos que estan en el area stage                                                                                                                      |
| 17. git log --graph                                | muestra todos los cambios del repositorio remoto en forma de grafo                                                                                                   |
| git log --graph --oneline                          | muestra en linea cada commit y con grafos *                                                                                                                          |
| git cherry pick nombre                             | Aplica un commmit de una rama en específico hacía otra rama distinta. Puede generar conflictos ⚠️                                                                     |
| git clone                                          | Clona un repositorio que se encuentra en remoto y lo crea en local. Es la manera más rápida de crear un repositorio.                                                 |
| git checkout  nombreRama                           | Cambia a la rama específica                                                                                                                                          |
| git checkout -b nombreRama                         | Crea una rama nueva con el nombre indicado y se mueve hacía dicha rama                                                                                               |
| git remote -v                                      | muestra todos los repositorios remotos                                                                                                                               |
| git show                                           | muestra el historial de cambios de la dos los cambios                                                                                                                |
| git branch                                         | muestra todas las ramas                                                                                                                                              |
| git merge                                          | Hacce merge, hace una unión entre ramas                                                                                                                              |
| git branch nombreRama                              | crea una rama con el nombre indicado                                                                                                                                 | a             |
| git merge --no-ff nombreAlgo -m "mensajeDeEjemplo" | Hace el merge entre ramas, non fast forward significa que mantene el historial de cambios y agrega un commit tras finalizar, suele ser más popular                   | git branch -d | eliminar rama |

><<Solo sé que no sé nada», **Sócrates**.
