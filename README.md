Este es mi primer repositorio para aprender a trabajar con github y git.
- a)° inicializar Git con el comando *git init*  y te regresa un mensaje de que si se inicializo, en la carpeta del proyecto a versionar 
*git init* en una carpeta te permite usar comandos que solo Git entiendo (no funcionan fuera de la carpeta versionada) 

1-comando: *git status* es como preguntar que esta pasando en mi carpeta.
 
 2-comando: *git add .* se usa para traquear (darles seguimiento) a TODAS los archivos.
 
 3- como sirve *git commit* es para dividir un proyecto en pedazos para poder regresar, cambiar, probar, etc, se usa como *git commit -m "(agregar un resumen)" se debe de agregar un pequeño resumen de que es lo que estabas haciendo en ese commit si no pues no sabras que es lo que estabas  haciendo ahí.

- b)° Subir las carpetas del local (mi computadora) a remoto (la nube) 

1-Entrar a mi °GitHub° e iniciar un repositorio usar los comandos adecuados que digan que se subira de local a remoto.

2°copiar la primera linea (git remote add origin...), pegarla y darle enter. para sabe hacia donde se subio se usa *git remote -v* 

3° copiar la segunda linea (git branch -M main...), pegarla y dar enter para saber a que rama se subio se usa *git branch*.

4° copiar la tercera linea (git push...) pegarla y enter para que se suban a mi repositorio

pd: se puede tranbajar en variar ramas pero yo trabajare en la rama °main° las instrucciones de la 1° a la 4° solo se usan cada vez que se inicia un repositorio por primera vez y si se hace un cambio en local y quiero subirlo a remoto se usan los siguientes comandos en orden: a) *git status*, b) *git add .*, c)*git commit -m "agregar resumen"* y para finalizar d)*git push origin main*.