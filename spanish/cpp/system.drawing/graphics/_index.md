---
title: "Clase System::Drawing::Graphics"
linktitle: "Graphics"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Graphics. Representa una superficie de dibujo. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.drawing/graphics/
---
## Graphics class


Representa una superficie de dibujo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Graphics : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddMetafileComment](./addmetafilecomment/)(const System::ArrayPtr\<uint8_t\>\&) | NO IMPLEMENTADO. |
| [BeginContainer](./begincontainer/)() | Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado. |
| [BeginContainer](./begincontainer/)(Rectangle, Rectangle, GraphicsUnit) | Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado. |
| [BeginContainer](./begincontainer/)(RectangleF, RectangleF, GraphicsUnit) | Guarda un contenedor con el estado actual de este objeto, abre y usa un nuevo contenedor y devuelve el contenedor guardado. |
| [Clear](./clear/)(Color) | Limpia la superficie de dibujo representada por el objeto actual y la rellena con el color especificado. |
| [CopyFromScreen](./copyfromscreen/)(Point, Point, Size, CopyPixelOperation) | NO IMPLEMENTADO. |
| [CopyFromScreen](./copyfromscreen/)(int32_t, int32_t, int32_t, int32_t, Size, CopyPixelOperation) | NO IMPLEMENTADO. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) | Dibuja el arco especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) | Dibuja el arco especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, Rectangle, float, float) | Dibuja el arco especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, RectangleF, float, float) | Dibuja el arco especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, const Point\&, const Point\&, const Point\&, const Point\&) | NO IMPLEMENTADO. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, const PointF\&, const PointF\&, const PointF\&, const PointF\&) | NO IMPLEMENTADO. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float, float, float) | NO IMPLEMENTADO. |
| [DrawBeziers](./drawbeziers/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&) | Dibuja una serie de splines de Bézier usando la pluma especificada. |
| [DrawBeziers](./drawbeziers/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&) | Dibuja una serie de splines de Bézier usando la pluma especificada. |
| [DrawClosedCurve](./drawclosedcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) | Dibuja un spline cerrado usando la pluma especificada. |
| [DrawClosedCurve](./drawclosedcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) | Dibuja un spline cerrado usando la pluma especificada. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) | Dibuja un spline usando la pluma especificada. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) | Dibuja un spline usando la pluma especificada. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) | Dibuja un spline usando la pluma especificada. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) | Dibuja un spline usando la pluma especificada. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, Rectangle) | Dibuja la elipse especificada usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, RectangleF) | Dibuja la elipse especificada usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Dibuja la elipse especificada usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Dibuja la elipse especificada usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawIcon](./drawicon/)(const SharedPtr\<Icon\>\&, Rectangle) | NO IMPLEMENTADO. |
| [DrawIcon](./drawicon/)(const SharedPtr\<Icon\>\&, int32_t, int32_t) | NO IMPLEMENTADO. |
| [DrawIconUnstretched](./drawiconunstretched/)(const SharedPtr\<Icon\>\&, Rectangle) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int) | Dibuja la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float) | Dibuja la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Point) | Dibuja la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, PointF) | Dibuja la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int, int, int) | Dibuja la imagen especificada en el rectángulo especificado. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float, float, float) | Dibuja la imagen especificada en el rectángulo especificado. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const Rectangle\&) | Dibuja la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const RectangleF\&) | Dibuja la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Dibuja la región especificada de la imagen especificada en el rectángulo especificado. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Dibuja la región especificada de la imagen especificada en el rectángulo especificado. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) | Dibuja la región especificada de la imagen especificada en el rectángulo especificado. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) | Dibuja la región especificada de la imagen especificada en el rectángulo especificado. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) | NO IMPLEMENTADO. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) | Dibuja la región especificada de la imagen especificada en la ubicación especificada. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, int, int) | Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, int, int, int, int) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, const Rectangle\&) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, const Point\&) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const SharedPtr\<Image\>\&, Rectangle) | NO IMPLEMENTADO. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, Point, Point) | Dibuja la línea especificada usando la pluma especificada. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, PointF, PointF) | Dibuja la línea especificada usando la pluma especificada. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Dibuja la línea especificada usando la pluma especificada. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Dibuja la línea especificada usando la pluma especificada. |
| [DrawLines](./drawlines/)(const SharedPtr\<Pen\>\&, const System::ArrayPtr\<System::Drawing::Point\>\&) | Dibuja una serie de segmentos de línea usando la pluma especificada. |
| [DrawLines](./drawlines/)(const SharedPtr\<Pen\>\&, const System::ArrayPtr\<System::Drawing::PointF\>\&) | Dibuja una serie de segmentos de línea usando la pluma especificada. |
| [DrawPath](./drawpath/)(const SharedPtr\<Pen\>\&, const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Dibuja la ruta especificada usando la pluma especificada. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) | Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) | Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, Rectangle, float, float) | Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, RectangleF, float, float) | Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawPolygon](./drawpolygon/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&) | Dibuja un polígono usando la pluma especificada. |
| [DrawPolygon](./drawpolygon/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&) | Dibuja un polígono usando la pluma especificada. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Dibuja el rectángulo especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Dibuja el rectángulo especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, Rectangle) | Dibuja el rectángulo especificado usando la pluma especificada en la superficie representada por el objeto actual. |
| [DrawRectangles](./drawrectangles/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Rectangle\>\&) | Dibuja una serie de rectángulos usando la pluma especificada. |
| [DrawRectangles](./drawrectangles/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<RectangleF\>\&) | Dibuja una serie de rectángulos usando la pluma especificada. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Dibuja la cadena especificada en el rectángulo especificado usando la fuente y el pincel especificados. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados. |
| [EndContainer](./endcontainer/)(const SharedPtr\<Drawing2D::GraphicsContainer\>\&) | Cierra el contenedor actual y restaura el estado de este objeto a partir del estado del contenedor guardado. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<PointF\>\&, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<Point\>\&, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Point, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, PointF, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Rectangle, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, RectangleF, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Point, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, PointF, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Rectangle, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, RectangleF, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | NO IMPLEMENTADO. |
| [ExcludeClip](./excludeclip/)(Rectangle) | NO IMPLEMENTADO. |
| [ExcludeClip](./excludeclip/)(const SharedPtr\<Region\>\&) | NO IMPLEMENTADO. |
| [FillClosedCurve](./fillclosedcurve/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) | Dibuja una spline cerrada usando el pincel especificado. |
| [FillClosedCurve](./fillclosedcurve/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) | Dibuja una spline cerrada usando el pincel especificado. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, Rectangle) | Rellena el interior de la elipse especificada por el rectángulo delimitador usando el pincel especificado. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, RectangleF) | Rellena el interior de la elipse especificada por el rectángulo delimitador usando el pincel especificado. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, int, int, int, int) | Rellena el interior de la elipse especificada por el rectángulo delimitador usando el pincel especificado. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, float, float, float, float) | Rellena el interior de la elipse especificada por el rectángulo delimitador usando el pincel especificado. |
| [FillPath](./fillpath/)(const SharedPtr\<Brush\>\&, const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Rellena los interiores de la ruta especificada usando el pincel especificado. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) | Rellena el sector especificado usando el pincel especificado en la superficie representada por el objeto actual. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) | Rellena el sector especificado usando el pincel especificado en la superficie representada por el objeto actual. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, Rectangle, float, float) | Rellena el sector especificado usando el pincel especificado en la superficie representada por el objeto actual. |
| [FillPolygon](./fillpolygon/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) | Rellena los interiores del polígono especificado usando el pincel especificado. |
| [FillPolygon](./fillpolygon/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) | Rellena los interiores del polígono especificado usando el pincel especificado. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, float, float, float, float) | Rellena el rectángulo especificado con el pincel especificado. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, int, int, int, int) | Rellena el rectángulo especificado con el pincel especificado. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, Rectangle) | Rellena el rectángulo especificado con el pincel especificado. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, RectangleF) | Rellena el rectángulo especificado con el pincel especificado. |
| [FillRectangles](./fillrectangles/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Rectangle\>\&) | Rellena una serie de rectángulos usando el pincel especificado. |
| [FillRectangles](./fillrectangles/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<RectangleF\>\&) | Rellena una serie de rectángulos usando el pincel especificado. |
| [FillRegion](./fillregion/)(const SharedPtr\<Brush\>\&, const SharedPtr\<Region\>\&) | Rellena los interiores de la región especificada usando el pincel especificado. |
| [Flush](./flush/)(Drawing2D::FlushIntention) | Desencadena la ejecución inmediata de todas las operaciones de dibujo pendientes. |
| static [FromHwnd](./fromhwnd/)(IntPtr) | NO IMPLEMENTADO. |
| static [FromHwndInternal](./fromhwndinternal/)(IntPtr) | NO IMPLEMENTADO. |
| static [FromImage](./fromimage/)(const SharedPtr\<Image\>\&) | Crea un nuevo objeto [Graphics](./) a partir de la imagen especificada. |
| [get_Clip](./get_clip/)() | Devuelve un objeto [Region](../region/) que representa una región que limita el área de dibujo de la superficie de dibujo representada por el objeto [Graphics](./) actual. |
| [get_ClipBounds](./get_clipbounds/)() const | Devuelve un rectángulo que delimita el área de recorte de la superficie representada por el objeto actual. |
| [get_CompositingMode](./get_compositingmode/)() | Devuelve un valor que indica cómo se dibujan las imágenes compuestas en la superficie representada por el objeto actual. |
| [get_CompositingQuality](./get_compositingquality/)() | Devuelve un valor que indica el nivel de calidad utilizado al componer imágenes. |
| [get_DpiX](./get_dpix/)() | Devuelve la resolución horizontal. |
| [get_DpiY](./get_dpiy/)() | Devuelve la resolución vertical. |
| [get_InterpolationMode](./get_interpolationmode/)() | Devuelve un valor que indica el modo de interpolación asociado al objeto actual. |
| [get_IsClipEmpty](./get_isclipempty/)() const | NO IMPLEMENTADO. |
| [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | NO IMPLEMENTADO. |
| [get_PageScale](./get_pagescale/)() const | Devuelve la escala entre unidades del mundo y unidades de página para el objeto [Graphics](./) actual. |
| [get_PageUnit](./get_pageunit/)() const | Devuelve las unidades de medida utilizadas para las coordenadas de página en la superficie representada por el objeto actual. |
| [get_PixelOffsetMode](./get_pixeloffsetmode/)() | Devuelve un valor que indica cómo se desplazan los píxeles durante el renderizado en la superficie representada por el objeto actual. |
| [get_RenderingOrigin](./get_renderingorigin/)() const | Devuelve un objeto [Point](../point/) que representa el origen de renderizado del objeto [Graphics](./) actual para tramado y para pinceles de trama. |
| [get_SmoothingMode](./get_smoothingmode/)() | Devuelve un valor que indica un modo de suavizado utilizado durante el renderizado en la superficie representada por el objeto actual. |
| [get_TextContrast](./get_textcontrast/)() const | NO IMPLEMENTADO. |
| [get_TextRenderingHint](./get_textrenderinghint/)() | Devuelve un valor que indica la calidad del renderizado de texto. |
| [get_Transform](./get_transform/)() | Devuelve la transformación geométrica del mundo para el objeto [Graphics](./) actual. |
| [get_VisibleClipBounds](./get_visibleclipbounds/)() const | Devuelve el objeto [RectangleF](../rectanglef/) que representa un rectángulo delimitador de la región de recorte visible del objeto [Graphics](./) actual. |
| [GetHdc](./gethdc/)() | NO IMPLEMENTADO. |
| [GetNearestColor](./getnearestcolor/)(Color) | NO IMPLEMENTADO. |
| [GetSkCanvas](./getskcanvas/)() const |  |
| [IntersectClip](./intersectclip/)(const System::SharedPtr\<Region\>\&) | Actualiza la región de recorte de este objeto a la intersección del recorte actual y el recorte especificado. |
| [IntersectClip](./intersectclip/)(System::Drawing::RectangleF) | Actualiza la región de recorte de este objeto a la intersección del recorte actual y el recorte especificado. |
| [IntersectClip](./intersectclip/)(System::Drawing::Rectangle) | Actualiza la región de recorte de este objeto a la intersección del recorte actual y el recorte especificado. |
| [IsVisible](./isvisible/)(Point) | Determina si el punto especificado está contenido dentro de la región de recorte visible del objeto [Graphics](./) actual. |
| [IsVisible](./isvisible/)(PointF) | NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(Rectangle) | NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(RectangleF) | NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(int32_t, int32_t) | NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(float, float) | NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(float, float, float, float) | NO IMPLEMENTADO. |
| [IsVisible](./isvisible/)(int32_t, int32_t, int32_t, int32_t) | NO IMPLEMENTADO. |
| [MeasureCharacterRanges](./measurecharacterranges/)(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) | Devuelve una matriz de regiones, cada una de las cuales delimita posiciones de caracteres en la cadena especificada. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const | Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const | Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const | NO IMPLEMENTADO. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const | Devuelve el tamaño de la cadena especificada cuando se dibuja con la fuente especificada en el formato especificado. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplica la matriz de transformación del mundo del objeto [Graphics](./) actual por la matriz especificada. |
| [ReleaseHdc](./releasehdc/)() | NO IMPLEMENTADO. |
| [ReleaseHdc](./releasehdc/)(IntPtr) | NO IMPLEMENTADO. |
| [ResetClip](./resetclip/)() | Restablece la región de recorte de este gráfico a una región infinita. |
| [ResetTransform](./resettransform/)() | Restablece la matriz de transformación del mundo del objeto actual para que se convierta en una matriz identidad. |
| [Restore](./restore/)(const SharedPtr\<Drawing2D::GraphicsState\>\&) | Restaura el estado de este objeto desde el estado guardado. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Aplica la rotación especificada a la matriz de transformación del mundo del objeto [Graphics](./) actual en el orden especificado. |
| [Save](./save/)() | Guarda el estado actual de este objeto y devuelve el estado guardado. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Aplica el vector de escala especificado a la matriz de transformación del mundo del objeto actual. |
| [set_Clip](./set_clip/)(const SharedPtr\<Region\>\&) | Establece una región que limita el área de dibujo de la superficie de dibujo representada por el actual. |
| [set_CompositingMode](./set_compositingmode/)(Drawing2D::CompositingMode) | Establece un valor que especifica cómo se dibujan las imágenes compuestas en la superficie representada por el objeto actual. |
| [set_CompositingQuality](./set_compositingquality/)(Drawing2D::CompositingQuality) | Establece un valor que especifica el nivel de calidad a usar al componer imágenes. |
| [set_InterpolationMode](./set_interpolationmode/)(Drawing2D::InterpolationMode) | Establece un valor que indica el modo de interpolación asociado al objeto actual. |
| [set_PageScale](./set_pagescale/)(float) | Establece la escala entre unidades del mundo y unidades de página para el objeto [Graphics](./) actual. |
| [set_PageUnit](./set_pageunit/)(GraphicsUnit) | Establece las unidades de medida usadas para las coordenadas de página en la superficie representada por el objeto actual. |
| [set_PixelOffsetMode](./set_pixeloffsetmode/)(Drawing2D::PixelOffsetMode) | Establece un valor que especifica cómo se deben desplazar los píxeles durante el renderizado en la superficie representada por el objeto actual. |
| [set_RenderingOrigin](./set_renderingorigin/)(Point) | Establece un objeto [Point](../point/) que especifica el origen de renderizado del objeto [Graphics](./) actual para el tramado y para pinceles de trama. |
| [set_SmoothingMode](./set_smoothingmode/)(Drawing2D::SmoothingMode) | Establece un valor que especifica un modo suavizante usado durante el renderizado en la superficie representada por el objeto actual. |
| [set_TextContrast](./set_textcontrast/)(int32_t) | NO IMPLEMENTADO. |
| [set_TextRenderingHint](./set_textrenderinghint/)(Text::TextRenderingHint) | Establece un valor que especifica la calidad del renderizado de texto. |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Establece la transformación geométrica del mundo para el objeto [Graphics](./) actual. |
| [SetClip](./setclip/)(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) | Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](./) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada. |
| [SetClip](./setclip/)(Rectangle, Drawing2D::CombineMode) | Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](./) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada. |
| [SetClip](./setclip/)(RectangleF, Drawing2D::CombineMode) | Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](./) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada. |
| [SetClip](./setclip/)(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) | NO IMPLEMENTADO. |
| [SetClip](./setclip/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) | Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](./) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada por una ruta gráfica. |
| [TransformPoints](./transformpoints/)(Drawing2D::CoordinateSpace, Drawing2D::CoordinateSpace, const ArrayPtr\<System::Drawing::Point\>\&) | NO IMPLEMENTADO. |
| [TransformPoints](./transformpoints/)(Drawing2D::CoordinateSpace, Drawing2D::CoordinateSpace, const ArrayPtr\<System::Drawing::PointF\>\&) | NO IMPLEMENTADO. |
| [TranslateClip](./translateclip/)(int, int) | NO IMPLEMENTADO. |
| [TranslateClip](./translateclip/)(float, float) | NO IMPLEMENTADO. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Aplica el vector de traslación especificado a la matriz de transformación mundial del objeto [Graphics](./) actual. |
| [~Graphics](./~graphics/)() |  |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [DrawImageAbort](./drawimageabort/) | El tipo de un objeto de función de devolución de llamada utilizado como argumento para el método DrawImage. |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | El tipo de un objeto de función de devolución de llamada utilizado como argumento para el método EnumerateMetafile. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
