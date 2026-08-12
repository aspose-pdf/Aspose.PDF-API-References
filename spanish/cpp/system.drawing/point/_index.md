---
title: "System::Drawing::Point class"
linktitle: "Point"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Point. Representa un par de coordenadas enteras X e Y de un punto en un plano bidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 1700
url: /es/cpp/system.drawing/point/
---
## Point class


Representa un par de coordenadas enteras X e Y de un punto en un plano bidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class Point
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Add](./add/)(const Point\&, const Size\&) | Añade los valores de ancho y alto del objeto [Size](../size/) especificado a los valores de coordenadas X e Y del objeto [Point](./) especificado correspondientemente. |
| static [Ceiling](./ceiling/)(const PointF\&) | Construye un objeto [Point](./) a partir del objeto [PointF](../pointf/) especificado redondeando los valores de coordenadas X e Y del objeto [PointF](../pointf/) al siguiente entero superior. |
| [Equals](./equals/)(const Point\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de coordenadas X e Y. |
| [get_IsEmpty](./get_isempty/)() const | Determina si ambos valores de coordenadas X e Y son iguales a 0. |
| [get_X](./get_x/)() const | Devuelve el valor de la coordenada X representado por el objeto actual. |
| [get_Y](./get_y/)() const | Devuelve el valor de la coordenada Y representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [getStdHash](./getstdhash/)() const | Devuelve un valor hash para el objeto actual. |
| [IsNull](./isnull/)() const | Siempre devuelve false. |
| [Offset](./offset/)(int, int) | Desplaza los valores de coordenadas X e Y representados por el objeto actual en los valores especificados. |
| [Offset](./offset/)(Point) | Desplaza las coordenadas X e Y representadas por el objeto actual en los valores de coordenadas X e Y representados por el objeto [Point](./) especificado correspondientemente. |
| [operator PointF](./operatorpointf/)() const | Construye una instancia del objeto [PointF](../pointf/) e inicializa sus valores de coordenadas X e Y con los del objeto [Point](./) actual. |
| [operator Size](./operatorsize/)() const | Construye una instancia del objeto [Size](../size/) e inicializa sus valores de ancho y alto con los valores de coordenadas X e Y representados por el objeto actual correspondientemente. |
| [Point](./point/)() | Construye un nuevo objeto [Point](./) e inicializa sus valores de coordenadas X e Y con 0. |
| [Point](./point/)(int, int) | Construye un nuevo objeto [Point](./) e lo inicializa con los valores especificados. |
| [Point](./point/)(const Size\&) | Construye un nuevo objeto [Point](./) e inicializa sus valores de coordenadas X e Y con los valores de ancho y alto del objeto [SizeF](../sizef/) especificado correspondientemente. |
| [Point](./point/)(int) | Construye un nuevo objeto [Point](./) e inicializa su valor de coordenada X con un valor formado por los 16 bits altos del entero de 32 bits especificado y su valor de coordenada Y con un valor formado por los 16 bits bajos del entero de 32 bits especificado. |
| static [Round](./round/)(const PointF\&) | Construye un objeto [Point](./) a partir del objeto [PointF](../pointf/) especificado, redondeando los valores de las coordenadas X y Y del objeto [PointF](../pointf/) al entero más cercano. |
| [set_X](./set_x/)(int) | Establece el valor de la coordenada X representada por el objeto actual. |
| [set_Y](./set_y/)(int) | Establece el valor de la coordenada Y representada por el objeto actual. |
| static [Subtract](./subtract/)(const Point\&, const Size\&) | Resta los valores de ancho y alto del objeto [Size](../size/) especificado de los valores de las coordenadas X y Y del objeto [Point](./) especificado, respectivamente. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de coordenadas X e Y representados por el objeto actual. |
| static [Truncate](./truncate/)(const PointF\&) | Construye un objeto [Point](./) a partir del objeto [PointF](../pointf/) especificado, truncando los valores de las coordenadas X y Y del objeto [PointF](../pointf/) al entero inferior más próximo. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [Point](./) cuyos valores de coordenadas X y Y son 0. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
