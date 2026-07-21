---
title: "Clase System::Drawing::PointF"
linktitle: "PointF"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::PointF. Representa un par de coordenadas X e Y de punto de coma flotante de precisión simple en un plano bidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 1800
url: /es/cpp/system.drawing/pointf/
---
## PointF class


Representa un par de coordenadas X e Y de punto de coma flotante de precisión simple en un plano bidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class PointF
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Add](./add/)(const PointF\&, const SizeF\&) | Añade los valores de ancho y alto del objeto [SizeF](../sizef/) especificado a los valores de coordenadas X e Y del objeto [PointF](./) especificado correspondientemente. |
| static [Add](./add/)(const PointF\&, const Size\&) | Añade los valores de ancho y alto del objeto [Size](../size/) especificado a los valores de coordenadas X e Y del objeto [PointF](./) especificado correspondientemente. |
| [Equals](./equals/)(const PointF\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de coordenadas X e Y. |
| [get_IsEmpty](./get_isempty/)() const | Determina si ambos valores de coordenadas X e Y son iguales a 0. |
| [get_X](./get_x/)() const | Devuelve el valor de la coordenada X representado por el objeto actual. |
| [get_Y](./get_y/)() const | Devuelve el valor de la coordenada Y representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [IsNull](./isnull/)() const | Siempre devuelve false. |
| explicit [operator bool](./operatorbool/)() | Siempre devuelve true. |
| [PointF](./pointf/)() | Construye un nuevo objeto [PointF](./) y inicializa sus valores de coordenadas X e Y con 0. |
| [PointF](./pointf/)(float, float) | Construye un nuevo objeto [PointF](./) y lo inicializa con los valores especificados. |
| [PointF](./pointf/)(const SizeF\&) | Construye un nuevo objeto [PointF](./) e inicializa sus valores de coordenadas X e Y con los valores de ancho y alto del objeto [SizeF](../sizef/) especificado, respectivamente. |
| [set_X](./set_x/)(float) | Establece el valor de la coordenada X representada por el objeto actual. |
| [set_Y](./set_y/)(float) | Establece el valor de la coordenada Y representada por el objeto actual. |
| static [Subtract](./subtract/)(const PointF\&, const SizeF\&) | Resta los valores de ancho y alto del objeto [SizeF](../sizef/) especificado de los valores de coordenadas X e Y del objeto [PointF](./) especificado, respectivamente. |
| static [Subtract](./subtract/)(const PointF\&, const Size\&) | Resta los valores de ancho y alto del objeto [Size](../size/) especificado de los valores de coordenadas X e Y del objeto [PointF](./) especificado, respectivamente. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de coordenadas X e Y representados por el objeto actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [PointF](./) cuyos valores de coordenadas X e Y son 0. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
