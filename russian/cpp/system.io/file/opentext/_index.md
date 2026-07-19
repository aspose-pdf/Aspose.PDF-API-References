---
title: "System::IO::File::OpenText метод"
linktitle: "OpenText"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::OpenText метод. Открывает указанный существующий файл для чтения текста с использованием кодировки UTF-8 без совместного доступа в C++."
type: docs
weight: 2100
url: /ru/cpp/system.io/file/opentext/
---
## File::OpenText method


Открывает указанный существующий файл для чтения текста с использованием кодировки UTF-8 без общего доступа.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, который нужно открыть |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

### ReturnValue

Умный указатель на объект [StreamWriter](../../streamwriter/), связанный с открытым файлом

## См. также

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
