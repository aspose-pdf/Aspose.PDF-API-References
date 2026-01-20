---
title: System::Drawing::Font::GetHeight method
linktitle: GetHeight
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Font::GetHeight method. Returns the line spacing of the font represented by the current object, in the current unit of a specified Graphics object in C++.'
type: docs
weight: 1900
url: /cpp/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) method


Returns the line spacing of the font represented by the current object, in the current unit of a specified [Graphics](../../graphics/) object.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


| Parameter | Type | Description |
| --- | --- | --- |
| graphics | const SharedPtr\<Graphics\>\& | A [Graphics](../../graphics/) object that specifies the measurement units |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../../graphics/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Font::GetHeight(float) method


Returns the height of the font represented by the current object when drawn to a display device with the specified vertical resolution.

```cpp
float System::Drawing::Font::GetHeight(float dpi=96.f)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dpi | float | The vertical resolution of the display device |

### ReturnValue

The hegiht of the font in pixels

## See Also

* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
