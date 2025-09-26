# MARKDOWN
# Esto es un encabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6

```
sudo systemctl start apache2
```

```bash
#!/bin/bash
echo "Hola mundo"
```

``` phyton
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')

``` yaml
version: '3'

services:
  apache:
    build: ./apache
    ports:
      - 80:80
    volumes:
     - ./src/var/www/html
```

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2] 
[1]: https://iescelia.org
[2]: https://github.com

![](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)

Item 1
Item 2
Item 3
Item 4

Item 1
  Item 1.1
  Item 1.2
Item 2
  Item 2.1
Item 3
Item 4

1. Item 1
2. Item 2
3. Item 3
4. Item 4

1. Item 1
  1.1 Item 1.1
  1.2 Item 1.2
2. Item 2
  2.1 Item 2.1
3. Item 3
4. Item 4

| Encabezado 1 | Encabezado 2 | Encabezado 3 
| --- | --- | --- | ---
| Fila 1.1 | FIla 1.2 | Fila 1.3
| Fila 2.1 | Fila 2.2 | Fila 2.3
| Fila 3.1 | Fila 3.2 | FIla 3.3

Por ejemplo, en esta frase 
hemos forzado un salto de línea


Este texto no es una cita.
> Este texto daría como resultado una cita

