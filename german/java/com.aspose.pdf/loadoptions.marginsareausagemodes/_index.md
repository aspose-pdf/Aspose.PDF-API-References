---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt den Verwendungsmodus des Randbereichs während der Konvertierung dar (wie HTML, EPUB usw.) und definiert die Behandlung von Anweisungen des importierten Formats im Zusammenhang mit der Nutzung der Ränder."
type: docs
weight: 2800
url: /de/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Stellt den Verwendungsmodus des Randbereichs während der Konvertierung dar (wie HTML, EPUB usw.) und definiert die Behandlung von Anweisungen des importierten Formats im Zusammenhang mit der Nutzung der Ränder.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Dieser Modus verbietet die Verwendung des Randbereichs strikt, sodass der Konverter den Randbereich niemals für das Rendern nutzt, selbst wenn CSS oder das Format des Quelldokuments dies erlaubt oder erfordert. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | In diesem Modus folgt der Konverter dem Format des importierten Dokuments (z. B. CSS des importierten HTML) bei der Verwendung des Randbereichs. Wenn also das Format des importierten Dokuments die Nutzung des Randbereichs zum Rendern erfordert, erlaubt der Konverter dies. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Dieser Modus verbietet die Verwendung des Randbereichs strikt, sodass der Konverter den Randbereich niemals für das Rendern nutzt, selbst wenn CSS oder das Format des Quelldokuments dies erlaubt oder erfordert.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

In diesem Modus folgt der Konverter dem Format des importierten Dokuments (z. B. CSS des importierten HTML) bei der Verwendung des Randbereichs. Wenn also das Format des importierten Dokuments die Nutzung des Randbereichs zum Rendern erfordert, erlaubt der Konverter dies.
