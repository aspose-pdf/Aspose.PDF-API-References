---
title: "Метод System::Uri::MakeRelativeUri"
linktitle: "MakeRelativeUri"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Uri::MakeRelativeUri. Определяет разницу между URI, представленными текущим и указанным объектами Uri, в C++."
type: docs
weight: 3100
url: /ru/cpp/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri method


Определяет разницу между URI, представленными текущим и указанным объектами [Uri](../).

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const SharedPtr\<Uri\>\& | Сравниваемое значение |

### ReturnValue

Если имя хоста и схема URI, представленных текущим объектом и **toUri**, одинаковы, то этот метод возвращает относительный [Uri](../), который при добавлении к текущему экземпляру URI дает **toUri**. Если имя хоста или схема различаются, метод возвращает объект [Uri](../), представляющий параметр **uri**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
