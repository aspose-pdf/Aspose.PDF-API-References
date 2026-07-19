---
title: "System::IO::File::Open метод"
linktitle: "Open"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::File::Open метод. Открывает указанный файл в заданном режиме для чтения и записи без совместного доступа в C++."
type: docs
weight: 1900
url: /ru/cpp/system.io/file/open/
---
## File::Open(const String\&, FileMode) method


Открывает указанный файл в указанном режиме для чтения и записи без общего доступа.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, который нужно открыть |
| режим | FileMode | Указывает режим, в котором открывать файл |

### ReturnValue

Объект [FileStream](../../filestream/), связанный с открытым файлом

## См. также

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::Open(const String\&, FileMode, FileAccess, FileShare) method


Открывает указанный файл в указанном режиме, с указанным типом доступа и параметром совместного использования.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | const String\& | Путь к файлу, который нужно открыть |
| режим | FileMode | Указывает режим, в котором открывать файл |
| доступ | FileAccess | Запрашиваемый тип доступа |
| share | FileShare | Тип доступа, который другие объекты [FileStream](../../filestream/) имеют к открытому файлу |

### ReturnValue

Объект [FileStream](../../filestream/), связанный с открытым файлом

## См. также

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
