---
title: "Метод System::Drawing::Graphics::SetClip"
linktitle: "SetClip"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Drawing::Graphics::SetClip. Устанавливает область отсечения поверхности рисования, представленной текущим объектом Graphics, в результат указанной операции, которая комбинирует текущую область отсечения и область, заданную графическим путем, в C++."
type: docs
weight: 8600
url: /ru/cpp/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая комбинирует текущую область отсечения и область, заданную графическим путем.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const SharedPtr\<Drawing2D::GraphicsPath\>\& | Указывает область для объединения |
| combineMode | Drawing2D::CombineMode | Указывает операцию объединения |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и указанную область.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| регион | const SharedPtr\<Region\>\& | Указывает область для объединения |
| combineMode | Drawing2D::CombineMode | Указывает операцию объединения |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и указанную область.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Указывает область для объединения |
| combineMode | Drawing2D::CombineMode | Указывает операцию объединения |

## См. также

* Class [Rectangle](../../rectangle/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и указанную область.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Указывает область для объединения |
| combineMode | Drawing2D::CombineMode | Указывает операцию объединения |

## См. также

* Class [RectangleF](../../rectanglef/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
