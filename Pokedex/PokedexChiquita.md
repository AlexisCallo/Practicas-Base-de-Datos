# Balbasaur

Es un pokemon de la primera generación y mi pokemon favorito.

## Tabla principal

### Pokedex_id(PK)

001

### Nombre(UQ)

Balbasur

### Tipo1_id(FK)

Planta

### Tipo2_id(FK)

Veneno

### Habilidades(FK)

Espesura

---

## Tabla tipos

### tipos_id(PK)

1. Planta
1. Veneno
1. Tierra
1. Roca
1. Fuego
1. Agua
1. Bicho
1. Hielo
1. Volador

### tipo1_id (FK)

* tipos_id(FK)

### tipo2_id (FK)

* tipos_id(FK)

## Tabla habilidades

### habilidades (FK)

1. Espesura
    * Aumenta en 50% los ataques de tipo planta
1. Insomnio
    * Evita quedarse dormido
