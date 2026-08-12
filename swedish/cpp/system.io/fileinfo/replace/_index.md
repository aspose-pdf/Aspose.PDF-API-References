---
title: "System::IO::FileInfo::Replace metod"
linktitle: "Ersätt"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileInfo::Replace metod. Ersätter innehållet i en angiven destinationsfil med filen som representeras av det aktuella FileInfo‑objektet och skapar en säkerhetskopia av den ersatta filen i C++."
type: docs
weight: 2000
url: /sv/cpp/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) method


Ersätter innehållet i en angiven destinationsfil med filen som representeras av det aktuella [FileInfo](../)‑objektet och skapar en säkerhetskopia av den ersatta filen.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationFileName | const String\& | Ett namn på filen som ska ersättas |
| destinationBackupFileName | const String\& | Ett namn på säkerhetskopian |

### ReturnValue

Ett FileInfor‑objekt som representerar filen som pekas på av **destinationFileName**

## Se även

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Replace(const String\&, const String\&, bool) method


Ersätter innehållet i en angiven destinationsfil med filen som representeras av det aktuella [FileInfo](../)‑objektet och skapar en säkerhetskopia av den ersatta filen.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationFileName | const String\& | Ett namn på filen som ska ersättas |
| destinationBackupFileName | const String\& | Ett namn på säkerhetskopian |
| ignoreMetadataErrors | bool | Anger om sammanslagningsfel från den ersatta filen till ersättningsfilen ska ignoreras (true) eller inte (false) |

### ReturnValue

Ett FileInfor‑objekt som representerar filen som pekas på av **destinationFileName**

## Se även

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
