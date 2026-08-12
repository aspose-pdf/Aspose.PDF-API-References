---
title: "System::IO::File::Create метод"
linktitle: "Создать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::Create метод. Создаёт новый файл (или перезаписывает существующий) и открывает его для чтения и записи, используя указанный размер буфера и параметры в C++."
type: docs
weight: 500
url: /ru/cpp/system.io/file/create/
---
## File::Create method


Создаёт новый файл (или перезаписывает существующий) и открывает его для чтения и записи, используя указанный размер буфера и параметры.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу для создания или перезаписи |
| bufferSize | int32_t | Количество байтов, буферизуемых при чтении из файла и записи в файл |
| опции | FileOptions | Указывает, как создать или перезаписать файл |

### ReturnValue

Умный указатель на объект [FileStream](../../filestream/), связанный с указанным файлом

## См. также

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileOptions](../../fileoptions/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
