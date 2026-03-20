# Pokedex

Pokedex chiquita

## Tabla principal

* Pokedex_id(PK)

---

## Tabla pokemon

* Pokedex_id(FK)(PF)

* Nombres (UQ)

* Habilidades_id(FK)

---

## Tabla tipos y habilidades

### tipos_id(PK)

1. Nombre

### habilidades_id(FK)

1. Nombre
1. Descripción

## Tabla Pibote tipos y pokemon

* Pokemon_id(FK)(PK)

* tipos_id(FK)(PK)

## Modelo entidad relación

![Hola](Imagenes\ModeloEntidadRelacion.drawio.png)

## Modelo Relacional de la base de datos

![Hola](Imagenes\ModeloRelacionalDeLaBD.drawio.png)
