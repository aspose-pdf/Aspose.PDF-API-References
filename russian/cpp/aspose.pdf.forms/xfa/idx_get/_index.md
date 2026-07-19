---
title: "Aspose::Pdf::Forms::XFA::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::XFA::idx_get метод. Получает или задает значение узла данных по пути в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.forms/xfa/idx_get/
---
## XFA::idx_get method


Получает или задаёт значение узла данных согласно *path*.

```cpp
System::String Aspose::Pdf::Forms::XFA::idx_get(const System::String &path)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const System::String\& | Путь к узлу данных, например form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Обязательно указывайте индексы, даже если данные содержат только единственное вхождение каждого узла, т.е. пишите node1[0].node2[0]... вместо node1.node2... |

### ReturnValue

Значение узла данных.

## См. также

* Class [String](../../../system/string/)
* Class [XFA](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
