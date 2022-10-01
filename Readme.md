## Titulo
**Autor:** _Pau Madueño Sanchez._

**Introduccion:** Se trata de un sistema de control de versiones distribuido. Es decir que cualquier desarrollador 
                  del equipo que tenga acceso puede gestionar el código fuente y su historial de cambios utilizando las 
                  herramientas de línea de comandos de Git.
...

**Pasos a seguir para conseguir diferentes acciones:**
  
   1. Para **instalar** GitHub, en Linux.  
     i. Con Comandos/Codigos:
      >$ sudo apt update  
       $ sudo apt install git
      
      ii. En la Web: _No hay que instalar nada_
       > Como mucho registrarte en la web.
       
   2. A continuacion podremos comprobar si se ha instalado correctamente.  
     i. Con Comandos/Codigos:
      >$ git --version
      
      ii. En la Web: _No hay que comprobar nada_
      
   3. Para crear un Repositorio.  
     i. Con Comandos/Codigos:  
      >$ git init  
       $ git add  
       $ git commit -m “Subida del archivo de prueba”  
       $ git push

      ii. En la Web: 
       > ![Captura](https://user-images.githubusercontent.com/113713397/192711953-475c6a35-3e23-4e26-a2a9-34d106e08c1f.png) 
      
   4. Para crear un Archivo.  
     i. Con Comandos/Codigos:  
      >$ mkdir pruebaGitHub  
       $ cd pruebaGitHub  
       $ touch prueba.c  
       $ gedit prueba.c
      
      ii. En la Web: 
      > Dentro del Repositorio...  
      ![Captura2](https://github.com/PauMadu/Tema-1/blob/main/Captura2.PNG)
      
   5. Y para escribir denttro del arvhivo.
     i. Con Comandos/Codigos:
      > #include <stdio.h>  
        int main(){  
        printf(“Hola DAW”);  
        return 0; }

También tenemos la oppcion de generar un **token**, o puede que en algun momento nos lo pida.  
Entonces desde la pagina web de GitHub, entramos a **Settings**, bajaremos hasta el final de la pagina y entraremos en **Developer Settings**, a continuacion en **Personal Access Tokens**, y por último en **Generate New Token**.

**Conclusiones:**  
En mi opionion yo creo que GitHub es un buen programa para gestionar proyectos, distribuirlo, y trabajar en equipo. Ya que tiene multiples herramientas y cantidades de acciones que te permiten crear un buen codigo; como el control de _versiones de codigo_, he incluso nos permite nos da la posibilidad de personalizar nuestro perfil.  

**Bibliografia:**  
[Pagina 1](https://www.webempresa.com/hosting/que-es-github.html)  
[Pagina 2](https://platzi.com/blog/que-es-github-como-funciona/)
