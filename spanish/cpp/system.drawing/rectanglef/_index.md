---
title: "Clase System::Drawing::RectangleF"
linktitle: "RectangleF"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::RectangleF. Representa un área rectangular de una imagen definida por coordenadas X e Y de punto flotante de precisión simple de su esquina superior izquierda y su ancho y alto. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 2000
url: /es/cpp/system.drawing/rectanglef/
---
## RectangleF class


Representa un área rectangular de una imagen definida por coordenadas X e Y de precisión simple de punto flotante de su esquina superior izquierda y su ancho y alto. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class RectangleF
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Contains](./contains/)(float, float) | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| [Contains](./contains/)(const PointF\&) | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| [Contains](./contains/)(const RectangleF\&) | Determina si el rectángulo especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| [Equals](./equals/)(const RectangleF\&) const | Determina si los rectángulos representados por el objeto actual y el objeto especificado son idénticos. |
| static [FromLTRB](./fromltrb/)(float, float, float, float) | Construye un nuevo objeto [RectangleF](./) que representa un rectángulo con las ubicaciones de borde especificadas. |
| [get_Bottom](./get_bottom/)() const | Devuelve la coordenada y del borde inferior del rectángulo representado por el objeto actual. |
| [get_Height](./get_height/)() const | Devuelve la altura del rectángulo representado por el objeto actual. |
| [get_IsEmpty](./get_isempty/)() const | Determina si las coordenadas X e Y de la esquina superior izquierda del rectángulo representado por el objeto actual, así como su ancho y alto, tienen valores de 0. |
| [get_Left](./get_left/)() const | Devuelve la coordenada X del borde izquierdo del rectángulo representado por el objeto actual. |
| [get_Location](./get_location/)() const | Devuelve una instancia de la clase [PointF](../pointf/) que especifica la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [get_Right](./get_right/)() const | Devuelve la coordenada X del borde derecho del rectángulo representado por el objeto actual. |
| [get_Size](./get_size/)() const | Devuelve una instancia de la clase [SizeF](../sizef/) que especifica el ancho y la altura del rectángulo representado por el objeto actual. |
| [get_Top](./get_top/)() const | Devuelve la coordenada Y del borde superior del rectángulo representado por el objeto actual. |
| [get_Width](./get_width/)() const | Devuelve el ancho del rectángulo representado por el objeto actual. |
| [get_X](./get_x/)() const | Devuelve la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [get_Y](./get_y/)() const | Devuelve la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash del objeto actual. |
| [Inflate](./inflate/)(float, float) | Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados. |
| [Inflate](./inflate/)(const SizeF\&) | Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores de ancho y altura especificados por el objeto de tamaño indicado, respectivamente. |
| static [Inflate](./inflate/)(const RectangleF\&, float, float) | Aumenta el ancho y la altura del rectángulo representado por el objeto especificado, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados. |
| [Intersect](./intersect/)(const RectangleF\&) | Reemplaza el rectángulo representado por el objeto actual con el rectángulo que resulta de su intersección con el rectángulo representado por el objeto especificado. |
| static [Intersect](./intersect/)(const RectangleF\&, const RectangleF\&) | Devuelve un rectángulo que es el resultado de la intersección de los rectángulos especificados. |
| [IntersectsWith](./intersectswith/)(const RectangleF\&) | Determina si los rectángulos representados por el objeto actual y los objetos especificados se intersectan. |
| [Offset](./offset/)(const PointF\&) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| [Offset](./offset/)(float, float) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Siempre devuelve true. |
| [operator==](./operator==/)(std::nullptr_t) const | Siempre devuelve false. |
| [RectangleF](./rectanglef/)() | Construye una nueva instancia del objeto [RectangleF](./) que representa un rectángulo con coordenadas X e Y y valores de ancho y alto establecidos en 0. |
| [RectangleF](./rectanglef/)(float, float, float, float) | Construye una nueva instancia del objeto [RectangleF](./) que representa un rectángulo con las coordenadas especificadas de su esquina superior izquierda y su ancho y alto. |
| [RectangleF](./rectanglef/)(const PointF\&, const SizeF\&) | Construye una nueva instancia del objeto [RectangleF](./) que representa un rectángulo con las coordenadas de su esquina superior izquierda especificadas como una instancia de la clase [PointF](../pointf/) y su ancho y alto como una instancia de la clase [SizeF](../sizef/). |
| explicit [RectangleF](./rectanglef/)(const Rectangle\&) | Construye una nueva instancia del objeto [RectangleF](./) que representa el rectángulo equivalente al especificado. |
| [set_Height](./set_height/)(float) | Establece la altura del rectángulo representado por el objeto actual. |
| [set_Location](./set_location/)(PointF) | Establece la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [set_Size](./set_size/)(SizeF) | Establece el ancho y la altura del rectángulo representado por el objeto actual. |
| [set_Width](./set_width/)(float) | Establece el ancho del rectángulo representado por el objeto actual. |
| [set_X](./set_x/)(float) | Establece la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [set_Y](./set_y/)(float) | Establece la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del objeto actual. |
| static [Union](./union/)(const RectangleF\&, const RectangleF\&) | Devuelve un rectángulo que es el resultado de la unión de los rectángulos especificados. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Un rectángulo vacío, es decir, un rectángulo cuyas valores de ubicación y tamaño son cero. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
