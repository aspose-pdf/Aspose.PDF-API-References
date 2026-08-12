---
title: "System::IO::File::WriteAllText метод"
linktitle: "WriteAllText"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::WriteAllText метод. Создаёт новый текстовый файл или перезаписывает существующий и записывает в него содержимое указанной строки, используя указанную кодировку, в C++."
type: docs
weight: 3700
url: /ru/cpp/system.io/file/writealltext/
---
## File::WriteAllText method


Создает новый текстовый файл или перезаписывает существующий и записывает содержимое указанной строки в него, используя указанную кодировку.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Файл для создания или перезаписи |
| contents | const String\& | Массив строк |
| encoding | const EncodingPtr\& | Кодировка символов, которую следует использовать |

## См. также

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
