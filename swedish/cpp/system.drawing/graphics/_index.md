---
title: "System::Drawing::Graphics-klass"
linktitle: "Grafik"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Graphics-klass. Representerar en ritningsyta. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.drawing/graphics/
---
## Graphics class


Representerar en ritningsyta. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Graphics : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddMetafileComment](./addmetafilecomment/)(const System::ArrayPtr\<uint8_t\>\&) | INTE IMPLEMENTERAD. |
| [BeginContainer](./begincontainer/)() | Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren. |
| [BeginContainer](./begincontainer/)(Rectangle, Rectangle, GraphicsUnit) | Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren. |
| [BeginContainer](./begincontainer/)(RectangleF, RectangleF, GraphicsUnit) | Sparar en behållare med det aktuella tillståndet för detta objekt, öppnar och använder en ny behållare och returnerar den sparade behållaren. |
| [Clear](./clear/)(Color) | Rensar den ritningsyta som representeras av det aktuella objektet och fyller den med den angivna färgen. |
| [CopyFromScreen](./copyfromscreen/)(Point, Point, Size, CopyPixelOperation) | INTE IMPLEMENTERAD. |
| [CopyFromScreen](./copyfromscreen/)(int32_t, int32_t, int32_t, int32_t, Size, CopyPixelOperation) | INTE IMPLEMENTERAD. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) | Ritar den angivna bågen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) | Ritar den angivna bågen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, Rectangle, float, float) | Ritar den angivna bågen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, RectangleF, float, float) | Ritar den angivna bågen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, const Point\&, const Point\&, const Point\&, const Point\&) | INTE IMPLEMENTERAD. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, const PointF\&, const PointF\&, const PointF\&, const PointF\&) | INTE IMPLEMENTERAD. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float, float, float) | INTE IMPLEMENTERAD. |
| [DrawBeziers](./drawbeziers/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&) | Ritar en serie av Bezier-splines med den angivna pennan. |
| [DrawBeziers](./drawbeziers/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&) | Ritar en serie av Bezier-splines med den angivna pennan. |
| [DrawClosedCurve](./drawclosedcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) | Ritar en sluten spline med den angivna pennan. |
| [DrawClosedCurve](./drawclosedcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) | Ritar en sluten spline med den angivna pennan. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) | Ritar en spline med den angivna pennan. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) | Ritar en spline med den angivna pennan. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) | Ritar en spline med den angivna pennan. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) | Ritar en spline med den angivna pennan. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, Rectangle) | Ritar den angivna ellipsen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, RectangleF) | Ritar den angivna ellipsen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Ritar den angivna ellipsen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Ritar den angivna ellipsen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawIcon](./drawicon/)(const SharedPtr\<Icon\>\&, Rectangle) | INTE IMPLEMENTERAD. |
| [DrawIcon](./drawicon/)(const SharedPtr\<Icon\>\&, int32_t, int32_t) | INTE IMPLEMENTERAD. |
| [DrawIconUnstretched](./drawiconunstretched/)(const SharedPtr\<Icon\>\&, Rectangle) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int) | Ritar den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float) | Ritar den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Point) | Ritar den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, PointF) | Ritar den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int, int, int) | Ritar den angivna bilden till den angivna rektangeln. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float, float, float) | Ritar den angivna bilden till den angivna rektangeln. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const Rectangle\&) | Ritar den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const RectangleF\&) | Ritar den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Ritar det angivna området av den angivna bilden till den angivna rektangeln. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Ritar det angivna området av den angivna bilden till den angivna rektangeln. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) | Ritar det angivna området av den angivna bilden till den angivna rektangeln. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) | Ritar det angivna området av den angivna bilden till den angivna rektangeln. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) | INTE IMPLEMENTERAD. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) | Ritar det angivna området av den angivna bilden på den angivna platsen. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, int, int) | Ritar den angivna bilden med sin ursprungliga fysiska storlek på den angivna platsen. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, int, int, int, int) | Ritar en angiven bild med sin ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, const Rectangle\&) | Ritar en angiven bild med sin ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, const Point\&) | Ritar en angiven bild med sin ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const SharedPtr\<Image\>\&, Rectangle) | INTE IMPLEMENTERAD. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, Point, Point) | Ritar den angivna linjen med den angivna pennan. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, PointF, PointF) | Ritar den angivna linjen med den angivna pennan. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Ritar den angivna linjen med den angivna pennan. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Ritar den angivna linjen med den angivna pennan. |
| [DrawLines](./drawlines/)(const SharedPtr\<Pen\>\&, const System::ArrayPtr\<System::Drawing::Point\>\&) | Ritar en serie av linjesegment med den angivna pennan. |
| [DrawLines](./drawlines/)(const SharedPtr\<Pen\>\&, const System::ArrayPtr\<System::Drawing::PointF\>\&) | Ritar en serie av linjesegment med den angivna pennan. |
| [DrawPath](./drawpath/)(const SharedPtr\<Pen\>\&, const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Ritar den angivna vägen med den angivna pennan. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) | Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) | Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, Rectangle, float, float) | Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, RectangleF, float, float) | Ritar den angivna pajen med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawPolygon](./drawpolygon/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&) | Ritar en polygon med den angivna pennan. |
| [DrawPolygon](./drawpolygon/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&) | Ritar en polygon med den angivna pennan. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Ritar den angivna rektangeln med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Ritar den angivna rektangeln med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, Rectangle) | Ritar den angivna rektangeln med den angivna pennan på ytan som representeras av det aktuella objektet. |
| [DrawRectangles](./drawrectangles/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Rectangle\>\&) | Ritar en serie rektanglar med den angivna pennan. |
| [DrawRectangles](./drawrectangles/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<RectangleF\>\&) | Ritar en serie rektanglar med den angivna pennan. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Ritar den angivna strängen på den angivna platsen med det angivna teckensnittet och penseln. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Ritar den angivna strängen i den angivna rektangeln med det angivna teckensnittet och penseln. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Ritar den angivna strängen på den angivna platsen med det angivna teckensnittet och penseln. |
| [EndContainer](./endcontainer/)(const SharedPtr\<Drawing2D::GraphicsContainer\>\&) | Stänger den aktuella behållaren och återställer objektets tillstånd från det sparade behållarens tillstånd. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<PointF\>\&, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<Point\>\&, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Point, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, PointF, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Rectangle, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, RectangleF, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Point, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, PointF, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Rectangle, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, RectangleF, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | INTE IMPLEMENTERAD. |
| [ExcludeClip](./excludeclip/)(Rectangle) | INTE IMPLEMENTERAD. |
| [ExcludeClip](./excludeclip/)(const SharedPtr\<Region\>\&) | INTE IMPLEMENTERAD. |
| [FillClosedCurve](./fillclosedcurve/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) | Ritar en sluten spline med den angivna penseln. |
| [FillClosedCurve](./fillclosedcurve/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) | Ritar en sluten spline med den angivna penseln. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, Rectangle) | Fyller insidan av ellipsen som anges av den omgivande rektangeln med den angivna penseln. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, RectangleF) | Fyller insidan av ellipsen som anges av den omgivande rektangeln med den angivna penseln. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, int, int, int, int) | Fyller insidan av ellipsen som anges av den omgivande rektangeln med den angivna penseln. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, float, float, float, float) | Fyller insidan av ellipsen som anges av den omgivande rektangeln med den angivna penseln. |
| [FillPath](./fillpath/)(const SharedPtr\<Brush\>\&, const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Fyller insidan av den angivna banan med den angivna penseln. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) | Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) | Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, Rectangle, float, float) | Fyller den angivna pajen med den angivna penseln på ytan som representeras av det aktuella objektet. |
| [FillPolygon](./fillpolygon/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) | Fyller insidan av den angivna polygonen med den angivna penseln. |
| [FillPolygon](./fillpolygon/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) | Fyller insidan av den angivna polygonen med den angivna penseln. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, float, float, float, float) | Fyller den angivna rektangeln med den angivna penseln. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, int, int, int, int) | Fyller den angivna rektangeln med den angivna penseln. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, Rectangle) | Fyller den angivna rektangeln med den angivna penseln. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, RectangleF) | Fyller den angivna rektangeln med den angivna penseln. |
| [FillRectangles](./fillrectangles/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Rectangle\>\&) | Fyller en serie rektanglar med den angivna penseln. |
| [FillRectangles](./fillrectangles/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<RectangleF\>\&) | Fyller en serie rektanglar med den angivna penseln. |
| [FillRegion](./fillregion/)(const SharedPtr\<Brush\>\&, const SharedPtr\<Region\>\&) | Fyller insidan av det angivna området med den angivna penseln. |
| [Flush](./flush/)(Drawing2D::FlushIntention) | Utlöser omedelbar körning av alla väntande ritoperationer. |
| static [FromHwnd](./fromhwnd/)(IntPtr) | INTE IMPLEMENTERAD. |
| static [FromHwndInternal](./fromhwndinternal/)(IntPtr) | INTE IMPLEMENTERAD. |
| static [FromImage](./fromimage/)(const SharedPtr\<Image\>\&) | Skapar ett nytt [Graphics](./)-objekt från den angivna bilden. |
| [get_Clip](./get_clip/)() | Returnerar ett [Region](../region/)-objekt som representerar ett område som begränsar ritningsytan för den ritningsyta som representeras av det aktuella [Graphics](./)-objektet. |
| [get_ClipBounds](./get_clipbounds/)() const | Returnerar en rektangel som avgränsar beskärningsområdet för ytan som representeras av det aktuella objektet. |
| [get_CompositingMode](./get_compositingmode/)() | Returnerar ett värde som indikerar hur sammansatta bilder ritas på ytan som representeras av det aktuella objektet. |
| [get_CompositingQuality](./get_compositingquality/)() | Returnerar ett värde som indikerar kvalitetsnivån som används vid sammanslagning av bilder. |
| [get_DpiX](./get_dpix/)() | Returnerar den horisontella upplösningen. |
| [get_DpiY](./get_dpiy/)() | Returnerar den vertikala upplösningen. |
| [get_InterpolationMode](./get_interpolationmode/)() | Returnerar ett värde som indikerar interpolationsläget som är associerat med det aktuella objektet. |
| [get_IsClipEmpty](./get_isclipempty/)() const | INTE IMPLEMENTERAD. |
| [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | INTE IMPLEMENTERAD. |
| [get_PageScale](./get_pagescale/)() const | Returnerar skalningen mellan värdenheter och sid‑enheter för det aktuella [Graphics](./)-objektet. |
| [get_PageUnit](./get_pageunit/)() const | Returnerar mätenheter som används för sidkoordinater på ytan som representeras av det aktuella objektet. |
| [get_PixelOffsetMode](./get_pixeloffsetmode/)() | Returnerar ett värde som indikerar hur pixlarna förskjuts under rendering på ytan som representeras av det aktuella objektet. |
| [get_RenderingOrigin](./get_renderingorigin/)() const | Returnerar ett [Point](../point/)‑objekt som representerar renderingsursprunget för det aktuella [Graphics](./)‑objektet för dithering och för hatch‑penslar. |
| [get_SmoothingMode](./get_smoothingmode/)() | Returnerar ett värde som indikerar ett lugnande läge som används under rendering på ytan som representeras av det aktuella objektet. |
| [get_TextContrast](./get_textcontrast/)() const | INTE IMPLEMENTERAD. |
| [get_TextRenderingHint](./get_textrenderinghint/)() | Returnerar ett värde som indikerar kvaliteten på textrendering. |
| [get_Transform](./get_transform/)() | Returnerar den geometriska världstransformationen för det aktuella [Graphics](./)‑objektet. |
| [get_VisibleClipBounds](./get_visibleclipbounds/)() const | Returnerar [RectangleF](../rectanglef/)‑objektet som representerar en omgivande rektangel för den synliga beskärningsregionen för det aktuella [Graphics](./)‑objektet. |
| [GetHdc](./gethdc/)() | INTE IMPLEMENTERAD. |
| [GetNearestColor](./getnearestcolor/)(Color) | INTE IMPLEMENTERAD. |
| [GetSkCanvas](./getskcanvas/)() const |  |
| [IntersectClip](./intersectclip/)(const System::SharedPtr\<Region\>\&) | Uppdaterar klippregionen för detta objekt till skärningspunkten mellan den aktuella klippningen och den angivna klippningen. |
| [IntersectClip](./intersectclip/)(System::Drawing::RectangleF) | Uppdaterar klippregionen för detta objekt till skärningspunkten mellan den aktuella klippningen och den angivna klippningen. |
| [IntersectClip](./intersectclip/)(System::Drawing::Rectangle) | Uppdaterar klippregionen för detta objekt till skärningspunkten mellan den aktuella klippningen och den angivna klippningen. |
| [IsVisible](./isvisible/)(Point) | Avgör om den angivna punkten finns inom den synliga klippregionen för det aktuella [Graphics](./)‑objektet. |
| [IsVisible](./isvisible/)(PointF) | INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(Rectangle) | INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(RectangleF) | INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(int32_t, int32_t) | INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(float, float) | INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(float, float, float, float) | INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(int32_t, int32_t, int32_t, int32_t) | INTE IMPLEMENTERAD. |
| [MeasureCharacterRanges](./measurecharacterranges/)(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) | Returnerar en array av regioner som var och en begränsar teckenpositioner i den angivna strängen. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const | Returnerar storleken på den angivna strängen när den ritas med det angivna typsnittet i det angivna formatet. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const | Returnerar storleken på den angivna strängen när den ritas med det angivna typsnittet i det angivna formatet. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const | INTE IMPLEMENTERAD. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const | Returnerar storleken på den angivna strängen när den ritas med det angivna typsnittet i det angivna formatet. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplicerar världstransformationsmatrisen för det aktuella [Graphics](./)‑objektet med den angivna matrisen. |
| [ReleaseHdc](./releasehdc/)() | INTE IMPLEMENTERAD. |
| [ReleaseHdc](./releasehdc/)(IntPtr) | INTE IMPLEMENTERAD. |
| [ResetClip](./resetclip/)() | Återställer klippregionen för denna grafik till en oändlig region. |
| [ResetTransform](./resettransform/)() | Återställer världstransformationsmatrisen för det aktuella objektet så att den blir en identitetsmatris. |
| [Restore](./restore/)(const SharedPtr\<Drawing2D::GraphicsState\>\&) | Återställer tillståndet för detta objekt från det sparade tillståndet. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Tillämpar den angivna rotationen på världstransformationsmatrisen för det aktuella [Graphics](./)‑objektet i den angivna ordningen. |
| [Save](./save/)() | Sparar det aktuella tillståndet för detta objekt och returnerar det sparade tillståndet. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Tillämpar den angivna skalningsvektorn på världstransformationsmatrisen för det aktuella objektet. |
| [set_Clip](./set_clip/)(const SharedPtr\<Region\>\&) | Ställer in en region som begränsar ritningsområdet för den ritningsyta som representeras av det aktuella objektet. |
| [set_CompositingMode](./set_compositingmode/)(Drawing2D::CompositingMode) | Ställer in ett värde som specificerar hur sammansatta bilder ritas på ytan som representeras av det aktuella objektet. |
| [set_CompositingQuality](./set_compositingquality/)(Drawing2D::CompositingQuality) | Ställer in ett värde som specificerar kvalitetsnivån som ska användas vid sammanslagning av bilder. |
| [set_InterpolationMode](./set_interpolationmode/)(Drawing2D::InterpolationMode) | Ställer in ett värde som indikerar interpolationsläget som är associerat med det aktuella objektet. |
| [set_PageScale](./set_pagescale/)(float) | Ställer in skalningen mellan världsenheter och sid-enheter för det aktuella [Graphics](./)‑objektet. |
| [set_PageUnit](./set_pageunit/)(GraphicsUnit) | Ställer in mätenheter som används för sidkoordinater på ytan som representeras av det aktuella objektet. |
| [set_PixelOffsetMode](./set_pixeloffsetmode/)(Drawing2D::PixelOffsetMode) | Ställer in ett värde som specificerar hur pixlarna ska förskjutas under rendering på ytan som representeras av det aktuella objektet. |
| [set_RenderingOrigin](./set_renderingorigin/)(Point) | Ställer in ett [Point](../point/)‑objekt som specificerar renderingsursprunget för det aktuella [Graphics](./)‑objektet för dithering och för hatch‑penslar. |
| [set_SmoothingMode](./set_smoothingmode/)(Drawing2D::SmoothingMode) | Ställer in ett värde som specificerar ett lugnande läge som används under rendering på ytan som representeras av det aktuella objektet. |
| [set_TextContrast](./set_textcontrast/)(int32_t) | INTE IMPLEMENTERAD. |
| [set_TextRenderingHint](./set_textrenderinghint/)(Text::TextRenderingHint) | Ställer in ett värde som specificerar kvaliteten på textåtergivning. |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Ställer in den geometriska världstransformationen för det aktuella [Graphics](./)-objektet. |
| [SetClip](./setclip/)(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) | Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](./)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den angivna regionen. |
| [SetClip](./setclip/)(Rectangle, Drawing2D::CombineMode) | Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](./)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den angivna regionen. |
| [SetClip](./setclip/)(RectangleF, Drawing2D::CombineMode) | Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](./)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och den angivna regionen. |
| [SetClip](./setclip/)(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) | INTE IMPLEMENTERAD. |
| [SetClip](./setclip/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) | Ställer in beskärningsregionen för ritytan som representeras av det aktuella [Graphics](./)-objektet till resultatet av den angivna operationen som kombinerar den aktuella beskärningsregionen och regionen som specificeras av en grafikstig. |
| [TransformPoints](./transformpoints/)(Drawing2D::CoordinateSpace, Drawing2D::CoordinateSpace, const ArrayPtr\<System::Drawing::Point\>\&) | INTE IMPLEMENTERAD. |
| [TransformPoints](./transformpoints/)(Drawing2D::CoordinateSpace, Drawing2D::CoordinateSpace, const ArrayPtr\<System::Drawing::PointF\>\&) | INTE IMPLEMENTERAD. |
| [TranslateClip](./translateclip/)(int, int) | INTE IMPLEMENTERAD. |
| [TranslateClip](./translateclip/)(float, float) | INTE IMPLEMENTERAD. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Tillämpar den angivna translationsvektorn på världstransformationsmatrisen för det aktuella [Graphics](./)-objektet. |
| [~Graphics](./~graphics/)() |  |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [DrawImageAbort](./drawimageabort/) | Typen av ett återuppringningsfunktion-objekt som används som argument för DrawImage-metoden. |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | Typen av ett återuppringningsfunktion-objekt som används som argument för EnumerateMetafile-metoden. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
