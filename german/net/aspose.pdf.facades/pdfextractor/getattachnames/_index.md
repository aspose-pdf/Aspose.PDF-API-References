---
title: GetAttachNames
second_title: Aspose.PDF für .NET-API-Referenz
description: Gibt eine Liste der Anhänge in der PDF-Datei zurück. Hinweis ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden.
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

Gibt eine Liste der Anhänge in der PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden.

```csharp
public IList<string> GetAttachNames()
```

### Rückgabewert

Liste der Anhänge

### Beispiele

Das Beispiel zeigt, wie Anhangsnamen aus einer PDF-Datei extrahiert werden.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
