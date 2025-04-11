---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfAOptionsBase. Ottiene o imposta la strategia per rimuovere i caratteri per ridurre al minimo la dimensione del file di output durante il processo di conversione PDF/A
type: docs
weight: 30
url: /it/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## Proprietà PdfAOptionsBase.ExcludeFontsStrategy

Ottiene o imposta la strategia per rimuovere i caratteri per ridurre al minimo la dimensione del file di output durante il processo di conversione PDF/A.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Valore della Proprietà

La strategia per rimuovere i caratteri. Questo può essere uno dei valori dell'enumerazione [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/). Il valore predefinito è la combinazione di SubsetFonts e RemoveDuplicatedFonts.

## Osservazioni

Questa proprietà consente di controllare come vengono gestiti i caratteri durante il processo di conversione. Puoi scegliere di rimuovere i caratteri duplicati, rimuovere caratteri simili con larghezze diverse o sottogruppare i caratteri.

### Vedi Anche

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)