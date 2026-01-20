---
title: System::Drawing::Graphics::MeasureString method
linktitle: MeasureString
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::MeasureString method. Returns a size of the specified string when drawn in the specified font in the specified format in C++.'
type: docs
weight: 6500
url: /cpp/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method


Returns a size of the specified string when drawn in the specified font in the specified format.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | String const\& | The string whose size to calculate |
| font | System::SharedPtr\<Font\> const\& | The font used to draw the string |
| width | int | The maximum width of the string |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Specifies the string format |

### ReturnValue

A [SizeF](../../sizef/) object that represents the size of the string in the measurment units specified by the PageUnit property of the current Grapphics object.

## See Also

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Returns a size of the specified string when drawn in the specified font in the specified format.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | String const\& | The string whose size to calculate |
| font | System::SharedPtr\<Font\> const\& | The font used to draw the string |
| origin | PointF const\& | Specifies the location of the upper left corner of the string |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Specifies the string format |

### ReturnValue

A [SizeF](../../sizef/) object that represents the size of the string in the measurment units specified by the PageUnit property of the current Grapphics object.

## See Also

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method


NOT IMPLEMENTED.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## See Also

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Returns a size of the specified string when drawn in the specified font in the specified format.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | String const\& | The string whose size to calculate |
| font | System::SharedPtr\<Font\> const\& | The font used to draw the string |
| layoutArea | SizeF const\& | The maximum layout area of the string |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Specifies the string format |

### ReturnValue

A [SizeF](../../sizef/) object that represents the size of the string in the measurment units specified by the PageUnit property of the current Grapphics object.

## See Also

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
