---
title: "System::Drawing::Graphics::SetClip metod"
linktitle: "SetClip"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Graphics::SetClip metod. Ställer in beskärningsområdet för ritytan som representeras av det aktuella Graphics‑objektet till resultatet av den angivna operationen som kombinerar det aktuella beskärningsområdet och det område som anges av en grafikbana i C++."
type: docs
weight: 8600
url: /sv/cpp/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


Ställer in beskärningsområdet för ritytan som representeras av det aktuella [Graphics](../) objektet till resultatet av den angivna operationen som kombinerar det aktuella beskärningsområdet och området som specificeras av en grafikbana.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const SharedPtr\<Drawing2D::GraphicsPath\>\& | Anger ett område att kombinera |
| combineMode | Drawing2D::CombineMode | Anger kombineringsoperationen |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


INTE IMPLEMENTERAD.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


Ställer in beskärningsområdet för ritytan som representeras av det aktuella [Graphics](../) objektet till resultatet av den angivna operationen som kombinerar det aktuella beskärningsområdet och det specificerade området.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | const SharedPtr\<Region\>\& | Anger ett område att kombinera |
| combineMode | Drawing2D::CombineMode | Anger kombineringsoperationen |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


Ställer in beskärningsområdet för ritytan som representeras av det aktuella [Graphics](../) objektet till resultatet av den angivna operationen som kombinerar det aktuella beskärningsområdet och det specificerade området.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Anger ett område att kombinera |
| combineMode | Drawing2D::CombineMode | Anger kombineringsoperationen |

## Se även

* Class [Rectangle](../../rectangle/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


Ställer in beskärningsområdet för ritytan som representeras av det aktuella [Graphics](../) objektet till resultatet av den angivna operationen som kombinerar det aktuella beskärningsområdet och det specificerade området.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | RectangleF | Anger ett område att kombinera |
| combineMode | Drawing2D::CombineMode | Anger kombineringsoperationen |

## Se även

* Class [RectangleF](../../rectanglef/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
