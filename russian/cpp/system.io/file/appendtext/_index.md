---
title: "System::IO::File::AppendText метод"
linktitle: "AppendText"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::AppendText метод. Создаёт объект StreamWriter, который добавляет текст в указанный файл, используя кодировку UTF-8. Если указанный файл не существует, он создаётся в C++."
type: docs
weight: 300
url: /ru/cpp/system.io/file/appendtext/
---
## File::AppendText method


Создаёт объект [StreamWriter](../../streamwriter/) который добавляет текст в указанный файл, используя кодировку UTF-8. Если указанный файл не существует, он создаётся.

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу для открытия или создания |

### ReturnValue

Умный указатель на созданный объект [StreamWriter](../../streamwriter/), связанный с указанным файлом

## См. также

* Typedef [StreamWriterPtr](../../../system/streamwriterptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
