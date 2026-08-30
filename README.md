# Credit Card Utilities

Este repositorio contiene dos scripts de Python para trabajar con números de tarjeta de crédito. Estas utilidades permiten **generar** números de tarjeta de crédito válidos y aleatorios, así como **validar** números de tarjeta de crédito existentes siguiendo los estándares del sector.

## Files

- `credit_card_generator.py`Features
: Genera números de tarjeta de crédito válidos y aleatorios para varios tipos de tarjeta. (Visa, MasterCard, American Express, Discover).

- `credit_card_validator.py`: Valida números de tarjeta de crédito comprobando el tipo y la longitud de la tarjeta, y utilizando el algoritmo de Luhn para verificar la estructura del número..

## Características

### `credit_card_generator.py`
- Permite al usuario especificar un tipo de tarjeta para la generación..
- Genera un número de tarjeta de crédito con una estructura válida y un dígito de control basado en el algoritmo de Luhn.
- Opcionalmente, formatea el número de tarjeta generado en grupos para facilitar su lectura.

### `credit_card_validator.py`
- Acepta la entrada de un número de tarjeta de crédito para su validación.
- Identifica el tipo de tarjeta y verifica la longitud del número.
- Verifica la validez del número mediante el algoritmo de Luhn.

## Cómo utilizarlo


git clone https://github.com/Angel-9574/Creacion_Validacion_tarjeta

### Requisitos
Asegúrate de tener Python 3 instalada.

Correr Para generar un número de tarjeta de crédito aleatorio válido:
```bash
python credit_card_generator.py
```
Sigue las indicaciones para seleccionar un tipo de tarjeta y generar un número..

### Run `credit_card_validator.py`
Para validar un número de tarjeta de crédito, ejecute:
```bash
python credit_card_validator.py
```
Ingrese un número de tarjeta cuando se le solicite para verificar si es válido.
