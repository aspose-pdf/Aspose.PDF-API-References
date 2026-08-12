---
title: "System::Drawing::Drawing2D::GraphicsPath class"
linktitle: "GraphicsPath"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::GraphicsPath class. Представляет набор соединённых линий и кривых. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath class


Представляет набор соединённых линий и кривых. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class GraphicsPath : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddArc](./addarc/)(float, float, float, float, float, float) | Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом. |
| [AddArc](./addarc/)(int, int, int, int, float, float) | Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом. |
| [AddArc](./addarc/)(const RectangleF\&, float, float) | Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом. |
| [AddArc](./addarc/)(const Rectangle\&, float, float) | Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом. |
| [AddBezier](./addbezier/)(const Point\&, const Point\&, const Point\&, const Point\&) | Добавляет указанную кубическую кривую Безье к пути, представленному текущим объектом. |
| [AddBezier](./addbezier/)(const PointF\&, const PointF\&, const PointF\&, const PointF\&) | Добавляет указанную кубическую кривую Безье к пути, представленному текущим объектом. |
| [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Добавляет указанную кубическую кривую Безье к пути, представленному текущим объектом. |
| [AddBezier](./addbezier/)(float, float, float, float, float, float, float, float) | Добавляет указанную кубическую кривую Безье к пути, представленному текущим объектом. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<Point\>\&) | Добавляет последовательность соединённых кубических кривых Безье к текущей фигуре. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<PointF\>\&) | Добавляет последовательность соединённых кубических кривых Безье к текущей фигуре. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<PointF\>\&, float) | Добавляет указанную замкнутую кривую к пути, представленному текущим объектом. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<Point\>\&, float) | Добавляет указанную замкнутую кривую к пути, представленному текущим объектом. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, float) | Добавляет указанную кривую к пути, представленному текущим объектом. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, float) | Добавляет указанную кривую к пути, представленному текущим объектом. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, int, int, float) | Добавляет указанную кривую к пути, представленному текущим объектом. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, int, int, float) | Добавляет указанную кривую к пути, представленному текущим объектом. |
| [AddEllipse](./addellipse/)(float, float, float, float) | Добавляет указанный эллипс к пути, представленному текущим объектом. |
| [AddEllipse](./addellipse/)(int, int, int, int) | Добавляет указанный эллипс к пути, представленному текущим объектом. |
| [AddEllipse](./addellipse/)(const RectangleF\&) | Добавляет указанный эллипс к пути, представленному текущим объектом. |
| [AddEllipse](./addellipse/)(const Rectangle\&) | Добавляет указанный эллипс к пути, представленному текущим объектом. |
| [AddLine](./addline/)(const Point\&, const Point\&) | Добавляет указанную линию к пути, представленному текущим объектом. |
| [AddLine](./addline/)(const PointF\&, const PointF\&) | Добавляет указанную линию к пути, представленному текущим объектом. |
| [AddLine](./addline/)(int, int, int, int) | Добавляет указанную линию к пути, представленному текущим объектом. |
| [AddLine](./addline/)(float, float, float, float) | Добавляет указанную линию к пути, представленному текущим объектом. |
| [AddLines](./addlines/)(const ArrayPtr\<PointF\>\&) | Добавляет указанную серию соединённых отрезков линий к пути, представленному текущим объектом. |
| [AddLines](./addlines/)(const ArrayPtr\<Point\>\&) | Добавляет указанную серию соединённых отрезков линий к пути, представленному текущим объектом. |
| [AddPath](./addpath/)(const SharedPtr\<GraphicsPath\>\&, bool) | Добавляет указанный путь к пути, представленному текущим объектом. |
| [AddPie](./addpie/)(float, float, float, float, float, float) | Добавляет указанный контур формы сектора к пути, представленному текущим объектом. |
| [AddPie](./addpie/)(int, int, int, int, float, float) | Добавляет указанный контур формы сектора к пути, представленному текущим объектом. |
| [AddPie](./addpie/)(const Rectangle\&, float, float) | Добавляет указанный контур формы сектора к пути, представленному текущим объектом. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<PointF\>\&) | Добавляет указанный многоугольник к пути, представленному текущим объектом. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<Point\>\&) | Добавляет указанный многоугольник к пути, представленному текущим объектом. |
| [AddRectangle](./addrectangle/)(const Rectangle\&) | Добавляет указанный прямоугольник к пути, представленному текущим объектом. |
| [AddRectangle](./addrectangle/)(const RectangleF\&) | Добавляет указанный прямоугольник к пути, представленному текущим объектом. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<Rectangle\>\&) | Добавляет указанную серию прямоугольников к пути, представленному текущим объектом. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<RectangleF\>\&) | Добавляет указанную серию прямоугольников к пути, представленному текущим объектом. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) | Добавляет строку текста к пути, представленному текущим объектом. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) | Добавляет строку текста к пути, представленному текущим объектом. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) | Добавляет строку текста к пути, представленному текущим объектом. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) | Добавляет строку текста к пути, представленному текущим объектом. |
| virtual [Clone](./clone/)() | Создаёт копию текущего объекта. |
| [CloseAllFigures](./closeallfigures/)() | Закрывает все открытые фигуры и начинает новую. |
| [CloseFigure](./closefigure/)() | Закрывает текущую фигуру и начинает новую. |
| [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, полученные текущим объектом. |
| [Flatten](./flatten/)() | Выравнивает каждую кривую в пути, преобразуя её в серию соединённых линий. Используется значение плоскостности 0.25. |
| [Flatten](./flatten/)(const MatrixPtr\&) | Выравнивает каждую кривую в пути, преобразуя её в серию соединённых линий. Используется значение плоскостности 0.25. |
| [Flatten](./flatten/)(const MatrixPtr\&, float) | Разглаживает каждую кривую в пути, преобразуя её в последовательность соединённых линий. |
| [get_FillMode](./get_fillmode/)() | Возвращает режим заливки текущего объекта. |
| [get_PathData](./get_pathdata/)() | Возвращает объект [PathData](../pathdata/), содержащий точки, из которых состоит путь, представленный текущим объектом, и их типы. |
| [get_PathPoints](./get_pathpoints/)() const | Возвращает массив, содержащий точки, из которых состоит путь, представленный текущим объектом. |
| [get_PathTypes](./get_pathtypes/)() const | Возвращает массив, содержащий значения, указывающие типы точек, из которых состоит путь, представленный текущим объектом. |
| [get_PointCount](./get_pointcount/)() const | Возвращает количество точек в пути, представленном текущим объектом. |
| [GetBounds](./getbounds/)(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const | Возвращает объект [RectangleF](../../system.drawing/rectanglef/), представляющий прямоугольник, ограничивающий путь, представленный текущим объектом, при трансформации с указанной матрицей. |
| [GetFigureFlags](./getfigureflags/)() | Возвращает значение, представляющее побитовое сочетание значений Detail::FigureType, указывающее, какие типы фигур содержатся в пути, представленном текущим объектом. |
| [GetLastPoint](./getlastpoint/)() const | Возвращает объект [PointF](../../system.drawing/pointf/), представляющий последнюю точку в пути. |
| [GraphicsPath](./graphicspath/)(FillMode) | Создаёт новый экземпляр класса [GraphicsPath](./) с указанным режимом заливки. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Создаёт новый экземпляр объекта [GraphicsPath](./), представляющего указанный путь. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Создаёт новый экземпляр объекта [GraphicsPath](./), представляющего указанный путь. |
| [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| [IsOutlineVisible](./isoutlinevisible/)(const PointF\&, const SharedPtr\<Pen\>\&) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](./) при отрисовке указанным [Pen](../../system.drawing/pen/). НЕ РЕАЛИЗОВАНО. |
| [IsVisible](./isvisible/)(const PointF\&) | Определяет, находится ли указанная точка внутри пути, представленного текущим объектом. |
| [IsVisible](./isvisible/)(float, float) | Определяет, находится ли указанная точка внутри пути, представленного текущим объектом. |
| [Reset](./reset/)() | Очищает путь, удаляя из него все точки. |
| [Reverse](./reverse/)() | Меняет порядок точек в массиве PathPoints этого [GraphicsPath](./) на обратный. |
| [set_FillMode](./set_fillmode/)(FillMode) | Устанавливает режим заливки текущего объекта. |
| [SetMarkers](./setmarkers/)() | НЕ РЕАЛИЗОВАНО. |
| [StartFigure](./startfigure/)() | Начинает новую фигуру. |
| [Transform](./transform/)(const MatrixPtr\&) | Трансформирует путь, представленный текущим объектом, применяя к нему указанную матрицу преобразования. |
| [Transform](./transform/)(const SkMatrix\&) |  |
| [Widen](./widen/)(const SharedPtr\<Pen\>\&) | Заменяет этот путь контуром вокруг оригинального пути. |
| [~GraphicsPath](./~graphicspath/)() | Деструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
