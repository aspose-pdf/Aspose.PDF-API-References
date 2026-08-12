---
title: "System::IO::File::Open-metoden"
linktitle: "Open"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::File::Open-metoden. Öppnar den angivna filen i det angivna läget för läsning och skrivning utan delning i C++."
type: docs
weight: 1900
url: /sv/cpp/system.io/file/open/
---
## File::Open(const String\&, FileMode) method


Öppnar den angivna filen i det angivna läget för läsning och skrivning utan delning.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska öppnas |
| läge | FileMode | Anger läget som filen ska öppnas i |

### ReturnValue

Ett [FileStream](../../filestream/)-objekt som är associerat med den öppnade filen

## Se även

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::Open(const String\&, FileMode, FileAccess, FileShare) method


Öppnar den angivna filen i det angivna läget, med den angivna åtkomsttypen och delningsalternativet.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska öppnas |
| läge | FileMode | Anger läget som filen ska öppnas i |
| åtkomst | FileAccess | Den begärda åtkomsttypen |
| share | FileShare | Typen av åtkomst som andra [FileStream](../../filestream/)‑objekt har till den öppnade filen |

### ReturnValue

Ett [FileStream](../../filestream/)-objekt som är associerat med den öppnade filen

## Se även

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
