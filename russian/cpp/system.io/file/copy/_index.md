---
title: "System::IO::File::Copy method"
linktitle: "Copy"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::Copy method. Копирует указанный файл в указанное место. Если файл назначения уже существует, параметр указывает, следует ли перезаписать его в C++."
type: docs
weight: 400
url: /ru/cpp/system.io/file/copy/
---
## File::Copy method


Копирует указанный файл в указанное место. Если файл назначения уже существует, параметр указывает, следует ли его перезаписать.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFileName | const String\& | Путь к файлу, который нужно скопировать |
| destFileName | const String\& | Путь к новому расположению копируемого файла |
| перезаписать | bool | True, если существующий файл назначения должен быть перезаписан; false, если копирование должно завершиться ошибкой, если файл назначения уже существует |

## См. также

* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
