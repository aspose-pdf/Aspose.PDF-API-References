---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF för Java API-referens"
description: "Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel"
type: docs
weight: 5790
url: /sv/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av sådana formateringsfel

## Fält

| Fält | Beskrivning |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Det här är den mest flexibla metoden – anpassad kod måste tillhandahålla (i egenskapen WarningCallback) en speciell hanterare som kommer att anropas när ett formateringsfel upptäcks. Den hanteraren kan t.ex. logga eller räkna fel osv och kommer att ge ett beslut om huruvida bearbetningen kan fortsätta för detta eller det felet. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | I det här fallet kommer konverteringen att stoppas omedelbart och ett undantag kommer att kastas omedelbart efter att det första formateringsfelet har upptäckts. |
| [TryIgnore](#TryIgnore) | I det här fallet kommer konverteraren att instrueras att försöka fortsätta med konverteringen och ignorera hittade formateringsfel. I detta fall är framgång inte garanterad, allvarliga problem kan uppstå senare i konverteraren, och i sådant fall kommer ett undantag att kastas med en lista över hittade formateringsfel. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Det här är den mest flexibla metoden – anpassad kod måste tillhandahålla (i egenskapen WarningCallback) en speciell hanterare som kommer att anropas när ett formateringsfel upptäcks. Den hanteraren kan t.ex. logga eller räkna fel osv och kommer att ge ett beslut om huruvida bearbetningen kan fortsätta för detta eller det felet.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

I det här fallet kommer konverteringen att stoppas omedelbart och ett undantag kommer att kastas omedelbart efter att det första formateringsfelet har upptäckts.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

I det här fallet kommer konverteraren att instrueras att försöka fortsätta med konverteringen och ignorera hittade formateringsfel. I detta fall är framgång inte garanterad, allvarliga problem kan uppstå senare i konverteraren, och i sådant fall kommer ett undantag att kastas med en lista över hittade formateringsfel.
