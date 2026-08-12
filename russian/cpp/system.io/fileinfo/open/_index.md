---
title: "System::IO::FileInfo::Open метод"
linktitle: "Open"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::FileInfo::Open метод. Открывает файл, представленный текущим объектом, в указанном режиме для чтения и записи без совместного доступа в C++."
type: docs
weight: 1600
url: /ru/cpp/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) method


Открывает файл, представленный текущим объектом, в указанном режиме для чтения и записи без совместного доступа.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | FileMode | Указывает режим, в котором открывать файл |

### ReturnValue

Объект [FileStream](../../filestream/) , связанный с файлом, представляемым текущим объектом

## См. также

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess) method


Открывает файл, представленный текущим объектом, в указанном режиме, с указанным типом доступа и без совместного доступа.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | FileMode | Указывает режим, в котором открывать файл |
| доступ | FileAccess | Запрашиваемый тип доступа |

### ReturnValue

Объект [FileStream](../../filestream/) , связанный с файлом, представляемым текущим объектом

## См. также

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess, FileShare) method


Открывает файл, представленный текущим объектом, в указанном режиме, с указанным типом доступа и параметром совместного доступа.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | FileMode | Указывает режим, в котором открывать файл |
| доступ | FileAccess | Запрашиваемый тип доступа |
| share | FileShare | Тип доступа, который другие объекты [FileStream](../../filestream/) имеют к открытому файлу |

### ReturnValue

Объект [FileStream](../../filestream/) , связанный с файлом, представляемым текущим объектом

## См. также

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
