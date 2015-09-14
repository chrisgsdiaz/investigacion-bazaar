# Bazaar (Características)

Dentro de las caracteristicas que encontramos en Bazaar tenemos:

- Gestiona el almacenamiento de cada uno de los elementos del proyecto.
- Capacidad de gestionar ramas de desarrollo paralelas a la principal.
- Gestión de conflictos, en el caso de un usuario cambie un elemento de un proyecto.
- Generación de informes de estado, donde se muestren las diferencias entre las distintas versiones.
- Proporciona soporte para IDEs y editores como Eclipse, Visual Studio, Emacs, entre otros.

Sin embargo, a diferencia de CVS o Subversion, Bazaar nos permite trabajar de formas mucho más flexibles… desde el típico esquema cliente-servidor hasta la descentralización de los repositorios.
Con Bazaar tenemos la posibilidad de trabajar de una forma más flexible que CVS o Subversion, adaptándose al flujo de trabajo que queramos utilizar:

  - Centralizado o Lock-Step: Concepto de trabajo igual que el aplicado por Subversion o CVS con la ventaja de una gestión de ramas mejorada mediante un repositorio.
  - Lock-Step con commits locales: Igual que el anterior pero los desarrolladores realizan commits locales sin modificar el servidor hasta que consideran oportuno actualizarlo. Tenemos la ventaja de reducir el número de commits erróneos que interfieran en el trabajo del resto de desarrolladores.
  - Descentralizado con linea principal compartida: Cada programador tiene su propia rama además de permisos en la rama principal. Cada uno trabaja en su rama personal (commit) y cuando lo consideran apropiado, lo fusionan con la rama principal (pull, merge). Ventajas:
    - Organización del trabajo sencilla.
    - Un desarrollador puede fusionar su rama con la de otra persona con la que este trabajando en algo conjuntamente.
  - Descentralizado con guardián automático o manual: Cada programador tiene su propia rama y permisos de solo lectura en la rama principal. Cuando un desarrollador quiere fusionar su código en la linea principal, lo pide al “guardián” que se encarga de revisar, compilar y hacer tests unitarios para comprobar que todo es correcto. La ventaja principal radica en que el código se revisa antes de pasar a la línea principal. 

 ## Proyectos
Proyectos destacados que utilizan Bazaar como sistema de control de versiones:

- GNU Mailman 
- Ubuntu
- GNU Mailman
- GNU Emacs
- Inkscape
- MySQL
- Gnash
- Squid






