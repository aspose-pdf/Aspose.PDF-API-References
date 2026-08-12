---
title: "System::IO::File::ReadLines метод"
linktitle: "ReadLines"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::ReadLines метод. Считывает содержимое указанного текстового файла построчно, используя указанную кодировку символов, и возвращает перечисляемую коллекцию строк, каждая из которых представляет отдельную строку содержимого файла в C++."
type: docs
weight: 2600
url: /ru/cpp/system.io/file/readlines/
---
## File::ReadLines method


Считывает содержимое указанного текстового файла построчно, используя указанную кодировку символов, и возвращает перечисляемую коллекцию строк, каждая из которых представляет отдельную строку содержимого файла.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу для чтения |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

### ReturnValue

Перечисляемая коллекция строк, представляющая содержимое указанного файла

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
