---
title: "Aspose::Pdf::ToUnicodeProcessingRules klass"
linktitle: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ToUnicodeProcessingRules klass. Denna klass beskriver regler som kan användas för att lösa Adobe Preflight‑felet \"Text cannot be mapped to Unicode\" i C++."
type: docs
weight: 18700
url: /sv/cpp/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class


Denna klass beskriver regler som kan användas för att lösa Adobe Preflight‑felet \"Text cannot be mapped to Unicode\".

```cpp
class ToUnicodeProcessingRules : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_MapNonLinkedSymbolsOnSpace](./get_mapnonlinkedsymbolsonspace/)() const | Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger ett fel "Text cannot be mapped to Unicode". Använd den här flaggan för att mappa o‑länkade symboler till Unicode‑"space" (kod 32). |
| [get_RemoveSpacesFromCMapNames](./get_removespacesfromcmapnames/)() const | Vissa teckensnitt har ToUnicode‑teckenkodkartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Denna flagga instruerar att ta bort mellanslag från namn på ToUnicode‑teckenkodkartor. Standardvärdet är falskt. |
| [set_MapNonLinkedSymbolsOnSpace](./set_mapnonlinkedsymbolsonspace/)(bool) | Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger ett fel "Text cannot be mapped to Unicode". Använd den här flaggan för att mappa o‑länkade symboler till Unicode‑"space" (kod 32). |
| [set_RemoveSpacesFromCMapNames](./set_removespacesfromcmapnames/)(bool) | Vissa teckensnitt har ToUnicode‑teckenkodkartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Denna flagga instruerar att ta bort mellanslag från namn på ToUnicode‑teckenkodkartor. Standardvärdet är falskt. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)() | Initierar en ny instans av klassen [ToUnicodeProcessingRules](./). |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool) | Initierar en ny instans av klassen [ToUnicodeProcessingRules](./) med det angivna alternativet för att ta bort mellanslag från CMap‑namn. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/)(bool, bool) | Initierar en ny instans av klassen [ToUnicodeProcessingRules](./) med angivna alternativ. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
