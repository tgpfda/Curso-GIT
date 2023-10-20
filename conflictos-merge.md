## Conflictos despues del Merge:

Despues de hacer el merge de la rama proyectos con la principal hubo conflictos con el archivo README.md. El merge no combinaba de forma correcta el texto de de ambos archivos.

## Solución:
Para todo el proceso de la actividad integradora utilice el Visual Studio Code. Una vez ejecutado el merge el entorno de desarrollo VS Code me abrió una pantalla mostrando el conflicto.
Luego haciendo click en el botón "Resolve in Merge Editor" abrió una solapa que estaba dividida en tres ventanas. A la izquierda se mostraba el texto del archivo README.md de la rama proyectos y a la derecha el texto del README.md de la rama principal. Y abajo una tercer ventana de resultado (Result README.md) para la combinacion final de los dos archivos.
 Decidí combinar los textos de la siguiente manera: Primero el texto del archivo de la rama principal y a continuación el texto de la rama proyectos.
En la ventana de la rama principal elegí la opción "Accept current". Esta accion copio el texto en la ventana principal a la de Resultado.
Luego en la ventana de la rama proyectos elegí la opción "Accept incoming". Esta acción copio el texto de la ventana proyectos a la ventana de Resultados debajo del texto anterior.
Una vez combinado ambos textos de forma correcta salva los cambios mediante el botón "Complete Merge".
Y por ultimo agregue el archivo README.md al area de staging, hice el commit y persistí el cambio al repositorio remoto con un push.
