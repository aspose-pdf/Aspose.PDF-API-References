---
title: "System::IO::FileInfo::CopyTo‑metod"
linktitle: "CopyTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileInfo::CopyTo‑metod. Kopierar filen som representeras av det aktuella objektet till den angivna platsen. Om målfilen redan finns, misslyckas kopieringen i C++."
type: docs
weight: 300
url: /sv/cpp/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) method


Kopierar filen som representeras av det aktuella objektet till den angivna platsen. Om målfilen redan finns, misslyckas kopieringen.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destFileName | const String\& | Målfilsnamnet |

### ReturnValue

Ett [FileInfo](../)‑objekt som representerar kopian

## Se även

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::CopyTo(const String\&, bool) method


Kopierar filen som representeras av det aktuella objektet till den angivna platsen. En parameter anger om befintlig målfil ska skrivas över.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destFileName | const String\& | Målfilsnamnet |
| skriv över | bool | Sant om den befintliga målfilen ska skrivas över, falskt om kopieringen ska misslyckas när målfilen redan finns |

### ReturnValue

Ett [FileInfo](../)‑objekt som representerar kopian

## Se även

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
