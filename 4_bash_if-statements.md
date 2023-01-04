# if Statements

Cuando estamos creando codigo, muy probablemente necesitaras tomar decisiones basadas en ciertas condiciones. Estas condiciones se evaluan con un tipo de dato llamado **Boolean**, esto es si son (verdadero o falso).

Declaraciones que ayudan a ejecutar diferentes ramas del codigo basadas en ciertas condiciones se les conoce como **" Declaraiones Condicionales "**.

``if...else`` es una de las **Declaraiones Condicionales** mas comunes que hay.

## Sintaxis

- De forma simple:

```sh
if [ condicion ]
then
  codigo a ejecutar si la condicion es verdadera
fi
```
> Nota: Los espacios son parte de la sintaxis.

- Usando ``if...else`` **else** se ejcuta en caso de la condicion se falsa.

```sh
if [ condicion ]
then
  codigo a ejecutar si la condicion es verdadera
else
  codigo a ejecutar si la condicion es falsa
fi
```

- Digamos que queremos agregar condiciones y comparaciones para hacer el codigo mas dinamico. En ese caso usamos esta sintaxis.

```sh
if [ condicion ]
then
  codigo a ejecutar si la condicion es verdadera 
elif [ condicion ]
then 
  codigo a ejecutar si la primera condicion es falsa
else
  codigo a ejecutar si las dos condiciones son falsas
fi
```


