---
title: System::Drawing::Drawing2D::GraphicsPath class
linktitle: GraphicsPath
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::GraphicsPath class. Represents a set of connected lines and curves. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath class


Represents a set of connected lines and curves. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GraphicsPath : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddArc](./addarc/)(float, float, float, float, float, float) | Adds the specified elliptical arc to the path represented by the current object. |
| [AddArc](./addarc/)(int, int, int, int, float, float) | Adds the specified elliptical arc to the path represented by the current object. |
| [AddArc](./addarc/)(const RectangleF\&, float, float) | Adds the specified elliptical arc to the path represented by the current object. |
| [AddArc](./addarc/)(const Rectangle\&, float, float) | Adds the specified elliptical arc to the path represented by the current object. |
| [AddBezier](./addbezier/)(const Point\&, const Point\&, const Point\&, const Point\&) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| [AddBezier](./addbezier/)(const PointF\&, const PointF\&, const PointF\&, const PointF\&) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| [AddBezier](./addbezier/)(float, float, float, float, float, float, float, float) | Adds the specified cubic Bezier curve to the path represented by the current object. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<Point\>\&) | Adds a sequence of connected cubic Bezier curves to the current figure. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<PointF\>\&) | Adds a sequence of connected cubic Bezier curves to the current figure. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<PointF\>\&, float) | Adds the specified closed curve to the path represented by the current object. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<Point\>\&, float) | Adds the specified closed curve to the path represented by the current object. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, float) | Adds the specified curve to the path represented by the current object. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, float) | Adds the specified curve to the path represented by the current object. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, int, int, float) | Adds the specified curve to the path represented by the current object. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, int, int, float) | Adds the specified curve to the path represented by the current object. |
| [AddEllipse](./addellipse/)(float, float, float, float) | Adds the specified ellipse to the path represented by the current object. |
| [AddEllipse](./addellipse/)(int, int, int, int) | Adds the specified ellipse to the path represented by the current object. |
| [AddEllipse](./addellipse/)(const RectangleF\&) | Adds the specified ellipse to the path represented by the current object. |
| [AddEllipse](./addellipse/)(const Rectangle\&) | Adds the specified ellipse to the path represented by the current object. |
| [AddLine](./addline/)(const Point\&, const Point\&) | Adds the specified line to the path represented by the current object. |
| [AddLine](./addline/)(const PointF\&, const PointF\&) | Adds the specified line to the path represented by the current object. |
| [AddLine](./addline/)(int, int, int, int) | Adds the specified line to the path represented by the current object. |
| [AddLine](./addline/)(float, float, float, float) | Adds the specified line to the path represented by the current object. |
| [AddLines](./addlines/)(const ArrayPtr\<PointF\>\&) | Adds the specified series of connected line segments to the path represented by the current object. |
| [AddLines](./addlines/)(const ArrayPtr\<Point\>\&) | Adds the specified series of connected line segments to the path represented by the current object. |
| [AddPath](./addpath/)(const SharedPtr\<GraphicsPath\>\&, bool) | Adds the specified path to the path represented by the current object. |
| [AddPie](./addpie/)(float, float, float, float, float, float) | Adds the specified outline of the pie shape to the path represented by the current object. |
| [AddPie](./addpie/)(int, int, int, int, float, float) | Adds the specified outline of the pie shape to the path represented by the current object. |
| [AddPie](./addpie/)(const Rectangle\&, float, float) | Adds the specified outline of the pie shape to the path represented by the current object. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<PointF\>\&) | Adds the specified polygon to the path represented by the current object. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<Point\>\&) | Adds the specified polygon to the path represented by the current object. |
| [AddRectangle](./addrectangle/)(const Rectangle\&) | Adds the specified rectangle to the path represented by the current object. |
| [AddRectangle](./addrectangle/)(const RectangleF\&) | Adds the specified rectangle to the path represented by the current object. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<Rectangle\>\&) | Adds the specified series of rectangles to the path represented by the current object. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<RectangleF\>\&) | Adds the specified series of rectangles to the path represented by the current object. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) | Adds a string of text to the path represented by the current object. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) | Adds a string of text to the path represented by the current object. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) | Adds a string of text to the path represented by the current object. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) | Adds a string of text to the path represented by the current object. |
| virtual [Clone](./clone/)() | Creates a copy of the current object. |
| [CloseAllFigures](./closeallfigures/)() | Closes all open figures and starts a new one. |
| [CloseFigure](./closefigure/)() | Closes the current figure and starts a new one. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [Flatten](./flatten/)() | Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used. |
| [Flatten](./flatten/)(const MatrixPtr\&) | Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used. |
| [Flatten](./flatten/)(const MatrixPtr\&, float) | Flattens each curve in the path by converting them into a series of connected lines. |
| [get_FillMode](./get_fillmode/)() | Returns the fill mode of the current object. |
| [get_PathData](./get_pathdata/)() | Returns a [PathData](../pathdata/) object containing the points that make up a path represented by the current object and their types. |
| [get_PathPoints](./get_pathpoints/)() const | Returns an array that contains points that make up a path represented by the current object. |
| [get_PathTypes](./get_pathtypes/)() const | Returns an array that contains values that indicate the types of the points that make up a path represented by the current object. |
| [get_PointCount](./get_pointcount/)() const | Returns the number of points in the path represented by the current object. |
| [GetBounds](./getbounds/)(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const | Returns a [RectangleF](../../system.drawing/rectanglef/) object that represents a rectangle that bounds the path represented by the current object when it is transformed with the specified matrix. |
| [GetFigureFlags](./getfigureflags/)() | Returns a value which is a bitwise combination of Detail::FigureType values that indicates what types of figures are contained within the path represented by the current object. |
| [GetLastPoint](./getlastpoint/)() const | Returns a [PointF](../../system.drawing/pointf/) object representing the last point in the path. |
| [GraphicsPath](./graphicspath/)(FillMode) | Constructs a new instance of [GraphicsPath](./) class with the specified fill mode. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Constructs a new instance of [GraphicsPath](./) object that represents the specified path. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Constructs a new instance of [GraphicsPath](./) object that represents the specified path. |
| [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| [IsOutlineVisible](./isoutlinevisible/)(const PointF\&, const SharedPtr\<Pen\>\&) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](./) when drawn with the specified [Pen](../../system.drawing/pen/). NOT EMPLEMENTED. |
| [IsVisible](./isvisible/)(const PointF\&) | Determines if the specified point is contained within the path represented by the current object. |
| [IsVisible](./isvisible/)(float, float) | Determines if the specified point is contained within the path represented by the current object. |
| [Reset](./reset/)() | Empties the path by removing all points from it. |
| [Reverse](./reverse/)() | Reverses the order of points in the PathPoints array of this [GraphicsPath](./). |
| [set_FillMode](./set_fillmode/)(FillMode) | Sets the fill mode of the current object. |
| [SetMarkers](./setmarkers/)() | NOT IMPLEMENTED. |
| [StartFigure](./startfigure/)() | Starts a new figure. |
| [Transform](./transform/)(const MatrixPtr\&) | Transforms the path represented by the current object by applying the specified transform matrix to it. |
| [Transform](./transform/)(const SkMatrix\&) |  |
| [Widen](./widen/)(const SharedPtr\<Pen\>\&) | Replaces this path with an outline around the original path. |
| [~GraphicsPath](./~graphicspath/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
