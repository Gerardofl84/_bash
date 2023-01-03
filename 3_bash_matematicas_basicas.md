# Funciones Matemáticas 

En esta ocasión vamos a ver como ``$BASH`` maneja diferentes tipos de datos, aunque muy poco se usan las funciones matemáticas. 

- Si queremos hacer alguna operación con **números**, tenemos que presentar la información de una manera para que ``$BASH`` entienda lo que estamos intentando hacer.  

- Específicamente en ``$BASH`` tenemos " Evaluate Expression Command " que lo usamos de esta manera: 

  - ``expr``

- ``expr``Este comando le indica a ``$BASH`` que lo que queremos es evaluar una expresión. 

```sh
expr 30 + 10

# esto imprime en consola 40
# para poder multiplicar tenemos que poner expr 10 \* 4
```

- En un script lo puedes hacer tambien de esta manera. 

```sh
num1="35"
num2="70"

echo $(($num1 + $num2))
```
