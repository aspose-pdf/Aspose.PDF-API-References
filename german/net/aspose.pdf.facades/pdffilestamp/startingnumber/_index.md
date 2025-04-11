---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-Eigenschaft. Legt die Startnummer für die erste Seite der Eingabedatei fest oder erhält sie. Die nächsten Seiten werden ab diesem Wert nummeriert. Wenn beispielsweise die StartingNumber auf 100 gesetzt ist, haben die Dokumentseiten die Nummern 100, 101, 102.
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber-Eigenschaft

Legt die Startnummer für die erste Seite der Eingabedatei fest oder erhält sie. Die nächsten Seiten werden ab diesem Wert nummeriert. Wenn beispielsweise die StartingNumber auf 100 gesetzt ist, haben die Dokumentseiten die Nummern 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)