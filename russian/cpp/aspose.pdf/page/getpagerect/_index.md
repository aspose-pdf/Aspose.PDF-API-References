---
title: "Aspose::Pdf::Page::GetPageRect метод"
linktitle: "GetPageRect"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Page::GetPageRect метод. Возвращает прямоугольник страницы согласно её CropBox (или MediaBox, если CropBox null) в C++."
type: docs
weight: 4500
url: /ru/cpp/aspose.pdf/page/getpagerect/
---
## Page::GetPageRect method


Возвращает прямоугольник страницы в соответствии с её CropBox (или MediaBox, если CropBox пуст).

```cpp
System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Page::GetPageRect(bool considerRotation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| considerRotation | bool | Если true, то вращение страницы будет учитываться при расчёте прямоугольника. |

### ReturnValue

[Rectangle](../../rectangle/) of the page.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
