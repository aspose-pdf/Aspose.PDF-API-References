---
title: "Метод System::BuildArray"
linktitle: "BuildArray"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::BuildArray. Создаёт массив в C++."
type: docs
weight: 15600
url: /ru/cpp/system/buildarray/
---
## System::BuildArray method


Создать массив.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива, который нужно создать |

### ReturnValue

ObjectBuilder, настроенный для построения массива
## Примечания



Создаёт [ArrayPtr<T>](../arrayptr/) и возвращает построитель для него
[Object](../object/) construction must be finished with [Get()](../get/) call 

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
