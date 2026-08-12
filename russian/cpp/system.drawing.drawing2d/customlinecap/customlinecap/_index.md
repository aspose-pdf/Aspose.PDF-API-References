---
title: "System::Drawing::Drawing2D::CustomLineCap::CustomLineCap конструктор"
linktitle: "CustomLineCap"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::CustomLineCap::CustomLineCap конструктор. Создаёт новый экземпляр класса CustomLineCap, представляющего пользовательскую окончание линии с указанными свойствами в C++."
type: docs
weight: 100
url: /ru/cpp/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap constructor


Создаёт новый экземпляр класса [CustomLineCap](../), представляющего пользовательскую окончание линии с указанными свойствами.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | const SharedPtr\<GraphicsPath\>\& | Указывает заливку для пользовательского окончания |
| strokePath | const SharedPtr\<GraphicsPath\>\& | Указывает контур пользовательского окончания |
| baseCap | LineCap | Базовое окончание линии, из которого создаётся пользовательское окончание |
| baseInset | float | Указывает расстояние между линией и окончанием |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Enum [LineCap](../../linecap/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
