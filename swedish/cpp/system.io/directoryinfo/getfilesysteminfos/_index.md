---
title: "System::IO::DirectoryInfo::GetFileSystemInfos metod"
linktitle: "GetFileSystemInfos"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::DirectoryInfo::GetFileSystemInfos metod. Returnerar en array som innehåller delade pekare till FileSystemInfo-objekt som representerar alla filer och kataloger som finns i den katalog som representeras av det aktuella objektet i C++."
type: docs
weight: 1400
url: /sv/cpp/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method


Returnerar en array som innehåller delade pekare till [FileSystemInfo](../../filesysteminfo/) objekt som representerar alla filer och kataloger som finns i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&) method


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för filerna och katalogerna att söka efter |

### ReturnValue

En array av delade pekare till [FileSystemInfo](../../filesysteminfo/) objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för filerna och katalogerna att söka efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den katalog som det aktuella objektet representerar eller i hela katalogträdet med den katalogen som rot |

### ReturnValue

En array av delade pekare till [FileSystemInfo](../../filesysteminfo/) objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
