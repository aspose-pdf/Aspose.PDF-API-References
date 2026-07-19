---
title: "Метод Aspose::Pdf::Page::IsBlank"
linktitle: "IsBlank"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Page::IsBlank. Получает флаг, указывающий, является ли страница пустой, в C++."
type: docs
weight: 4800
url: /ru/cpp/aspose.pdf/page/isblank/
---
## Page::IsBlank method


Получает флаг, указывающий, является ли страница пустой.

```cpp
bool Aspose::Pdf::Page::IsBlank(double fillThresholdFactor)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fillThresholdFactor | double | Значение порога заполнения, управляющее чувствительностью обнаружения. Должно находиться в диапазоне [0..1). |

### ReturnValue

True — если страница пустая; иначе — false.
## Примечания



Чтобы определить, пустая ли страница, вычисляется отношение заполненного пространства к общему пространству страницы. Это отношение сравнивается с параметром fillThresholdFactor, и если оно меньше, страница считается пустой.
## См. также

* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
