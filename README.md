# Práctica 6: Recursión y Complejidad. 📌

Nombre:

NumCuenta:

En esta práctica se llevarán a cabo la implementación de algiritmos iterativos y recursivos, así como el conteo de operaciones requeridas para cada una de las versiones. 

## Autores 😊
* **Salvador López Mendoza** - *Titular* - [Correo](slm@ciencias.unam.mx)
* **Gerardo Emiliano Figueroa Sandoval** - *Teoría* - [Emiliano-Fs](https://github.com/Emiliano-FS)
* **Ramsés Antonio López Soto** - *Laboratorio* - [ramseslopez](https://github.com/ramseslopez)
  
## Objetivos 🚀

- Entender las diferencias entre los algoritmos iterativos y los recursivos.
- Hacer el análisis de la complejidad en tiempo y espacio de un algoritmo (recursivo o iterativo).
- Contar el número de pasos requeridos para un algortimo iterativo y recursivo. 

### Pre-requisitos 📋

- Sistema Operativo Linux (Ubuntu, Debian, Fedora, etc.)
- Git versión 2.43.0
- Java versión 21.0.7
- Perfil de GitHub
- Maven 3.8.7

### Instalación 🔧

- Git

Para instalar la versión más reciente de Git:

```bash
sudo apt-get install git

```
Una vez finaliado, verifica la versión instalada.

```
git -v
```

- Java
  
Instala Java con el siguiente comando:

```
sudo apt-get install openjdk-21-jre
```

Al finalizar, verifica la versión instalada.

```
java --version
```
y también del compilador:

```
javac --version
``` 

- Maven

Para instalar Maven, utliliza el siguiente comando:

```
sudo apt-get install maven
```

Al finalizar, verifica la versión instalada:

```
mvn -v
```

## Recursos 📖

Puedes encontrar más información de los recursos a utilizar en:

- [Recursión](https://www.geeksforgeeks.org/introduction-to-recursion-2/)
- [Iteración vs Recursión](https://www.geeksforgeeks.org/dsa/difference-between-recursion-and-iteration/)
- [Complejidad](https://drive.google.com/file/d/13c54HXCGR7e6CY6pUj8YYNxSQILOd-9Y/view?usp=sharing)

## Ejercicios ⌨️

Realiza los siguientes ejercicios:

### Manejo de cadenas y números.

Tomando como base la solución de la práctica 2 donde implementaste los siguientes métodos:

- suma
- división
- potencia
- esPerfecto
- sumarDigitos
- reversa 
- esPalindromo
- ocurrenciasDe
- decimalABinario

Deberás de realizar una versión recursivo de cada uno de los métodos anteriores y deberás de contar el número de operaciones totales de cada uno de los métodos en sus dos versiones. 

El número de pasos deberán de verse en pantalla al momento de invocar los métodos.

Las pruebas unitarias deben de actualizarse para que tomen en cuenta las versiones recursivas.

### Análisis de Complejidad

Debes de elegir al menos cuatro métodos y hacer un análiis de su complejidad en sus dos versiones y debes agregarlo al directorio raíz en un formato PDF.

Para compilar, debes usar el siguiente comando:

```
mvn compile
```

Para ejecutar todas las prubas unitarias:

```
mvn test
```

Y para ejecutar el programa principal:

```
mvn install
----
java -jar target/practica6.jar
```

## Intrucciones

* La práctica se entrega de forma individual.
* Debes de clonar el este repositorio y agregar tu nombre en la parte de `Nombre: ` y seguido de tu número de cuenta en `NumCuenta: ` en el `README`.
* El código debe ser legible y el nombre varialbes y métodos debe ser adecuado.
* Como entrega en el Classroom deberás de colocar el link **HTTPS** de tu repositorio.
* Sube la solución de la práctica antes de las 23:59 del día de mañana.
* Ningún tipo de copia y/o plagio será tolerado.

## Licencia 📄

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para más detalles.
