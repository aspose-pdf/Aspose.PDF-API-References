---
title: "System::IO::DirectoryInfo::EnumerateFiles‑metod"
linktitle: "EnumerateFiles"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::DirectoryInfo::EnumerateFiles‑metod. Returnerar en enumererbar samling som innehåller alla filer som finns i den katalog som det aktuella objektet representerar i C++."
type: docs
weight: 600
url: /sv/cpp/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() method


Returnerar en enumererbar samling som innehåller alla filer som finns i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&) method


Söker efter filerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för de filer som ska sökas efter |

### ReturnValue

Den enumererbara samlingen av delade pekare till [FileInfo](../../fileinfo/)‑objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) method


Söker efter filerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för de filer som ska sökas efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den katalog som det aktuella objektet representerar eller i hela katalogträdet med den katalogen som rot |

### ReturnValue

Den enumererbara samlingen av delade pekare till [FileInfo](../../fileinfo/)‑objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
