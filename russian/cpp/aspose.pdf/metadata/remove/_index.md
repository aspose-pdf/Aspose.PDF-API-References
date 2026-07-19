---
title: "Метод Aspose::Pdf::Metadata::Remove"
linktitle: "Remove"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Metadata::Remove. Удаляет пару ключ/значение из коллекции в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.pdf/metadata/remove/
---
## Metadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Удаляет пару ключ/значение из коллекции.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Пара ключ/значение, которую нужно удалить. |

### ReturnValue

true, если пара была найдена и удалена.

## См. также

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Remove(const System::String\&) method


Удаляет запись из метаданных.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::String &key) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const System::String\& | Ключ записи для удаления. |

### ReturnValue

True - если ключ удалён; иначе false.

## См. также

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
