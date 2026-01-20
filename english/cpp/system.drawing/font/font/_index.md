---
title: System::Drawing::Font::Font constructor
linktitle: Font
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Font::Font constructor. Constructs a new instance of Font class that represents the specified existing font with the specified font style in C++.'
type: docs
weight: 100
url: /cpp/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Constructs a new instance of [Font](../) class that represents the specified existing font with the specified font style.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


| Parameter | Type | Description |
| --- | --- | --- |
| prototype | const SharedPtr\<Font\>\& | The existing font to create the new one from |
| new_style | FontStyle | A font style to apply to the new font |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontStyle](../../fontstyle/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| family | const SharedPtr\<FontFamily\>\& | The font family of the new font |
| em_size | float | The em size of the new font in the units specified by **unit** parameter |
| style | FontStyle | The style of the new font |
| unit | GraphicsUnit | The measurement units of the new font |
| gdi_charset | uint8_t | A GDI charset to be used for the new font |
| gdi_vertical_font | bool | True if the new font is derived from a GDI vertical font |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Parameter | Type | Description |
| --- | --- | --- |
| family | const SharedPtr\<FontFamily\>\& | The font family of the new font |
| em_size | float | The em size of the new font in the units specified by **unit** parameter |
| unit | GraphicsUnit | The measurement units of the new font |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontFamily](../../fontfamily/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const String\& | The name of the new font's font family |
| em_size | float | The em size of the new font in the units specified by **unit** parameter |
| style | FontStyle | The style of the new font |
| unit | GraphicsUnit | The measurement units of the new font |
| gdi_charset | uint8_t | A GDI charset to be used for the new font |
| gdi_vertical_font | bool | True if the new font is derived from a GDI vertical font |

## See Also

* Class [String](../../../system/string/)
* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::Font(const String\&, float, GraphicsUnit) constructor


Constructs a new instance of [Font](../) class.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const String\& | The name of the new font's font family |
| em_size | float | The em size of the new font in the units specified by **unit** parameter |
| unit | GraphicsUnit | The measurement units of the new font |

## See Also

* Class [String](../../../system/string/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
