# OCAML

Sean bienvenidos a conocer el lenguaje Ocaml (lenguaje proveniente de caml pero con implementación en POO - año 1995).
Ocaml es un lenguaje que cumple con 4 criterios de los buenos lenguajes: (portable, seguro, expresivo, pedagogico).

### criterios
- portable : lenguaje lo mas independiente de los detalles de la maquina.
- seguro : programas robuztos con restricciones semanticas
- expresivo : capacidad de expresar las mismas cosas con las mismas palabras.
- pedagogico : capacidad de explorar facilmente todos los conceptos basicos de la programación.

Ademas su logo es un lindo camello.

![](https://github.com/daandradec/Ocaml-Lenguajes/blob/master/Imagenes/camello.png)

![](https://github.com/daandradec/Ocaml-Lenguajes/blob/master/Imagenes/colour-logo.png)

# PRIMEROS PASOS 

Primero tratemos de tener el entorno para poder correr instrucciones del lenguaje ocaml.

## Instalación

Comencemos por ir a la pagina oficial en la sección de instalación 

[http://ocaml.org/docs/install.html](http://ocaml.org/docs/install.html)

Una vez allí podemos ver la guia de instalación para varios sistemas operativos, pero aqui daremos la guia para Ubuntu y Windows

## Ubuntu

Ejecutar el comando

```
sudo apt install ocaml
```

Con esto, ya deberiamos ser capaces de ejecutar en la terminal el comando : $ ocaml

## Windows

Para windows sera necesario instalar un paquete que permite instalar ocaml con solo ejecutar un .exe.

Primero vamos a la sección de windows y buscamos el link que dice (instalación con OCPWIN), lo que nos deberia enviara a este link

[https://www.typerex.org/ocpwin.html](https://www.typerex.org/ocpwin.html)

una vez allí descargamos la versión de 32 o 64 bits, ejecutamos el instalador, damos siguiente a todas las ventanas hasta finalizar con exito. Con esto ya debemos tener ocaml instalado y podremos ejecutar el comando ocaml en la consola de windows.

# Editores Online

Si no quieres instalar Ocaml en tu sistema puedes buscar editores online, como por ejemplo: 

[https://try.ocamlpro.com/](https://try.ocamlpro.com/)

[https://www.tutorialspoint.com/compile_ocaml_online.php](https://www.tutorialspoint.com/compile_ocaml_online.php)


# Tour por el Lenguaje

Ahora sí para empezar a conocer el lenguaje abarcaremos estas secciones

- hello world
- tipos de datos
- variables
- definiciones locales
- condicionales

### hello world

Abre la consola de ocaml y ejecuta

``` print_string "hello world";; ```

Con esta instrucción mostramos en la salida estandar la cadena hello world

#### lista de funciones nativas para impresión

- print_int ENTERO
- print_float FLOTANTE
- print_newline ()
- print_string CADENA

# Particularidades del lenguaje respecto al paradigma funcional

Ahora vayamos un poco mas profundo en el lenguaje aprendiendo estos temas que son comunes entre lenguajes de programación pero que en ocaml se manejan de manera un poco distinta. 

- funciones
- funciones recursivas
- listas
- tuplas
- tipos
- arreglos

# Ejemplos Avanzados

# Links de Referencia

[http://structio.sourceforge.net/guias/progocaml/progocaml.html](http://structio.sourceforge.net/guias/progocaml/progocaml.html)

[http://caml.inria.fr/pub/docs/manual-ocaml/language.html](http://caml.inria.fr/pub/docs/manual-ocaml/language.html)

[http://www.cs.us.es/~mjoseh/LCyTM-15/temas/tema-2.html](http://www.cs.us.es/~mjoseh/LCyTM-15/temas/tema-2.html)

[https://ocaml.org/learn/taste.html](https://ocaml.org/learn/taste.html)

[https://learnxinyminutes.com/docs/ocaml/](https://learnxinyminutes.com/docs/ocaml/)

[http://ocaml.org/learn/tutorials/basics.html#Basic-types](http://ocaml.org/learn/tutorials/basics.html#Basic-types)