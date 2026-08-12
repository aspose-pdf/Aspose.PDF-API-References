---
title: "System::IO::File::Replace метод"
linktitle: "Заменить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::Replace метод. Заменяет содержимое одного файла другим и создаёт резервную копию заменённого файла в C++."
type: docs
weight: 2700
url: /ru/cpp/system.io/file/replace/
---
## File::Replace method


Заменяет содержимое одного файла другим и создает резервную копию заменённого файла.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=true)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFileName | const String\& | Имя файла, которым будет заменён |
| destinationFileName | const String\& | Имя файла для замены |
| destinationBackupFileName | const String\& | Имя резервного файла |
| ignoreMetadataErrors | bool | Указывает, следует ли игнорировать ошибки слияния из заменённого файла в файл‑замену (true) или нет (false) |

## См. также

* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
