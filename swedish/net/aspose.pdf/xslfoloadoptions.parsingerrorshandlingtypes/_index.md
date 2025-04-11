---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes enum. Källan XSLFO-dokumentet kan innehålla formateringsfel. Denna enum uppräkna möjliga strategier för hantering av sådana formateringsfel
type: docs
weight: 11540
url: /sv/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Källan XSLFO-dokumentet kan innehålla formateringsfel. Denna enum uppräkna möjliga strategier för hantering av sådana formateringsfel

```csharp
public enum ParsingErrorsHandlingTypes
```

### Values

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| TryIgnore | `0` | I detta fall kommer konverteraren att instrueras att försöka fortsätta med konverteringen och ignorera funna formateringsfel. I detta fall är framgång inte garanterad, allvarliga problem kan uppstå senare i konverteraren, och i sådana fall kommer ett undantag att kastas med en lista över funna formateringsfel. |
| ThrowExceptionImmediately | `1` | I detta fall kommer konverteringen att stoppas omedelbart och ett undantag kommer att kastas omedelbart efter att den första formateringsfelet har upptäckts |
| InvokeCustomHandler | `2` | Detta är den mest flexibla metoden - anpassad kod måste tillhandahålla (i WarningCallback-egenskapen) en speciell hanterare som kommer att anropas när ett formateringsfel upptäcks. Den hanteraren kan t.ex. logga eller räkna fel osv. och kommer att ge beslut om bearbetningen kan fortsätta för detta eller det felet. |

### Se Även

* klass [XslFoLoadOptions](../xslfoloadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)