# Subversion vs Git

============================================================================

<!-- START doctoc generado TOC por favor mantenga el comentario aquí para permitir la actualización automática ->
<!-- NO EDITE ESTA SECCIÓN, EN LUGAR RE-RUN doctoc PARA ACTUALIZAR -->

**Tabla de contenido**  *generado con: [DocToc](https://github.com/thlorenz/doctoc)*

- [Sistema Centralizado vs Sistema Distribuido](#sistema-centralizado-vs-sistema-distribuido)

- [Diferencias entre Subversion y Git](#diferencias-entre-subversion-y-git)

-[Resumen subversion vs Git](#resumen-subversion-vs-git)

<!-- END doctoc generó TOC por favor mantenga un comentario aquí para permitir la actualización automática -->

# Sistema Centralizado vs Sistema Distribuido

**Subversion(sistema centralizado)  | Git(sistema distribuido).**

**Sistema centralizado**

Subversion se basa en un sistema centralizado, la principal ventaja de un sistema centralizado es su simplicidad, pero por el contrario no nos permite tener más de un repositorio central sobre el que trabajar, no podemos realizar confirmaciones (commit) si no estamos conectados al repositorio central y si estamos trabajando en un equipo de trabajo con muchos usuarios, la colaboración se complica.

**Sistema distribuido**

En el caso de un sistema distribuido es posible trabajar sin conexión al repositorio central (trabajo offline), se facilita la colaboración, podemos tener tantos repositorios externos como queramos, la mayoría de las operaciones son locales por lo que el tiempo de ejecución de las mismas se reduce considerablemente y su instalación y configuración es muy sencilla en nuestro espacio de hosting.

![Tipos de sistemas](Imagenes/sistemas.jpg)

# Diferencias entre Subversion y Git.

1. Con Subversion, no podremos conectarnos al repositorio central y, por lo tanto no podremos realizar confirmaciones (commit) ni tener un control local de versiones del código fuente.

2. Con Git, nuestra copia local es un repositorio y podemos hacer confirmaciones (commit) sobre éste y tener todas las ventajas del control de código fuente. Cuando volvamos a tener conexión con el repositorio central, podremos realizar confirmaciones sobre él.

3. Mientras que SVN tiene la ventaja de que es más sencillo de aprender, Git se adapta mejor para desarrolladores que no están conectados continuamente al repositorio central.

4. Git es más rápido en ejecución que SVN y características avanzadas, como la creación de ramas de trabajo (branching) y la combinación de ramas (merging) están mejor definidas.

# Resumen subversion vs Git.

**Git no es mejor que SVN**, sólo trabajan de forma diferente. Si necesitamos un control de código fuente offline y tenemos la disposición de gastar más tiempo en aprender un sistema de control de versiones, Git es nuestra elección.

Si tenemos un sistema de control de código fuente estrictamente centralizado y estamos iniciándonos en el control de versiones, la simplicidad de SVN nos facilitará nuestro flujo de trabajo.