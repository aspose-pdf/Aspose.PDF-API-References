---
title: System::Drawing::Graphics::DrawString method
linktitle: DrawString
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::DrawString method. Draws the specified string at the specified location using the specified font and brush in C++.'
type: docs
weight: 2800
url: /cpp/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Draws the specified string at the specified location using the specified font and brush.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | The string to draw |
| font | const SharedPtr\<Font\>\& | A font to use |
| brush | const SharedPtr\<Brush\>\& | A [Brush](../../brush/) object to use for drawing |
| x | float | The X coordinate of the location of the upper left corner of the drawn string |
| y | float | The Y coordinate of the location of the upper left corner of the drawn string |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Specified the format of the string |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Draws the specified string at the specified location using the specified font and brush.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | The string to draw |
| font | const SharedPtr\<Font\>\& | A font to use |
| brush | const SharedPtr\<Brush\>\& | A [Brush](../../brush/) object to use for drawing |
| topLeft | PointF | Specifies the location of the upper left corner of the drawn string |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Specified the format of the string |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Draws the specified string in the specified rectangle using the specified font and brush.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | The string to draw |
| font | const SharedPtr\<Font\>\& | A font to use |
| brush | const SharedPtr\<Brush\>\& | A [Brush](../../brush/) object to use for drawing |
| layoutRectangle | RectangleF | Specifies a rectangle to draw the string in |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Specified the format of the string |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
