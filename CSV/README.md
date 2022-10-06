# Filmy

Datový formát CSV pro ukládání filmů, žánrů, zemí...

## Specifikace

Kódováno v UTF-8

## Značky

### `<movie>`
- id MEDIUMINT
- name VARCHAR(45)
- year YEAR

### `<genre>`
- id SMALLINT
- name VARCHAR(45)

### `<country>`
- id SMALLINT
- name VARCHAR(45)