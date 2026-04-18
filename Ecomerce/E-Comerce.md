# Práctica E-Comerce (Ventas)

## Lista de entidades

### clientes (ED)

- cliente_id **(PK)**
- nombre
- apellido
- email
- direccion
- cp
- ciudad
- pais_id **(FK)**

### productos (ED|EC)

- producto_id **(PK)**
- nombre
- descripcion
- foto
- precio
- stok

### ventas (ED)

- venta_id **(PK)**
- cliente_id **(FK)**
- fecha
- monto

### articulos_por_venta (EP)

- articulo_id **(PK)**
- venta_id **(FK)**
- producto **(FK)**
- cantidad

### paises (EC)

- pais_id **(PK)**
- nombre
- dominio

## Relaciones

1. Un **cliente** tiene un **pais** (1 - 1)
1. Un **Cliente** genera **ventas** (1 - M)
1. Una **venta** tiene **articulos** (1 - M)
1. Un **articulo** es un **producto** (1 - M)
