---
title: "System::Drawing::Region::Equals метод"
linktitle: "Equals"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Region::Equals метод. Определяет, является ли указанная область идентичной области, представленной текущим объектом, на указанной поверхности рисования в C++."
type: docs
weight: 600
url: /ru/cpp/system.drawing/region/equals/
---
## Region::Equals method


Определяет, идентичен ли указанный регион региону, представленному текущим объектом, на указанной поверхности рисования.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| r | const SharedPtr\<Region\>\& | Область, с которой сравнивается данная область |
| g | const SharedPtr\<Graphics\>\& | Поверхность рисования |

### ReturnValue

True, если внутренность указанной области идентична внутренности области, представленной текущим объектом, когда применяется преобразование, связанное с параметром **g**; иначе — false

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Class [Region](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
