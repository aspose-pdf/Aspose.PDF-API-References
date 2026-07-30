---
title: "PdfViewer.Resolution"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfViewer propriété. Obtient ou définit la résolution pendant la visualisation et l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150"
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

Obtient ou définit la résolution lors de la visualisation et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150.

```csharp
public int Resolution { get; set; }
```

## Remarques

Cette propriété modifie la résolution de l'image dans les flux de conversion page‑vers‑image : lorsque le [`PrintAsImage`](../printasimage/) est défini sur `true`, ou lorsque la méthode [`DecodePage`](../decodepage/) ou [`DecodeAllPages`](../decodeallpages/) est appelée. Pour définir une résolution d'imprimante pour l'impression directe sur une imprimante, utilisez la propriété [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) dans la classe [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Voir aussi

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


