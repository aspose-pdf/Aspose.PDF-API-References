---
title: "System::Drawing::Point::Add method"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Point::Add method. Добавляет значения ширины и высоты указанного объекта Size к значениям координат X и Y указанного объекта Point соответственно в C++."
type: docs
weight: 1500
url: /ru/cpp/system.drawing/point/add/
---
## Point::Add method


Добавляет значения ширины и высоты указанного объекта [Size](../../size/) к значениям координат X и Y указанного объекта [Point](../) соответственно.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const Point\& | Точка для трансляции |
| size | const Size\& | Объект [Size](../../size/), который задает значения для добавления к координатам **point** |

### ReturnValue

Новый объект [Point](../), у которого значение координаты X равно сумме значения координаты X **point** и значения ширины **size**, а значение координаты Y равно сумме значения координаты Y **point** и значения высоты **size**

## См. также

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
