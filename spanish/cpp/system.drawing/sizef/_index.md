---
title: "Clase System::Drawing::SizeF"
linktitle: "SizeF"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::SizeF class. Representa un par de valores de punto flotante de precisión simple que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use System::SmartPtr class para gestionar objetos de este tipo en C++."
type: docs
weight: 2300
url: /es/cpp/system.drawing/sizef/
---
## SizeF class


Representa un par de valores de punto flotante de precisión simple que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use [System::SmartPtr](../../system/smartptr/) class para gestionar objetos de este tipo.

```cpp
class SizeF
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Add](./add/)(const SizeF\&, const SizeF\&) | Devuelve un nuevo objeto [SizeF](./) que es la suma de los objetos [SizeF](./) especificados, es decir, cuyo valor de ancho es igual a la suma de los valores de ancho de los objetos especificados y cuyo valor de altura es igual a la suma de los valores de altura de los objetos especificados. |
| [Equals](./equals/)(const SizeF\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de ancho y altura. |
| [get_Height](./get_height/)() const | Devuelve el valor de altura representado por el objeto actual. |
| [get_IsEmpty](./get_isempty/)() const | Determina si los valores de ancho y altura son iguales a 0. |
| [get_Width](./get_width/)() const | Devuelve el valor de ancho representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [operator PointF](./operatorpointf/)() const | Convierte el objeto actual en una instancia del objeto [Point](../point/) inicializando sus coordenadas X e Y con los valores de ancho y altura del objeto actual, respectivamente. |
| [operator+=](./operator+=/)(const SizeF\&) | Añade los valores de ancho y altura del objeto [SizeF](./) especificado a los valores de ancho y altura del objeto [SizeF](./) actual, respectivamente. |
| [set_Height](./set_height/)(float) | Establece el valor de altura representado por el objeto actual. |
| [set_Width](./set_width/)(float) | Establece el valor de ancho representado por el objeto actual. |
| [SizeF](./sizef/)() | Construye un nuevo objeto [SizeF](./) e inicializa sus valores de ancho y altura con 0. |
| [SizeF](./sizef/)(const PointF\&) | Construye un nuevo objeto [SizeF](./) e inicializa sus valores de ancho y altura con los valores de las coordenadas X e Y del punto especificado, respectivamente. |
| [SizeF](./sizef/)(float, float) | Construye un nuevo objeto [SizeF](./) e lo inicializa con el valor especificado. |
| static [Subtract](./subtract/)(const SizeF\&, const SizeF\&) | Devuelve un nuevo objeto [SizeF](./) que es el resultado de la sustracción de **size2** de **size1**, es decir, cuyo valor de ancho es el resultado de restar el valor de ancho de **size2** del valor de ancho de **size1** y cuyo valor de altura es el resultado de restar el valor de altura de **size2** del valor de altura de **size1**. |
| [ToPointF](./topointf/)() const | Convierte el objeto actual en una instancia del objeto [Point](../point/) inicializando sus coordenadas X e Y con los valores de ancho y altura del objeto actual, respectivamente. |
| [ToSize](./tosize/)() const | Construye un objeto [Size](../size/) a partir del objeto [SizeF](./) actual truncando los valores de ancho y altura del objeto [SizeF](./) a los siguientes valores enteros inferiores. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de ancho y altura representados por el objeto actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [SizeF](./) cuyo ancho y altura son 0. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
