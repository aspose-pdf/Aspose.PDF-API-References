---
title: "System::IO::DirectoryInfo::EnumerateFileSystemInfos metod"
linktitle: "EnumerateFileSystemInfos"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::DirectoryInfo::EnumerateFileSystemInfos metod. Returnerar en enumererbar samling som innehåller alla filer och kataloger som finns i katalogen som representeras av det aktuella objektet i C++."
type: docs
weight: 700
url: /sv/cpp/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Returnerar en enumererbar samling som innehåller alla filer och kataloger som finns i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för filerna och katalogerna att söka efter |

### ReturnValue

Den enumererbara samlingen av delade pekare till [FileSystemInfo](../../filesysteminfo/) objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för filerna och katalogerna att söka efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den katalog som det aktuella objektet representerar eller i hela katalogträdet med den katalogen som rot |

### ReturnValue

Den enumererbara samlingen av delade pekare till [FileSystemInfo](../../filesysteminfo/) objekt som representerar de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
