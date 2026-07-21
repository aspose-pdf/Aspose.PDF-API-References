---
title: "Clase System::Drawing::Size"
linktitle: "Size"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Size. Representa un par de valores enteros que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 2200
url: /es/cpp/system.drawing/size/
---
## Size class


Representa un par de valores enteros que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class Size
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Add](./add/)(const Size\&, const Size\&) | Devuelve un nuevo objeto [Size](./) que es la suma del objeto [Size](./) especificado, es decir, cuyo valor de ancho es igual a la suma de los valores de ancho de los objetos especificados y cuyo valor de altura es igual a la suma de los valores de altura de los objetos especificados. |
| static [Ceiling](./ceiling/)(const SizeF\&) | Construye un objeto [Size](./) a partir del objeto [SizeF](../sizef/) especificado redondeando los valores de ancho y altura del objeto [SizeF](../sizef/) al siguiente entero superior. |
| [Equals](./equals/)(const Size\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de ancho y altura. |
| [get_Height](./get_height/)() const | Devuelve el valor de altura representado por el objeto actual. |
| [get_IsEmpty](./get_isempty/)() const | Determina si los valores de ancho y altura son iguales a 0. |
| [get_Width](./get_width/)() const | Devuelve el valor de ancho representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [operator Point](./operatorpoint/)() const | Construye una instancia del objeto [Point](../point/) e inicializa sus coordenadas X e Y con los valores de ancho y altura del objeto actual, respectivamente. |
| [operator SizeF](./operatorsizef/)() const | Construye una instancia del objeto [SizeF](../sizef/) y lo inicializa con los valores de ancho y altura del objeto [Size](./) actual. |
| static [Round](./round/)(const SizeF\&) | Construye un objeto [Size](./) a partir del objeto [SizeF](../sizef/) especificado redondeando los valores de ancho y altura del objeto [SizeF](../sizef/) al entero más cercano. |
| [set_Height](./set_height/)(int) | Establece el valor de altura representado por el objeto actual. |
| [set_Width](./set_width/)(int) | Establece el valor de ancho representado por el objeto actual. |
| [Size](./size/)() | Construye un nuevo objeto [Size](./) e inicializa sus valores de ancho y altura con 0. |
| [Size](./size/)(const Point\&) | Construye un nuevo objeto [Size](./) e inicializa sus valores de ancho y altura con los valores de las coordenadas X e Y del punto especificado, respectivamente. |
| [Size](./size/)(int, int) | Construye un nuevo objeto [Size](./) y lo inicializa con el valor especificado. |
| static [Subtract](./subtract/)(const Size\&, const Size\&) | Devuelve un nuevo objeto [Size](./) que es el resultado de la sustracción de **size2** de **size1**, es decir, cuyo valor de ancho es el resultado de la sustracción del valor de ancho de **size2's** del valor de ancho de **size1's** y cuyo valor de alto es el resultado de la sustracción del valor de alto de **size2's** del valor de alto de **size1's**. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de ancho y altura representados por el objeto actual. |
| static [Truncate](./truncate/)(const SizeF\&) | Construye un objeto [Size](./) a partir del objeto [SizeF](../sizef/) especificado truncando los valores de ancho y alto del objeto [SizeF](../sizef/) al siguiente entero inferior. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [Size](./) cuyos valores de ancho y alto son 0. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
