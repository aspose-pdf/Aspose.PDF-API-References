---
title: "System::IO::DirectoryInfo::GetFiles metod"
linktitle: "GetFiles"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::DirectoryInfo::GetFiles metod. Returnerar en array som innehåller delade pekare till FileInfo-objekt som representerar alla kataloger som finns i den katalog som representeras av det aktuella objektet i C++."
type: docs
weight: 1300
url: /sv/cpp/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Returnerar en array som innehåller delade pekare till [FileInfo](../../fileinfo/) objekt som representerar alla kataloger som finns i den katalog som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&) method


Söker efter filerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för de filer som ska sökas efter |

### ReturnValue

En array av delade pekare till [FileInfo](../../fileinfo/) objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Söker efter filerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchPattern | const String\& | Namnmönstret för de filer som ska sökas efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den katalog som det aktuella objektet representerar eller i hela katalogträdet med den katalogen som rot |

### ReturnValue

En array av delade pekare till [FileInfo](../../fileinfo/) objekt som representerar de hittade filerna vars namn matchar **searchPattern**

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
