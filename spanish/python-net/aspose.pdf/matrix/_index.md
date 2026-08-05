---
title: "Matrix"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "La clase representa una matriz de transformación."
type: docs
weight: 900
url: /es/python-net/aspose.pdf/matrix/
---

## Matrix class

La clase representa una matriz de transformación.

El tipo Matrix expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Matrix() | Constructor<br/>            crea una matriz estándar 1 a 1:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Inicializa una nueva instancia de la clase Matrix |
| Matrix(matrix_array) | Inicializa una nueva instancia de la clase Matrix |
| Matrix(matrix) | Inicializa una nueva instancia de la clase Matrix |
| Matrix(a, b, c, d, e, f) | Inicializa una nueva instancia de la clase Matrix |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| data | Obtiene los datos de Matrix como una matriz. |
| a | Un miembro de la matriz de transformación. |
| b | Miembro B de la matriz de transformación. |
| c | Miembro C de la matriz de transformación. |
| d | Miembro D de la matriz de transformación. |
| e | Miembro E de la matriz de transformación. |
| f | Miembro F de la matriz de transformación. |
| elementos | Elementos de la matriz. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| rotation(alpha) | Crea una matriz para el ángulo de rotación dado. |
| rotation(rotation) | Crea una matriz para el ángulo de rotación dado. |
| transform(p) | Transforma el punto usando esta matriz. |
| transform(rect) | Transforma el rectángulo.<br/>            Si el ángulo no es 90 * N grados, entonces se devuelve el rectángulo delimitador. |
| skew(alpha, beta) | Crea una matriz para el ángulo de rotación dado. |
| get_angle(rotation) | Traduce la rotación a ángulo (grados) |
| multiply(other) | Multiplica la matriz por otra matriz. |
| add(other) | Añade la matriz a otra matriz. |
| reverse() | Calcula la matriz inversa. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

