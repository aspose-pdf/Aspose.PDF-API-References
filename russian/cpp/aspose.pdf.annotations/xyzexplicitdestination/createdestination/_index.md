---
title: "Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination метод"
linktitle: "CreateDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination метод. Создаёт назначение в указанное место страницы с учётом вращения страницы, если требуется, в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.annotations/xyzexplicitdestination/createdestination/
---
## XYZExplicitDestination::CreateDestination method


Создайте пункт назначения в указанное место страницы, учитывая поворот страницы, если требуется.

```cpp
static System::SharedPtr<XYZExplicitDestination> Aspose::Pdf::Annotations::XYZExplicitDestination::CreateDestination(const System::SharedPtr<Aspose::Pdf::Page> &page, double left, double top, double zoom, bool considerRotation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница назначения. |
| left | double | [Left](../../../aspose.pdf/left/) позиция на странице. |
| верх | double | Верхняя позиция на странице. |
| масштаб | double | Коэффициент масштабирования (0 — по умолчанию). |
| considerRotation | bool | Если true, позиция будет пересчитана с учётом вращения страницы. |

### ReturnValue

Объект назначения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XYZExplicitDestination](../)
* Class [Page](../../../aspose.pdf/page/)
* Class [XYZExplicitDestination](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
