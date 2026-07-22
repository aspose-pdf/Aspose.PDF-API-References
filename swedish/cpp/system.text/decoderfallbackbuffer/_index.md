---
title: "System::Text::DecoderFallbackBuffer-klass"
linktitle: "DecoderFallbackBuffer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::DecoderFallbackBuffer-klass. Tillhandahåller en buffert för återfallsimplementation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.text/decoderfallbackbuffer/
---
## DecoderFallbackBuffer class


Tillhandahåller en buffert för fallback‑implementation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn `new`, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class DecoderFallbackBuffer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) | Implementerar den faktiska fallback‑proceduren. |
| virtual [get_Remaining](./get_remaining/)() const | Hämtar återstående antal tecken som ska bearbetas. |
| virtual [GetNextChar](./getnextchar/)() | Extraherar nästa tecken i fallback‑bufferten. |
| virtual [MovePrevious](./moveprevious/)() | Flyttar buffertpositionen ett steg tillbaka om möjligt. |
| virtual [Reset](./reset/)() | Återställer bufferten till ursprungligt tillstånd. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
