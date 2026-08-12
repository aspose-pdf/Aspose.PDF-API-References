---
title: "System::ObjectExt::UnboxToNullable метод"
linktitle: "UnboxToNullable"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ObjectExt::UnboxToNullable метод. Разупаковывает объект в тип, допускающий null, в C++."
type: docs
weight: 1700
url: /ru/cpp/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable method


Разупаковывает объект в тип, допускающий null.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=true)
```


| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) для разупаковки. |
| безопасно | bool | Если true, возвращает nullptr при ошибке, иначе бросает InvalidCastException. |

### ReturnValue

Разупакованное nullable значение (может быть null).

## См. также

* Class [Nullable](../../nullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
