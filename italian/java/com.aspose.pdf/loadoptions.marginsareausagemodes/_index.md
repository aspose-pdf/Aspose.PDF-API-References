---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la modalità di utilizzo dell'area dei margini durante la conversione (come HTML, EPUB ecc.), definisce il trattamento delle istruzioni del formato importato relative all'uso dei margini."
type: docs
weight: 2800
url: /it/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Rappresenta la modalità di utilizzo dell'area dei margini durante la conversione (come HTML, EPUB ecc.), definisce il trattamento delle istruzioni del formato importato relative all'uso dei margini.

## Campi

| Campo | Descrizione |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Questa modalità vieta strettamente l'uso dell'area dei margini, quindi, il convertitore non utilizzerà mai l'area dei margini per il rendering, anche se CSS o il formato del documento sorgente lo consente o lo richiede. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | In questa modalità il convertitore rispetta il formato del documento importato (ad es. CSS dell'HTML importato) nell'uso dell'area dei margini. Quindi, se il formato del documento importato richiede l'uso dell'area dei margini per il rendering, il convertitore lo consentirà. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Questa modalità vieta strettamente l'uso dell'area dei margini, quindi, il convertitore non utilizzerà mai l'area dei margini per il rendering, anche se CSS o il formato del documento sorgente lo consente o lo richiede.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

In questa modalità il convertitore rispetta il formato del documento importato (ad es. CSS dell'HTML importato) nell'uso dell'area dei margini. Quindi, se il formato del documento importato richiede l'uso dell'area dei margini per il rendering, il convertitore lo consentirà.
