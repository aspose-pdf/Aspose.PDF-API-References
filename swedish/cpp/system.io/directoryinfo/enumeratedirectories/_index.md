---
title: "System::IO::DirectoryInfo::EnumerateDirectories metod"
linktitle: "EnumerateDirectories"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::DirectoryInfo::EnumerateDirectories metod. Returnerar en enumererbar samling som innehåller alla kataloger som finns i den katalog som representeras av det aktuella objektet i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() method


Returnerar en enumererbar samling som innehåller alla kataloger som finns i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&) method


Söker efter katalogerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för de kataloger som ska sökas efter |

### ReturnValue

Den enumererbara samlingen av delade pekare till [DirectoryInfo](../) objekt som representerar de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) method


Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för de kataloger som ska sökas efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den katalog som det aktuella objektet representerar eller i hela katalogträdet med den katalogen som rot |

### ReturnValue

Den enumererbara samlingen av delade pekare till [DirectoryInfo](../) objekt som representerar de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
