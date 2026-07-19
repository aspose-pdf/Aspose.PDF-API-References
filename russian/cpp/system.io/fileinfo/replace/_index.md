---
title: "System::IO::FileInfo::Replace метод"
linktitle: "Заменить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::FileInfo::Replace метод. Заменяет содержимое указанного файла назначения файлом, представленным текущим объектом FileInfo, и создаёт резервную копию заменённого файла в C++."
type: docs
weight: 2000
url: /ru/cpp/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) method


Заменяет содержимое указанного файла назначения файлом, представленным текущим объектом [FileInfo](../), и создаёт резервную копию заменённого файла.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationFileName | const String\& | Имя файла для замены |
| destinationBackupFileName | const String\& | Имя резервного файла |

### ReturnValue

Объект FileInfor, представляющий файл, на который указывает **destinationFileName**

## См. также

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Replace(const String\&, const String\&, bool) method


Заменяет содержимое указанного файла назначения файлом, представленным текущим объектом [FileInfo](../), и создаёт резервную копию заменённого файла.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationFileName | const String\& | Имя файла для замены |
| destinationBackupFileName | const String\& | Имя резервного файла |
| ignoreMetadataErrors | bool | Указывает, следует ли игнорировать ошибки слияния из заменённого файла в файл‑замену (true) или нет (false) |

### ReturnValue

Объект FileInfor, представляющий файл, на который указывает **destinationFileName**

## См. также

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
