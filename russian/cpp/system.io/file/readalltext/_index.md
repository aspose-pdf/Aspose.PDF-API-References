---
title: "System::IO::File::ReadAllText метод"
linktitle: "ReadAllText"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::ReadAllText метод. Считывает содержимое указанного текстового файла в один объект String, используя заданную кодировку символов, в C++."
type: docs
weight: 2500
url: /ru/cpp/system.io/file/readalltext/
---
## File::ReadAllText method


Считывает содержимое указанного текстового файла в один объект [String](../../../system/string/), используя заданную кодировку символов.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу для чтения |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

### ReturnValue

Строка, содержащая содержимое указанного файла

## См. также

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
