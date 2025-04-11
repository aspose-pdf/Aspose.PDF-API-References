---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase-Eigenschaft. Ruft die Version des PDF/A-Standards ab oder legt sie fest, die für die Validierung oder Konvertierung verwendet werden soll
type: docs
weight: 110
url: /de/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion-Eigenschaft

Ruft die Version des PDF/A-Standards ab oder legt sie fest, die für die Validierung oder Konvertierung verwendet werden soll.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Eigenschaftswert

Die Version des PDF/A-Standards. Dies kann einer der Werte aus der [`PdfAStandardVersion`](../../pdfastandardversion/) Enumeration sein.

## Anmerkungen

Die Version des PDF/A-Standards wird verwendet, um das Konformitätsniveau für die PDF/A-Validierung und -Konvertierung zu bestimmen. Wenn die Version auf Auto gesetzt ist, bestimmt das System automatisch die geeignete PDF/A-Standardversion für die Validierung basierend auf den Metadaten des Dokuments. Für den PDF/A-Konvertierungsprozess wird Auto standardmäßig auf die PDF/A-1b-Standardversion gesetzt.

### Siehe auch

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)