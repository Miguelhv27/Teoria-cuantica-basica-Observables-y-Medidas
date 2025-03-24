# Teoría cuántica básica, Observables y Medidas

Este proyecto explora la evolución de sistemas cuánticos utilizando matrices unitarias y el concepto de estados de superposición. A lo largo de los ejercicios, hemos verificado la unitariedad de ciertas matrices, analizado la evolución de estados cuánticos a través de pasos temporales y evaluado la separabilidad de estados en sistemas multipartícula. Implementamos estos cálculos utilizando Python y NumPy, aplicando operaciones matriciales como productos y potencias de matrices. Finalmente, estos conceptos se extienden a registros cuánticos, fundamentales para la computación cuántica.

### Requisitos previos.  

Para que el proyecto duncione correctamente, en un jupyter notebook en este caso usando python, tenemos que tener instalado:

1. Python
2. Jupyter Notebook
3. Bibliotecas necesarias. Por si no las tienes instaladas ejecuta el siguiente comando:

```
%pip install numpy matplotlib
```

## Contenido:

Este proyecto simula un sistema cuántico en un Jupyter Notebook utilizando el lenguaje Python, especificamente para modelar una particula confinada en posiciones discretas dentro de una linea. A lo largo del desarrollo, hemos implementado los conceptos clave de la seccion 4.1 y se resolvieron los desafios del capitulo 4, abordando los siguientes puntos:

1. Simulacion de un sistema cuantico este nos permitio definir el numero de posiciones y asignar emplitudes a un vector ket de estado.
2. Cálculo de probabilidades, tanto de encontrar la partícula en una posición específica como de transición entre dos estados dados.
3. Implementación de operaciones cuánticas, como el cálculo de amplitud de transición entre dos estados y la aplicación de observables.
4. Verificación de matrices hermitianas, junto con el cálculo de media y varianza del observable en un estado determinado.
5. Cálculo de valores propios de un observable y la probabilidad de transición hacia sus vectores propios.
6. Evolución temporal del sistema, utilizando una serie de matrices unitarias para calcular el estado final desde un estado inicial.

Además, el proyecto incluye la resolución de los problemas 4.3.1, 4.3.2, 4.4.1 y 4.4.2, modelados dentro de la librería implementada. Finalmente, se ha desarrollado una discusión sobre los ejercicios 4.5.2 y 4.5.3, la cual se encuentra en el mismo Jupyter Notebook. 

## Instrucciones de uso. 

Para ejecutar este proyecto en un sistema local, sigue los siguientes pasos:

1. Clonar el repositorio desde GitHub en tu maquina local.
2. Abrir Jupyter Notebook y abrir el archivo principal del proyecto.
3. Ejecutar las celdas en orden, asegurandose que todas las dependencias hayan sido instaladas previamente. 

## Autor

* **Miguel Ángel Hernández Vargas**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Agradecimientos. 

* Especialmente a las herramientas como Visual Studio Code, NumPy y Matplotlib, ya que facilitaron la implementacion y visualizacion de los calculos que realizamos a lo largo del proyecto.
* Ademas a los recursos educativos que me ayudaron a comprender y aplicar los conceptos necesarios para realizar este proyecto. 
