---
title: "System::IO::File::ReadAllLines метод"
linktitle: "ReadAllLines"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::ReadAllLines метод. Считывает содержимое указанного текстового файла построчно в массив строк, используя указанную кодировку символов в C++."
type: docs
weight: 2400
url: /ru/cpp/system.io/file/readalllines/
---
## File::ReadAllLines method


Считывает содержимое указанного текстового файла построчно в массив строк, используя указанную кодировку символов.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу для чтения |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

### ReturnValue

Массив строк, каждый элемент которого представляет отдельную строку из указанного файла

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
