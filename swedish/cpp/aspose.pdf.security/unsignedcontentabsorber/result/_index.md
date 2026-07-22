---
title: "Aspose::Pdf::Security::UnsignedContentAbsorber::Result klass"
linktitle: "Resultat"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::UnsignedContentAbsorber::Result klass. Inkapslar resultatet av en operation som försöker extrahera osignerat innehåll från ett PDF-dokument i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.security/unsignedcontentabsorber/result/
---
## Result class


Inkapslar resultatet av en operation som försöker extrahera osignerat innehåll från ett PDF-dokument.

```cpp
class Result : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Coverage](./get_coverage/)() const | Hämtar ett värde som indikerar i vilken grad dokumentet är täckt av giltiga digitala signaturer. |
| [get_Message](./get_message/)() const | Hämtar ett meddelande som beskriver resultatet av operationen. |
| [get_Success](./get_success/)() const | Hämtar ett värde som indikerar om operationen för att hämta osignerat innehåll från dokumentet lyckades. |
| [get_UnsignedContent](./get_unsignedcontent/)() const | Hämtar ett osignerat innehåll. |
## Anmärkningar


Denna klass tillhandahåller information om operationens framgång, detaljer om det osignerade innehållet, ett meddelande som beskriver resultatet och täckningsstatusen för dokumentets signaturer.
## Se även

* Class [Object](../../../system/object/)
* Class [UnsignedContentAbsorber](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
