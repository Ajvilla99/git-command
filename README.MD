# **COMANDOS DE GIT**
* **git --version** : Ver la version que tienes instalada en el dispositivo.

* **git help** : Git muestra todos los comandos disponibles.

        git help

## **GIT CONFIG**

* **git -config**: Este comando va bien para establecer las opciones de configuración para instalar Git. Normalmente, solo es necesario usarlo inmediatamente después de instalar Git en un nuevo equipo de desarrollo.

        git -config

 * **git config --global user.name**: Configurar Nombre que salen en los commits.

        git config --global user.name "your_name"

 * **git config --global user.email**: Este ejemplo escribe el valor your_email@example.com en el nombre de configuración user.email. La marca --global la usa para que se defina este valor para el usuario actual del sistema operativo.

        git config --global user.email "your_email@example.com"

 * **git config --global -e**: 

        git config --global -e

 * **git config --global alias**:   Muestra o modifica los alias de los comando.

        git config --global alias."añadir_alias" "Añadir_comando_al_alias" 

>Por ejemplo para hacer un **status --short**.

        git config --global alias.s "status --short"

 * **git init** : Inicializa un directorio como un  repositorio de git.

        git init

 * **git add** : Mueve los cambios del directorio de trabajo al área del entorno de ensayo. Así puedes preparar una instantánea antes de confirmar en el historial oficial.

        git add nombre_del_archivo o git add . (agrega todo)

 * **git commit -m**: Confirma la instantánea preparada en el historial del proyecto. En combinación con git add, define el flujo de trabajo básico de todos los usuarios de Git.

        git commit -m "Mensaje_del_commit"

 * **git Checkout**: Además de extraer las confirmaciones y las revisiones de archivos antiguas, git checkout también sirve para navegar por las ramas existentes. Combinado con los comandos básicos de Git, es una forma de trabajar en una línea de desarrollo concreta.
    > Devuelve los archivos al ultimo commit, ( Solo los archivos que se les esta dando seguimiento por GIT )

        git checkout -- .


 * **git status**: Lista un estado actual del repositorio con lista de archivos modificados o agregados.

        * 


 * **git log**: Muestra los logs de los commits realizados.

        git log 

    
 * **git branch**: Se encarga de mostrar cuales son las ramas del proyecto.

         git branch

    
 * **git config --global init.defaultBranch**: Indica la rama predeterminada que se utilizará al inicializar un nuevo repositorio.

        git config --global init.defaultBranch nombre_de_la_rama
    
# **GIT ADD**

Mueve los cambios del directorio de trabajo al área del entorno de ensayo. Así puedes preparar una instantánea antes de confirmar en el historial oficial.

> **git add .** -    
       
       git add

* **git add .**:     

       git add

* **git add .**:     

       git add


# **GIT COMMIT**

* **git commit**: Guardar cambios en el historial de Git.

       git commit
       
>  **-m**  "Comentario sobre lo que se ha hecho y/o modificado"

       git commit -m "comentario"
       
>  **-am**  ""

> a

> b

       git commit -am "comentario"
       
>  **-m**  ""

       git commit -m "comentario"
                
>  **-m**  ""

       git commit -m "comentario"
         
<!--     
 * ****: 

         #
    
 * ****: 

         #
    
 * ****: 

         #
    
 * ****: 

         #
    
 * ****: 

         # -->


         

    

# **PALABRAS CLAVES**

> **Commit**: Es una captura instantánea del estado actual

> **Merge**: Es la unión de dos o más ramas

