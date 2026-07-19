---
title: "System::IO::FileInfo::CopyTo метод"
linktitle: "CopyTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::FileInfo::CopyTo метод. Копирует файл, представленный текущим объектом, в указанное место. Если файл назначения уже существует, копирование завершается с ошибкой в C++."
type: docs
weight: 300
url: /ru/cpp/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) method


Копирует файл, представленный текущим объектом, в указанное место. Если файл назначения уже существует, копирование завершается с ошибкой.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| destFileName | const String\& | Имя файла назначения |

### ReturnValue

Объект [FileInfo](../) , представляющий копию

## См. также

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::CopyTo(const String\&, bool) method


Копирует файл, представленный текущим объектом, в указанное место. Параметр указывает, следует ли перезаписать существующий файл назначения.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| destFileName | const String\& | Имя файла назначения |
| перезаписать | bool | True, если существующий файл назначения должен быть перезаписан; false, если копирование должно завершиться ошибкой, если файл назначения уже существует |

### ReturnValue

Объект [FileInfo](../) , представляющий копию

## См. также

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
