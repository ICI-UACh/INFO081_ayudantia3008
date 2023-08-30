# ayudantia3008
# Ayudantia 30/08

### Ejercicio 1: Artistas y canciones

Dada un string de artistas y canciones con el siguiente formato:

```bash
arte = "easykid-tanjiro,drefquila-afuego,drefquila-demasiao,jordan23-ando"
```

Programe en Python una funcion llamada **info_a_tupla()**, esta debe recibir el String y retornar una lista de tuplas, en donde cada tupla contiene el artista y cancion leído en el string. Esta lista se muestra a continuación:

```bash
[('easykid', 'tanjiro'),
 ('drefquila', 'afuego'),
 ('drefquila', 'demasiao'),
 ('jordan23', 'ando')]
```

Luego cree otra función llamada **encuentra_artistas_unicos()**, esta debe recibir la lista de tuplas y retornar un *set* que contenga los artistas únicos.

En este caso, el set debe ser de la siguiente manera:
```bash
{'drefquila', 'easykid', 'jordan23'}
```

Finalmente cree una función llamada **contar_canciones()**, esta debe recibir el nombre de un artista y la lista de tuplas. Esta función debe retornar la cantidad de canciones que tenga el artista (pasado como argumento).  

```bash
El artista drefquila tiene 2 canciones.
El artista jordan23 tiene 1 canciones.
El artista easykid tiene 1 canciones.
```
