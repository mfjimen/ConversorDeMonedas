# Convertidor de Divisas

Este es un programa en Java que permite convertir montos entre diferentes divisas utilizando la API de ExchangeRate. El programa es interactivo y permite al usuario seleccionar la conversión deseada.

## Características

- Conversión entre las siguientes divisas:
  - USD a ARS (Peso Argentino)
  - ARS a USD
  - USD a BRL (Real Brasileño)
  - BRL a USD
  - USD a COP (Peso Colombiano)
  - COP a USD
- Utiliza la API de ExchangeRate para obtener tasas de conversión actualizadas.
- Interfaz de línea de comandos simple e intuitiva.

## Requisitos

- Java 11 o superior.
- Dependencia de Gson para el manejo de JSON. Puedes agregar Gson a tu proyecto mediante Maven o descargando el JAR directamente.

## Instalación

1. Clona este repositorio o descarga los archivos.
2. Asegúrate de tener Java instalado en tu máquina.
3. Si usas Maven, agrega la siguiente dependencia en tu archivo `pom.xml`:

   ```xml
   <dependency>
       <groupId>com.google.code.gson</groupId>
       <artifactId>gson</artifactId>
       <version>2.8.8</version>
   </dependency>

   Compila y ejecuta el programa.
Uso
Ejecuta el programa.
Selecciona el tipo de conversión que deseas realizar ingresando el número correspondiente.
Ingresa el monto que deseas convertir.
El programa mostrará el monto convertido en la divisa seleccionada.
Ejemplo de Uso

 
Sea bienvenido al convertidor de divisas =)
Elija el número de su selección a convertir:
1)         "USD a ARS"
2)         "ARS a USD"
3)         "USD a BRL"
4)         "BRL a USD"
5)         "USD a COP"
6)         "COP a USD"


