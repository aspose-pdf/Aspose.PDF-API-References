---
title: "System::IO::File::Create metod"
linktitle: "Skapa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::File::Create-metoden. Skapar en ny fil (eller skriver över befintlig) och öppnar den för läs- och skrivåtkomst med angiven buffertstorlek och alternativ i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/file/create/
---
## File::Create method


Skapar en ny fil (eller skriver över befintlig) och öppnar den för läs- och skrivåtkomst med angiven buffertstorlek och alternativ.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska skapas eller skrivas över |
| bufferSize | int32_t | Antalet byte som buffras vid läsning från och skrivning till filen |
| options | FileOptions | Anger hur filen ska skapas eller skrivas över |

### ReturnValue

En delad pekare till objektet [FileStream](../../filestream/) som är associerat med den angivna filen

## Se även

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileOptions](../../fileoptions/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
