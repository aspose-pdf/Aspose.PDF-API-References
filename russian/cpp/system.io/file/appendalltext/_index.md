---
title: "System::IO::File::AppendAllText метод"
linktitle: "AppendAllText"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::AppendAllText метод. Добавляет указанную строку в указанный файл, используя указанную кодировку в C++."
type: docs
weight: 200
url: /ru/cpp/system.io/file/appendalltext/
---
## File::AppendAllText method


Добавляет указанную строку в указанный файл, используя указанную кодировку.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, в который следует добавить строку |
| contents | const String\& | Строка для записи в файл |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

## См. также

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
