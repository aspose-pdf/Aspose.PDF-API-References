---
title: "Метод Aspose::Pdf::Metadata::Contains"
linktitle: "Contains"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Metadata::Contains. Проверяет, содержится ли указанная пара ключ‑значение в словаре в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf/metadata/contains/
---
## Metadata::Contains(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const method


Проверяет, содержится ли указанная пара ключ‑значение в словаре.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) const override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Пара ключ‑значение. |

### ReturnValue

true, если этот pauir найден.

## См. также

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Contains(const System::String\&) const method


Проверяет, содержится ли ключ в метаданных.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::String &key) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const System::String\& | Ключ записи для поиска. |

### ReturnValue

True, если ключ содержится в метаданных.

## См. также

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
