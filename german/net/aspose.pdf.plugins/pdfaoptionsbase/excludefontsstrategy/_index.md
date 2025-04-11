---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase-Eigenschaft. Ruft die Strategie zum Entfernen von Schriftarten ab oder legt sie fest, um die Dateigröße während des PDF/A-Konvertierungsprozesses zu minimieren
type: docs
weight: 30
url: /de/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy-Eigenschaft

Ruft die Strategie zum Entfernen von Schriftarten ab oder legt sie fest, um die Dateigröße während des PDF/A-Konvertierungsprozesses zu minimieren.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Eigenschaftswert

Die Strategie zum Entfernen von Schriftarten. Dies kann einer der Werte aus der [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) Enumeration sein. Der Standardwert ist die Kombination aus SubsetFonts und RemoveDuplicatedFonts.

## Anmerkungen

Diese Eigenschaft ermöglicht es Ihnen, zu steuern, wie Schriftarten während des Konvertierungsprozesses behandelt werden. Sie können wählen, ob Sie doppelte Schriftarten entfernen, ähnliche Schriftarten mit unterschiedlichen Breiten entfernen oder Schriftarten subsetten möchten.

### Siehe auch

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)