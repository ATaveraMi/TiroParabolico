## Cambios realizados por Marce

### Punto uno - hacer el proyectil y los balones más rápidos

Se ha implementado una nueva velocidad para los proyectiles:

- **Velocidad**: 

### Nueva funcionalidad

- Se cambió el `ontimer(move, 50)` a `ontimer(move, 25)`, haciendo los proyectiles más rápidos
### Código clave


## Cambios realizados por Tavera

### Borrar función que acaba el juego


- **se borró la línea que finalizaba el juego**

### Reposicionar elementos

- Se agregó la siguiente condición

```python
  else:
        #Reposicionar
        ball.x = -199
        ball.y = -199
        speed.x = 0
        speed.y = 0
