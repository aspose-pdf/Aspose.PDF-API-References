---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfViewer. Obtém ou define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150
type: docs
weight: 160
url: /pt/net/aspose.pdf.facades/pdfviewer/resolution/
---
## Propriedade PdfViewer.Resolution

Obtém ou define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150.

```csharp
public int Resolution { get; set; }
```

## Observações

Esta propriedade altera a resolução da imagem nos fluxos de conversão de página para imagem: quando o [`PrintAsImage`](../printasimage/) é definido como `true`, ou quando o método [`DecodePage`](../decodepage/) ou [`DecodeAllPages`](../decodeallpages/) é chamado. Para definir uma resolução de impressora para impressão direta em uma impressora, use a propriedade [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) na classe [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Veja Também

* classe [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)