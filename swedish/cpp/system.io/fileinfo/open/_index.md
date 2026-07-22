---
title: "System::IO::FileInfo::Open‑metod"
linktitle: "Open"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileInfo::Open‑metod. Öppnar filen som representeras av det aktuella objektet i det angivna läget för läsning och skrivning utan delning i C++."
type: docs
weight: 1600
url: /sv/cpp/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) method


Öppnar filen som representeras av det aktuella objektet i det angivna läget för läsning och skrivning utan delning.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | FileMode | Anger läget i vilket filen ska öppnas |

### ReturnValue

Ett [FileStream](../../filestream/)‑objekt som är associerat med filen som representeras av det aktuella objektet

## Se även

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess) method


Öppnar filen som representeras av det aktuella objektet i det angivna läget, med den angivna åtkomsttypen och utan delning.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | FileMode | Anger läget i vilket filen ska öppnas |
| åtkomst | FileAccess | Den begärda åtkomsttypen |

### ReturnValue

Ett [FileStream](../../filestream/)‑objekt som är associerat med filen som representeras av det aktuella objektet

## Se även

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess, FileShare) method


Öppnar filen som representeras av det aktuella objektet i det angivna läget, med den angivna åtkomsttypen och delningsalternativet.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | FileMode | Anger läget i vilket filen ska öppnas |
| åtkomst | FileAccess | Den begärda åtkomsttypen |
| share | FileShare | Typen av åtkomst som andra [FileStream](../../filestream/)‑objekt har till den öppnade filen |

### ReturnValue

Ett [FileStream](../../filestream/)‑objekt som är associerat med filen som representeras av det aktuella objektet

## Se även

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
