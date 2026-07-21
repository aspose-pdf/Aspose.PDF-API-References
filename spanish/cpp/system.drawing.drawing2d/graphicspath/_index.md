---
title: "System::Drawing::Drawing2D::GraphicsPath class"
linktitle: "GraphicsPath"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Drawing2D::GraphicsPath class. Representa un conjunto de líneas y curvas conectadas. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath class


Representa un conjunto de líneas y curvas conectadas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class GraphicsPath : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddArc](./addarc/)(float, float, float, float, float, float) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| [AddArc](./addarc/)(int, int, int, int, float, float) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| [AddArc](./addarc/)(const RectangleF\&, float, float) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| [AddArc](./addarc/)(const Rectangle\&, float, float) | Agrega el arco elíptico especificado a la ruta representada por el objeto actual. |
| [AddBezier](./addbezier/)(const Point\&, const Point\&, const Point\&, const Point\&) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| [AddBezier](./addbezier/)(const PointF\&, const PointF\&, const PointF\&, const PointF\&) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| [AddBezier](./addbezier/)(float, float, float, float, float, float, float, float) | Agrega la curva cúbica de Bézier especificada a la ruta representada por el objeto actual. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<Point\>\&) | Agrega una secuencia de curvas cúbicas de Bézier conectadas a la figura actual. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<PointF\>\&) | Agrega una secuencia de curvas cúbicas de Bézier conectadas a la figura actual. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<PointF\>\&, float) | Agrega la curva cerrada especificada a la ruta representada por el objeto actual. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<Point\>\&, float) | Agrega la curva cerrada especificada a la ruta representada por el objeto actual. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, float) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, float) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, int, int, float) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, int, int, float) | Agrega la curva especificada a la ruta representada por el objeto actual. |
| [AddEllipse](./addellipse/)(float, float, float, float) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| [AddEllipse](./addellipse/)(int, int, int, int) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| [AddEllipse](./addellipse/)(const RectangleF\&) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| [AddEllipse](./addellipse/)(const Rectangle\&) | Agrega la elipse especificada a la ruta representada por el objeto actual. |
| [AddLine](./addline/)(const Point\&, const Point\&) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| [AddLine](./addline/)(const PointF\&, const PointF\&) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| [AddLine](./addline/)(int, int, int, int) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| [AddLine](./addline/)(float, float, float, float) | Agrega la línea especificada a la ruta representada por el objeto actual. |
| [AddLines](./addlines/)(const ArrayPtr\<PointF\>\&) | Agrega la serie especificada de segmentos de línea conectados a la ruta representada por el objeto actual. |
| [AddLines](./addlines/)(const ArrayPtr\<Point\>\&) | Agrega la serie especificada de segmentos de línea conectados a la ruta representada por el objeto actual. |
| [AddPath](./addpath/)(const SharedPtr\<GraphicsPath\>\&, bool) | Agrega la ruta especificada a la ruta representada por el objeto actual. |
| [AddPie](./addpie/)(float, float, float, float, float, float) | Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual. |
| [AddPie](./addpie/)(int, int, int, int, float, float) | Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual. |
| [AddPie](./addpie/)(const Rectangle\&, float, float) | Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<PointF\>\&) | Agrega el polígono especificado a la ruta representada por el objeto actual. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<Point\>\&) | Agrega el polígono especificado a la ruta representada por el objeto actual. |
| [AddRectangle](./addrectangle/)(const Rectangle\&) | Agrega el rectángulo especificado a la ruta representada por el objeto actual. |
| [AddRectangle](./addrectangle/)(const RectangleF\&) | Agrega el rectángulo especificado a la ruta representada por el objeto actual. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<Rectangle\>\&) | Agrega la serie especificada de rectángulos a la ruta representada por el objeto actual. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<RectangleF\>\&) | Agrega la serie especificada de rectángulos a la ruta representada por el objeto actual. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) | Agrega una cadena de texto a la ruta representada por el objeto actual. |
| virtual [Clone](./clone/)() | Crea una copia del objeto actual. |
| [CloseAllFigures](./closeallfigures/)() | Cierra todas las figuras abiertas y comienza una nueva. |
| [CloseFigure](./closefigure/)() | Cierra la figura actual y comienza una nueva. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [Flatten](./flatten/)() | Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se utiliza el valor de planitud de 0.25. |
| [Flatten](./flatten/)(const MatrixPtr\&) | Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se utiliza el valor de planitud de 0.25. |
| [Flatten](./flatten/)(const MatrixPtr\&, float) | Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. |
| [get_FillMode](./get_fillmode/)() | Devuelve el modo de relleno del objeto actual. |
| [get_PathData](./get_pathdata/)() | Devuelve un objeto [PathData](../pathdata/) que contiene los puntos que forman una ruta representada por el objeto actual y sus tipos. |
| [get_PathPoints](./get_pathpoints/)() const | Devuelve una matriz que contiene los puntos que forman una ruta representada por el objeto actual. |
| [get_PathTypes](./get_pathtypes/)() const | Devuelve una matriz que contiene valores que indican los tipos de los puntos que forman una ruta representada por el objeto actual. |
| [get_PointCount](./get_pointcount/)() const | Devuelve el número de puntos en la ruta representada por el objeto actual. |
| [GetBounds](./getbounds/)(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const | Devuelve un objeto [RectangleF](../../system.drawing/rectanglef/) que representa un rectángulo que delimita la ruta representada por el objeto actual cuando se transforma con la matriz especificada. |
| [GetFigureFlags](./getfigureflags/)() | Devuelve un valor que es una combinación bit a bit de los valores Detail::FigureType que indica qué tipos de figuras están contenidas dentro de la ruta representada por el objeto actual. |
| [GetLastPoint](./getlastpoint/)() const | Devuelve un objeto [PointF](../../system.drawing/pointf/) que representa el último punto de la ruta. |
| [GraphicsPath](./graphicspath/)(FillMode) | Construye una nueva instancia de la clase [GraphicsPath](./) con el modo de relleno especificado. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Construye una nueva instancia del objeto [GraphicsPath](./) que representa la ruta especificada. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Construye una nueva instancia del objeto [GraphicsPath](./) que representa la ruta especificada. |
| [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| [IsOutlineVisible](./isoutlinevisible/)(const PointF\&, const SharedPtr\<Pen\>\&) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este [GraphicsPath](./) cuando se dibuja con el [Pen](../../system.drawing/pen/) especificado. NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(const PointF\&) | Determina si el punto especificado está contenido dentro de la ruta representada por el objeto actual. |
| [IsVisible](./isvisible/)(float, float) | Determina si el punto especificado está contenido dentro de la ruta representada por el objeto actual. |
| [Reset](./reset/)() | Vacía la ruta eliminando todos sus puntos. |
| [Reverse](./reverse/)() | Invierte el orden de los puntos en la matriz PathPoints de este [GraphicsPath](./). |
| [set_FillMode](./set_fillmode/)(FillMode) | Establece el modo de relleno del objeto actual. |
| [SetMarkers](./setmarkers/)() | NO IMPLEMENTADO. |
| [StartFigure](./startfigure/)() | Inicia una nueva figura. |
| [Transform](./transform/)(const MatrixPtr\&) | Transforma la ruta representada por el objeto actual aplicando la matriz de transformación especificada. |
| [Transform](./transform/)(const SkMatrix\&) |  |
| [Widen](./widen/)(const SharedPtr\<Pen\>\&) | Reemplaza esta ruta con un contorno alrededor de la ruta original. |
| [~GraphicsPath](./~graphicspath/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
