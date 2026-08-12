---
title: "Clase System::Drawing::Rectangle"
linktitle: "Rectángulo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Rectangle. Representa un área rectangular de una imagen definida por coordenadas enteras X e Y de su esquina superior izquierda y su ancho y alto. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 1900
url: /es/cpp/system.drawing/rectangle/
---
## Rectangle class


Representa un área rectangular de una imagen definida por coordenadas enteras X e Y de su esquina superior izquierda y su ancho y alto. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class Rectangle
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Ceiling](./ceiling/)(const RectangleF\&) | Construye un objeto [Rectangle](./) a partir del objeto [RectangleF](../rectanglef/) especificado redondeando los valores de ubicación y tamaño del objeto [RectangleF](../rectanglef/) al siguiente entero superior. |
| [Contains](./contains/)(int, int) const | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| [Contains](./contains/)(const Point\&) const | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| [Contains](./contains/)(const Rectangle\&) const | Determina si el rectángulo especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| [Equals](./equals/)(const Rectangle\&) const | Determina si los rectángulos representados por el objeto actual y el objeto especificado son idénticos. |
| static [FromLTRB](./fromltrb/)(int, int, int, int) | Construye un nuevo objeto [Rectangle](./) que representa un rectángulo con las ubicaciones de borde especificadas. |
| [get_Bottom](./get_bottom/)() const | Devuelve la coordenada y del borde inferior del rectángulo representado por el objeto actual. |
| [get_Height](./get_height/)() const | Devuelve la altura del rectángulo representado por el objeto actual. |
| [get_IsEmpty](./get_isempty/)() const | Determina si las coordenadas X e Y de la esquina superior izquierda del rectángulo representado por el objeto actual, así como su ancho y alto, tienen valores de 0. |
| [get_Left](./get_left/)() const | Devuelve la coordenada X del borde izquierdo del rectángulo representado por el objeto actual. |
| [get_Location](./get_location/)() const | Devuelve una instancia de la clase [Point](../point/) que especifica la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [get_Right](./get_right/)() const | Devuelve la coordenada X del borde derecho del rectángulo representado por el objeto actual. |
| [get_Size](./get_size/)() const | Devuelve una instancia de la clase [Size](../size/) que especifica el ancho y alto del rectángulo representado por el objeto actual. |
| [get_Top](./get_top/)() const | Devuelve la coordenada Y del borde superior del rectángulo representado por el objeto actual. |
| [get_Width](./get_width/)() const | Devuelve el ancho del rectángulo representado por el objeto actual. |
| [get_X](./get_x/)() const | Devuelve la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [get_Y](./get_y/)() const | Devuelve la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash del objeto actual. |
| [Inflate](./inflate/)(int, int) | Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados. |
| [Inflate](./inflate/)(const Size\&) | Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores de ancho y altura especificados por el objeto de tamaño indicado, respectivamente. |
| static [Inflate](./inflate/)(const Rectangle\&, int, int) | Aumenta el ancho y la altura del rectángulo representado por el objeto especificado, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados. |
| [Intersect](./intersect/)(const Rectangle\&) | Reemplaza el rectángulo representado por el objeto actual con el rectángulo que resulta de su intersección con el rectángulo representado por el objeto especificado. |
| static [Intersect](./intersect/)(const Rectangle\&, const Rectangle\&) | Devuelve un rectángulo que es el resultado de la intersección de los rectángulos especificados. |
| [IntersectsWith](./intersectswith/)(const Rectangle\&) | Determina si los rectángulos representados por el objeto actual y los objetos especificados se intersectan. |
| [Offset](./offset/)(const Point\&) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| [Offset](./offset/)(int, int) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| [operator RectangleF](./operatorrectanglef/)() const | Devuelve un objeto [RectangleF](../rectanglef/) que representa un rectángulo equivalente al rectángulo representado por el objeto actual. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Siempre devuelve true. |
| [operator==](./operator==/)(std::nullptr_t) const | Siempre devuelve false. |
| [Rectangle](./rectangle/)() | Construye una nueva instancia del objeto [Rectangle](./) que representa un rectángulo con coordenadas X e Y y valores de ancho y alto establecidos en 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Construye una nueva instancia del objeto [Rectangle](./) que representa un rectángulo con las coordenadas especificadas de su esquina superior izquierda y su ancho y alto. |
| [Rectangle](./rectangle/)(const Point\&, const Size\&) | Construye una nueva instancia del objeto [Rectangle](./) que representa un rectángulo con las coordenadas de su esquina superior izquierda especificadas como una instancia de la clase [Point](../point/) y su ancho y alto como una instancia de la clase [Size](../size/). |
| [Rectangle](./rectangle/)(const System::Windows::Forms::Screen::Rectangle_\&) | Construye una nueva instancia del objeto [Rectangle](./) que representa el rectángulo equivalente al especificado. |
| static [Round](./round/)(const RectangleF\&) | Construye un objeto [Rectangle](./) a partir del objeto [RectangleF](../rectanglef/) especificado redondeando los valores de ubicación y tamaño del objeto [RectangleF](../rectanglef/) al entero más cercano. |
| [set_Height](./set_height/)(int) | Establece la altura del rectángulo representado por el objeto actual. |
| [set_Location](./set_location/)(Point) | Establece la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [set_Size](./set_size/)(Size) | Establece el ancho y la altura del rectángulo representado por el objeto actual. |
| [set_Width](./set_width/)(int) | Establece el ancho del rectángulo representado por el objeto actual. |
| [set_X](./set_x/)(int) | Establece la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [set_Y](./set_y/)(int) | Establece la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena del objeto actual. |
| static [Truncate](./truncate/)(const RectangleF\&) | Construye un objeto [Rectangle](./) a partir del objeto [RectangleF](../rectanglef/) especificado truncando los valores de ubicación y tamaño del objeto [RectangleF](../rectanglef/) al siguiente entero inferior. |
| static [Union](./union/)(const Rectangle\&, const Rectangle\&) | Devuelve un rectángulo que es el resultado de la unión de los rectángulos especificados. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Un rectángulo vacío, es decir, un rectángulo cuyas valores de ubicación y tamaño son cero. |
## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
