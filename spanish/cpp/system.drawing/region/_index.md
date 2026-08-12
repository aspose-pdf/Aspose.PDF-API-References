---
title: "Clase System::Drawing::Region"
linktitle: "Región"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Region. Representa el interior de una forma gráfica. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system.drawing/region/
---
## Region class


Representa el interior de una forma gráfica. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Region : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() const | Devuelve una copia del objeto actual. |
| [Complement](./complement/)(const RectangleF\&) | Reemplaza la región representada por el objeto actual con la porción de la región definida por el rectángulo especificado que no intersecta con esta región. |
| [Complement](./complement/)(const Rectangle\&) | Reemplaza la región representada por el objeto actual con la porción de la región definida por el rectángulo especificado que no intersecta con esta región. |
| [Complement](./complement/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Reemplaza la región representada por el objeto actual con la porción de la región definida por la ruta especificada que no intersecta con esta región. |
| [Complement](./complement/)(const SharedPtr\<Region\>\&) | Reemplaza la región representada por el objeto actual con la porción de la región especificada que no intersecta con esta región. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [Equals](./equals/)(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) | Determina si la región especificada es idéntica a la región representada por el objeto actual en la superficie de dibujo especificada. |
| [Exclude](./exclude/)(const RectangleF\&) | Reemplaza la región representada por el objeto actual con el resultado de la exclusión de la región definida por el rectángulo especificado. |
| [Exclude](./exclude/)(const Rectangle\&) | Reemplaza la región representada por el objeto actual con el resultado de la exclusión de la región definida por el rectángulo especificado. |
| [Exclude](./exclude/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la exclusión de la región definida por la ruta especificada. |
| [Exclude](./exclude/)(const SharedPtr\<Region\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la exclusión de la región especificada. |
| [GetBounds](./getbounds/)(const SharedPtr\<Graphics\>\&) const | Obtiene una estructura [RectangleF](../rectanglef/) que representa un rectángulo que delimita este [Region](./) en la superficie de dibujo de un objeto [Graphics](../graphics/). |
| [GetRegionData](./getregiondata/)() const | Devuelve un objeto RegionData que contiene los datos que definen la región representada por el objeto actual. |
| [GetRegionScans](./getregionscans/)(const SharedPtr\<Drawing2D::Matrix\>\&) const | Devuelve una matriz de estructuras [RectangleF](../rectanglef/) que aproximan esta [Region](./) después de aplicar la transformación de matriz especificada. |
| [Intersect](./intersect/)(const RectangleF\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y una región definida por el rectángulo especificado. |
| [Intersect](./intersect/)(const Rectangle\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y una región definida por el rectángulo especificado. |
| [Intersect](./intersect/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y una región definida por la ruta especificada. |
| [Intersect](./intersect/)(const SharedPtr\<Region\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la intersección de esta región y la región especificada. |
| [IsEmpty](./isempty/)(const SharedPtr\<Graphics\>\&) const | Determina si la región representada por el objeto actual tiene un interior vacío en la superficie de dibujo especificada. |
| [IsInfinite](./isinfinite/)(const SharedPtr\<Graphics\>\&) const | Determina si la región representada por el objeto actual tiene un interior infinito en la superficie de dibujo especificada. |
| [IsVisible](./isvisible/)(const Point\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual. |
| [IsVisible](./isvisible/)(const PointF\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual. |
| [IsVisible](./isvisible/)(const Rectangle\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual. |
| [IsVisible](./isvisible/)(const RectangleF\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual. |
| [IsVisible](./isvisible/)(const Point\&, const SharedPtr\<Graphics\>\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual usando los gráficos especificados. |
| [IsVisible](./isvisible/)(const PointF\&, const SharedPtr\<Graphics\>\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual usando los gráficos especificados. |
| [IsVisible](./isvisible/)(const Rectangle\&, const SharedPtr\<Graphics\>\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual usando los gráficos especificados. |
| [IsVisible](./isvisible/)(const RectangleF\&, const SharedPtr\<Graphics\>\&) | Determina si alguna parte del rectángulo especificado está contenida dentro de la región representada por el objeto actual usando los gráficos especificados. |
| [IsVisible](./isvisible/)(float, float) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual. |
| [IsVisible](./isvisible/)(float, float, const SharedPtr\<Graphics\>\&) const | Determina si el punto especificado está contenido dentro de la región representada por el objeto actual usando los gráficos especificados. |
| [MakeEmpty](./makeempty/)() | Inicializa el objeto actual con un interior vacío. |
| [MakeInfinite](./makeinfinite/)() | Inicializa este objeto de región con un interior infinito. |
| [Region](./region/)() | Construye una nueva instancia de la clase [Region](./). |
| [Region](./region/)(const RectangleF\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por el rectángulo especificado. |
| [Region](./region/)(const Rectangle\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por el rectángulo especificado. |
| [Region](./region/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por la ruta especificada. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const SharedPtr\<Drawing2D::RegionData\>\&) | Construye una nueva instancia de la clase [Region](./) que representa una región definida por el objeto RegionData especificado. |
| [Transform](./transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Transforma esta región mediante la matriz especificada. |
| [Transform](./transform/)(const SkMatrix\&) | Transforma esta región mediante la matriz especificada. |
| [Translate](./translate/)(int, int) | Mueve las coordenadas de la región en la cantidad especificada. |
| [Translate](./translate/)(float, float) | Mueve las coordenadas de la región en la cantidad especificada. |
| [Union](./union/)(const RectangleF\&) | Reemplaza la región representada por el objeto actual con el resultado de la operación de unión de esta región y una región definida por el rectángulo especificado. |
| [Union](./union/)(const Rectangle\&) | Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y una región definida por el rectángulo especificado. |
| [Union](./union/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y una región definida por la ruta especificada. |
| [Union](./union/)(const SharedPtr\<Region\>\&) | Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y la región especificada. |
| [Xor](./xor/)(const RectangleF\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no se intersectan. |
| [Xor](./xor/)(const Rectangle\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por el rectángulo especificado que no se intersectan. |
| [Xor](./xor/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región definida por la ruta especificada que no se intersectan. |
| [Xor](./xor/)(const SharedPtr\<Region\>\&) | Reemplaza la región representada por el objeto actual con las porciones de esta región y la región especificada que no se intersectan. |
| virtual [~Region](./~region/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
