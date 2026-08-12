---
title: "System::Drawing::Graphics::DrawString metod"
linktitle: "DrawString"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Graphics::DrawString metod. Ritar den angivna strängen på den specificerade platsen med det angivna teckensnittet och penseln i C++."
type: docs
weight: 2800
url: /sv/cpp/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Ritar den angivna strängen på den angivna platsen med det angivna teckensnittet och penseln.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Strängen att rita |
| teckensnitt | const SharedPtr\<Font\>\& | Ett teckensnitt att använda |
| brush | const SharedPtr\<Brush\>\& | Ett [Brush](../../brush/) objekt att använda för ritning |
| x | float | X-koordinaten för platsen för det övre vänstra hörnet av den ritade strängen |
| y | float | Y-koordinaten för platsen för det övre vänstra hörnet av den ritade strängen |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Angav formatet för strängen |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Ritar den angivna strängen på den angivna platsen med det angivna teckensnittet och penseln.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Strängen att rita |
| teckensnitt | const SharedPtr\<Font\>\& | Ett teckensnitt att använda |
| brush | const SharedPtr\<Brush\>\& | Ett [Brush](../../brush/) objekt att använda för ritning |
| topLeft | PointF | Anger platsen för det övre vänstra hörnet av den ritade strängen |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Angav formatet för strängen |

## Se även

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


Ritar den angivna strängen i den angivna rektangeln med det angivna teckensnittet och penseln.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | Strängen att rita |
| teckensnitt | const SharedPtr\<Font\>\& | Ett teckensnitt att använda |
| brush | const SharedPtr\<Brush\>\& | Ett [Brush](../../brush/) objekt att använda för ritning |
| layoutRectangle | RectangleF | Anger en rektangel att rita strängen i |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Angav formatet för strängen |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
