---
title: "Aspose::Pdf::XslFoLoadOptions::ParsingErrorsHandlingTypes enum"
linktitle: "ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XslFoLoadOptions::ParsingErrorsHandlingTypes enum. Källdokumentet XSLFO kan innehålla formateringsfel. Detta enum enumererar möjliga strategier för hantering av sådana formateringsfel i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf/xslfoloadoptions/parsingerrorshandlingtypes/
---
## ParsingErrorsHandlingTypes enum


Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel.

```cpp
enum class ParsingErrorsHandlingTypes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| TryIgnore | 0 | I detta fall kommer konverteraren att instrueras att försöka fortsätta med konverteringen och ignorera hittade formateringsfel. I detta fall är framgång inte garanterad, allvarliga problem kan uppstå senare i konverteraren, och i sådant fall kommer ett undantag att kastas med en lista över hittade formateringsfel. |
| ThrowExceptionImmediately | 1 | I detta fall kommer konverteringen att stoppas omedelbart och ett undantag kommer att kastas omedelbart efter att det första formateringsfelet har upptäckts. |
| InvokeCustomHandler | 2 | Detta är den mest flexibla metoden – anpassad kod måste tillhandahålla (i egenskapen WarningCallback) en speciell hanterare som kommer att anropas när ett formateringsfel upptäcks. Den hanteraren kan t.ex. logga eller räkna fel osv och kommer att ge ett beslut om behandlingen kan fortsätta för detta eller det felet. |

## Se även

* Class [XslFoLoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
