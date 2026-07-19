---
title: "System::ObjectExt::UnknownIsNull метод"
linktitle: "UnknownIsNull"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ObjectExt::UnknownIsNull метод. Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для не скалярных типов в C++."
type: docs
weight: 1800
url: /ru/cpp/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) method


Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для не‑скалярных типов.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | [Object](../../object/) для проверки. |

### ReturnValue

Истина, если 'obj == nullptr' истинно, иначе ложь.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownIsNull(T) method


Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для скалярных типов.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | [Object](../../object/) для проверки. |

### ReturnValue

Всегда возвращает false.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
