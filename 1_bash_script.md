# Bash Scripting

## Que es Bash

- Bash es conocido en la industria como ``SHELL``.

- Cuando abrimos una terminal en un sistema operativo como **UNIX** o **LINUX** donde usamos comandos estamos interactuando con una ``SHELL``.

- Una ``SHELL`` nos permite ejecutar comandos que dan como resultado una impresion en la consola.

- Una ``SHELL`` nos permite trabajar con un sistema por medio de comandos.


## Que es un Bash Script.

- En esencia es un archivo de texto el cual contiene uno o varios comandos en su interior.

### Como convertir estos comandos en un Script.

1.Crear el archivo con terminación .sh (esto no es necesario, pero es una práctica común). 
  ```sh
  nvim myScript.sh
  ```

2. Hacer el archivo ejecutable.
  ```
  chmod +x myScript.sh
  ```

3. Correr el Script
  ```
  ./myScript.sh
  ```


## La forma correcta de escribir un Bash Script

-La primera línea de un bash Script es conocido como ``shebang``.  

  ```sh
  #!/bin/bash
  ```

> El ``#!/bin/bash`` le dice al Script que interprete debe de usar.


## Hello World

```sh
#!/bin/bash

echo "Hello World"
```
