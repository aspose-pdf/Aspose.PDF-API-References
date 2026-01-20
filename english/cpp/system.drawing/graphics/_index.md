---
title: System::Drawing::Graphics class
linktitle: Graphics
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics class. Represents a drawing surface. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.drawing/graphics/
---
## Graphics class


Represents a drawing surface. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Graphics : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddMetafileComment](./addmetafilecomment/)(const System::ArrayPtr\<uint8_t\>\&) | NOT IMPLEMENTED. |
| [BeginContainer](./begincontainer/)() | Saves a container with the current state of this object, opens and uses a new container and returns the saved container. |
| [BeginContainer](./begincontainer/)(Rectangle, Rectangle, GraphicsUnit) | Saves a container with the current state of this object, opens and uses a new container and returns the saved container. |
| [BeginContainer](./begincontainer/)(RectangleF, RectangleF, GraphicsUnit) | Saves a container with the current state of this object, opens and uses a new container and returns the saved container. |
| [Clear](./clear/)(Color) | Clears the drawing surface represented by the current object and fills it with the specified color. |
| [CopyFromScreen](./copyfromscreen/)(Point, Point, Size, CopyPixelOperation) | NOT IMPLEMENTED. |
| [CopyFromScreen](./copyfromscreen/)(int32_t, int32_t, int32_t, int32_t, Size, CopyPixelOperation) | NOT IMPLEMENTED. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) | Draws the specified arc using the specified pen on the surface represented by the current object. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) | Draws the specified arc using the specified pen on the surface represented by the current object. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, Rectangle, float, float) | Draws the specified arc using the specified pen on the surface represented by the current object. |
| [DrawArc](./drawarc/)(const SharedPtr\<Pen\>\&, RectangleF, float, float) | Draws the specified arc using the specified pen on the surface represented by the current object. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, const Point\&, const Point\&, const Point\&, const Point\&) | NOT IMPLEMENTED. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, const PointF\&, const PointF\&, const PointF\&, const PointF\&) | NOT IMPLEMENTED. |
| [DrawBezier](./drawbezier/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float, float, float) | NOT IMPLEMENTED. |
| [DrawBeziers](./drawbeziers/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&) | Draws a series of Bezier splines using the specified pen. |
| [DrawBeziers](./drawbeziers/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&) | Draws a series of Bezier splines using the specified pen. |
| [DrawClosedCurve](./drawclosedcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) | Draws a closed spline using the specified pen. |
| [DrawClosedCurve](./drawclosedcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) | Draws a closed spline using the specified pen. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) | Draws a spline using the specified pen. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) | Draws a spline using the specified pen. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) | Draws a spline using the specified pen. |
| [DrawCurve](./drawcurve/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) | Draws a spline using the specified pen. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, Rectangle) | Draws the specified ellipse using the specified pen on the surface represented by the current object. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, RectangleF) | Draws the specified ellipse using the specified pen on the surface represented by the current object. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Draws the specified ellipse using the specified pen on the surface represented by the current object. |
| [DrawEllipse](./drawellipse/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Draws the specified ellipse using the specified pen on the surface represented by the current object. |
| [DrawIcon](./drawicon/)(const SharedPtr\<Icon\>\&, Rectangle) | NOT IMPLEMENTED. |
| [DrawIcon](./drawicon/)(const SharedPtr\<Icon\>\&, int32_t, int32_t) | NOT IMPLEMENTED. |
| [DrawIconUnstretched](./drawiconunstretched/)(const SharedPtr\<Icon\>\&, Rectangle) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int) | Draws the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float) | Draws the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Point) | Draws the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, PointF) | Draws the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int, int, int) | Draws the specified image to the specified rectangle. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float, float, float) | Draws the specified image to the specified rectangle. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const Rectangle\&) | Draws the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const RectangleF\&) | Draws the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Draws the specified region of the specified image to the specified rectangle. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) | Draws the specified region of the specified image to the specified rectangle. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) | Draws the specified region of the specified image to the specified rectangle. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) | Draws the specified region of the specified image to the specified rectangle. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) | NOT IMPLEMENTED. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) | Draws the specified region of the specified image at the specified location. |
| [DrawImage](./drawimage/)(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) | Draws the specified region of the specified image at the specified location. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, int, int) | Draws the specified image using its original physical size at the specified location. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, int, int, int, int) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, const Rectangle\&) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](./drawimageunscaled/)(const SharedPtr\<Image\>\&, const Point\&) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const SharedPtr\<Image\>\&, Rectangle) | NOT IMPLEMENTED. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, Point, Point) | Draws the specified line using the specified pen. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, PointF, PointF) | Draws the specified line using the specified pen. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Draws the specified line using the specified pen. |
| [DrawLine](./drawline/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Draws the specified line using the specified pen. |
| [DrawLines](./drawlines/)(const SharedPtr\<Pen\>\&, const System::ArrayPtr\<System::Drawing::Point\>\&) | Draws a series of line segments using the specified pen. |
| [DrawLines](./drawlines/)(const SharedPtr\<Pen\>\&, const System::ArrayPtr\<System::Drawing::PointF\>\&) | Draws a series of line segments using the specified pen. |
| [DrawPath](./drawpath/)(const SharedPtr\<Pen\>\&, const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Draws the specified path using the specified pen. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) | Draws the specified pie using the specified pen on the surface represented by the current object. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) | Draws the specified pie using the specified pen on the surface represented by the current object. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, Rectangle, float, float) | Draws the specified pie using the specified pen on the surface represented by the current object. |
| [DrawPie](./drawpie/)(const SharedPtr\<Pen\>\&, RectangleF, float, float) | Draws the specified pie using the specified pen on the surface represented by the current object. |
| [DrawPolygon](./drawpolygon/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&) | Draws a polygon using the specified pen. |
| [DrawPolygon](./drawpolygon/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&) | Draws a polygon using the specified pen. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, int, int, int, int) | Draws the specified rectangle using the specified pen on the surface represented by the current object. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, float, float, float, float) | Draws the specified rectangle using the specified pen on the surface represented by the current object. |
| [DrawRectangle](./drawrectangle/)(const SharedPtr\<Pen\>\&, Rectangle) | Draws the specified rectangle using the specified pen on the surface represented by the current object. |
| [DrawRectangles](./drawrectangles/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<Rectangle\>\&) | Draws a series of rectangles using the specified pen. |
| [DrawRectangles](./drawrectangles/)(const SharedPtr\<Pen\>\&, const ArrayPtr\<RectangleF\>\&) | Draws a series of rectangles using the specified pen. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Draws the specified string at the specified location using the specified font and brush. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Draws the specified string in the specified rectangle using the specified font and brush. |
| [DrawString](./drawstring/)(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) | Draws the specified string at the specified location using the specified font and brush. |
| [EndContainer](./endcontainer/)(const SharedPtr\<Drawing2D::GraphicsContainer\>\&) | Closes the current container and restores the state of this object from the state of saved container. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<PointF\>\&, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<Point\>\&, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Point, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, PointF, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Rectangle, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, RectangleF, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Point, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, PointF, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, Rectangle, Rectangle, GraphicsUnit, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [EnumerateMetafile](./enumeratemetafile/)(const SharedPtr\<Imaging::Metafile\>\&, RectangleF, RectangleF, GraphicsUnit, Graphics::EnumerateMetafileProc) | NOT IMPLEMENTED. |
| [ExcludeClip](./excludeclip/)(Rectangle) | NOT IMPLEMENTED. |
| [ExcludeClip](./excludeclip/)(const SharedPtr\<Region\>\&) | NOT IMPLEMENTED. |
| [FillClosedCurve](./fillclosedcurve/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) | Draws a closed spline using the specified brush. |
| [FillClosedCurve](./fillclosedcurve/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) | Draws a closed spline using the specified brush. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, Rectangle) | Fills the interior of the ellipse specified by the bounding rectangle using the specified brush. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, RectangleF) | Fills the interior of the ellipse specified by the bounding rectangle using the specified brush. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, int, int, int, int) | Fills the interior of the ellipse specified by the bounding rectangle using the specified brush. |
| [FillEllipse](./fillellipse/)(const SharedPtr\<Brush\>\&, float, float, float, float) | Fills the interior of the ellipse specified by the bounding rectangle using the specified brush. |
| [FillPath](./fillpath/)(const SharedPtr\<Brush\>\&, const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Fills the interiors of the specified path using the specified brush. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) | Fills the specified pie using the specified brush on the surface represented by the current object. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) | Fills the specified pie using the specified brush on the surface represented by the current object. |
| [FillPie](./fillpie/)(const SharedPtr\<Brush\>\&, Rectangle, float, float) | Fills the specified pie using the specified brush on the surface represented by the current object. |
| [FillPolygon](./fillpolygon/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) | Fills the interiors of the specified polygon using the specified brush. |
| [FillPolygon](./fillpolygon/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) | Fills the interiors of the specified polygon using the specified brush. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, float, float, float, float) | Fills the specified rectangle with the specified brush. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, int, int, int, int) | Fills the specified rectangle with the specified brush. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, Rectangle) | Fills the specified rectangle with the specified brush. |
| [FillRectangle](./fillrectangle/)(const SharedPtr\<Brush\>\&, RectangleF) | Fills the specified rectangle with the specified brush. |
| [FillRectangles](./fillrectangles/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<Rectangle\>\&) | Fills a series of rectangles using the specified brush. |
| [FillRectangles](./fillrectangles/)(const SharedPtr\<Brush\>\&, const ArrayPtr\<RectangleF\>\&) | Fills a series of rectangles using the specified brush. |
| [FillRegion](./fillregion/)(const SharedPtr\<Brush\>\&, const SharedPtr\<Region\>\&) | Fills the interiors of the specified region using the specified brush. |
| [Flush](./flush/)(Drawing2D::FlushIntention) | Triggers the immediate execution of all pending draw operations. |
| static [FromHwnd](./fromhwnd/)(IntPtr) | NOT IMPLEMENTED. |
| static [FromHwndInternal](./fromhwndinternal/)(IntPtr) | NOT IMPLEMENTED. |
| static [FromImage](./fromimage/)(const SharedPtr\<Image\>\&) | Creates a new [Graphics](./) object from the specified image. |
| [get_Clip](./get_clip/)() | Returns a [Region](../region/) object that represents a region that limits the drawing area of the drawing surface represented by the current [Graphics](./) object. |
| [get_ClipBounds](./get_clipbounds/)() const | Returns a rectangle that bounds the clipping area of the surface represented by the current object. |
| [get_CompositingMode](./get_compositingmode/)() | Returns a value that indicates how composited images are drawn on the surface represented by the current object. |
| [get_CompositingQuality](./get_compositingquality/)() | Returns a value that indicates the quality level used when compositing images. |
| [get_DpiX](./get_dpix/)() | Returns the horizontal resolution. |
| [get_DpiY](./get_dpiy/)() | Returns the vertical resolution. |
| [get_InterpolationMode](./get_interpolationmode/)() | Returns a value that indicates the interpolation mode associated with the current object. |
| [get_IsClipEmpty](./get_isclipempty/)() const | NOT IMPLEMENTED. |
| [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | NOT IMPLEMENTED. |
| [get_PageScale](./get_pagescale/)() const | Returns the scaling between world units and page units for the current [Graphics](./) object. |
| [get_PageUnit](./get_pageunit/)() const | Returns measurement units used for page coordinates on the surface represented by the current object. |
| [get_PixelOffsetMode](./get_pixeloffsetmode/)() | Returns a value that indicates how the pixels are offset during rendering on the surface represented by the current object. |
| [get_RenderingOrigin](./get_renderingorigin/)() const | Returns a [Point](../point/) object that represents the rendering origin of the current [Graphics](./) object for dithering and for hatch brushes. |
| [get_SmoothingMode](./get_smoothingmode/)() | Returns a value that indicates a soothing mode used during rendering on the surface represented by the current object. |
| [get_TextContrast](./get_textcontrast/)() const | NOT IMPLEMENTED. |
| [get_TextRenderingHint](./get_textrenderinghint/)() | Returns a value that indicates the quality of text rendering. |
| [get_Transform](./get_transform/)() | Returns the geometric world transformation for the current [Graphics](./) object. |
| [get_VisibleClipBounds](./get_visibleclipbounds/)() const | Returns the [RectangleF](../rectanglef/) object that represents a bounding rectangle of the visible clipping region of the current [Graphics](./) object. |
| [GetHdc](./gethdc/)() | NOT IMPLEMENTED. |
| [GetNearestColor](./getnearestcolor/)(Color) | NOT IMPLEMENTED. |
| [GetSkCanvas](./getskcanvas/)() const |  |
| [IntersectClip](./intersectclip/)(const System::SharedPtr\<Region\>\&) | Updates the clip region of this object to the intersection of the current clip and the specified clip. |
| [IntersectClip](./intersectclip/)(System::Drawing::RectangleF) | Updates the clip region of this object to the intersection of the current clip and the specified clip. |
| [IntersectClip](./intersectclip/)(System::Drawing::Rectangle) | Updates the clip region of this object to the intersection of the current clip and the specified clip. |
| [IsVisible](./isvisible/)(Point) | Determines whether the specified point is contained within the visible clip region of the current [Graphics](./) object. |
| [IsVisible](./isvisible/)(PointF) | NOT IMPLEMENTED. |
| [IsVisible](./isvisible/)(Rectangle) | NOT IMPLEMENTED. |
| [IsVisible](./isvisible/)(RectangleF) | NOT IMPLEMENTED. |
| [IsVisible](./isvisible/)(int32_t, int32_t) | NOT IMPLEMENTED. |
| [IsVisible](./isvisible/)(float, float) | NOT IMPLEMENTED. |
| [IsVisible](./isvisible/)(float, float, float, float) | NOT IMPLEMENTED. |
| [IsVisible](./isvisible/)(int32_t, int32_t, int32_t, int32_t) | NOT IMPLEMENTED. |
| [MeasureCharacterRanges](./measurecharacterranges/)(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) | Returns an array of regions each of which bounds character positions in the specified string. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const | Returns a size of the specified string when drawn in the specified font in the specified format. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const | Returns a size of the specified string when drawn in the specified font in the specified format. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const | NOT IMPLEMENTED. |
| [MeasureString](./measurestring/)(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const | Returns a size of the specified string when drawn in the specified font in the specified format. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplies the world transformation matrix of the current [Graphics](./) object by the specified matrix. |
| [ReleaseHdc](./releasehdc/)() | NOT IMPLEMENTED. |
| [ReleaseHdc](./releasehdc/)(IntPtr) | NOT IMPLEMENTED. |
| [ResetClip](./resetclip/)() | Resets the clip region for this graphics to an infinite region. |
| [ResetTransform](./resettransform/)() | Resets the world transformation matrix of the current object so that it becomes an identity matrix. |
| [Restore](./restore/)(const SharedPtr\<Drawing2D::GraphicsState\>\&) | Restores the state of this object from the saved state. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Applies the specified rotation to the world transformation matrix of the current [Graphics](./) object in the specified order. |
| [Save](./save/)() | Saves the current state of this object and returns the saved state. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Applies the specified scale vector to the world transformation matrix of the current object. |
| [set_Clip](./set_clip/)(const SharedPtr\<Region\>\&) | Sets a region that limits the drawing area of the drawing surface represented by the current. |
| [set_CompositingMode](./set_compositingmode/)(Drawing2D::CompositingMode) | Sets a value that specifies how composited images are drawn on the surface represented by the current object. |
| [set_CompositingQuality](./set_compositingquality/)(Drawing2D::CompositingQuality) | Sets a value that specifies the quality level to use when compositing images. |
| [set_InterpolationMode](./set_interpolationmode/)(Drawing2D::InterpolationMode) | Sets a value that indicates the interpolation mode associated with the current object. |
| [set_PageScale](./set_pagescale/)(float) | Sets the scaling between world units and page units for the current [Graphics](./) object. |
| [set_PageUnit](./set_pageunit/)(GraphicsUnit) | Sets measurement units used for page coordinates on the surface represented by the current object. |
| [set_PixelOffsetMode](./set_pixeloffsetmode/)(Drawing2D::PixelOffsetMode) | Sets a value that specifies how the pixels should be offset during rendering on the surface represented by the current object. |
| [set_RenderingOrigin](./set_renderingorigin/)(Point) | Sets a [Point](../point/) object that specifies the rendering origin of the current [Graphics](./) object for dithering and for hatch brushes. |
| [set_SmoothingMode](./set_smoothingmode/)(Drawing2D::SmoothingMode) | Sets a value that specifies a soothing mode used during rendering on the surface represented by the current object. |
| [set_TextContrast](./set_textcontrast/)(int32_t) | NOT IMPLEMENTED. |
| [set_TextRenderingHint](./set_textrenderinghint/)(Text::TextRenderingHint) | Sets a value that specifies the quality of text rendering. |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Sets the geometric world transformation for the current [Graphics](./) object. |
| [SetClip](./setclip/)(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) | Sets the clipping region of drawing surface represented by the current [Graphics](./) object to the result of the specified operation that combines the current clip region and the specified region. |
| [SetClip](./setclip/)(Rectangle, Drawing2D::CombineMode) | Sets the clipping region of drawing surface represented by the current [Graphics](./) object to the result of the specified operation that combines the current clip region and the specified region. |
| [SetClip](./setclip/)(RectangleF, Drawing2D::CombineMode) | Sets the clipping region of drawing surface represented by the current [Graphics](./) object to the result of the specified operation that combines the current clip region and the specified region. |
| [SetClip](./setclip/)(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) | NOT IMPLEMENTED. |
| [SetClip](./setclip/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) | Sets the clipping region of drawing surface represented by the current [Graphics](./) object to the result of the specified operation that combines the current clip region and the region specified by a graphics path. |
| [TransformPoints](./transformpoints/)(Drawing2D::CoordinateSpace, Drawing2D::CoordinateSpace, const ArrayPtr\<System::Drawing::Point\>\&) | NOT IMPLEMENTED. |
| [TransformPoints](./transformpoints/)(Drawing2D::CoordinateSpace, Drawing2D::CoordinateSpace, const ArrayPtr\<System::Drawing::PointF\>\&) | NOT IMPLEMENTED. |
| [TranslateClip](./translateclip/)(int, int) | NOT IMPLEMENTED. |
| [TranslateClip](./translateclip/)(float, float) | NOT IMPLEMENTED. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Applies the specified translation vector to the world transformation matrix of the current [Graphics](./) object. |
| [~Graphics](./~graphics/)() |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [DrawImageAbort](./drawimageabort/) | The type of a callback fuction object used as an argument for DrawImage method. |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | The type of a callback fuction object used as an argument for EnumerateMetafile method. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
