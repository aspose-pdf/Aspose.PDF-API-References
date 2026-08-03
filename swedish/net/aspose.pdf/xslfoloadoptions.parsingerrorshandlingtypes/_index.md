---
title: "Enum XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes-enum. Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel."
type: docs
weight: 11730
url: /sv/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| TryIgnore | `0` | I det här fallet kommer konverteraren att instrueras att försöka fortsätta med konverteringen och ignorera hittade formateringsfel. I det här fallet är framgång inte garanterad, allvarliga problem kan uppstå senare i konverteraren, och i sådant fall kommer ett undantag att kastas med en lista över hittade formateringsfel. |
| ThrowExceptionImmediately | `1` | I det här fallet kommer konverteringen att stoppas omedelbart och ett undantag kommer att kastas omedelbart efter att det första formateringsfelet har upptäckts. |
| InvokeCustomHandler | `2` | Det här är den mest flexibla metoden – anpassad kod måste tillhandahålla (i egenskapen WarningCallback) en speciell hanterare som anropas när ett formateringsfel upptäcks. Den hanteraren kan t.ex. logga eller räkna fel osv och kommer att ge ett beslut om behandlingen kan fortsätta för detta eller det felet. |

### Se även

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


