---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Entfernt die Öffnungsaktion aus dem Dokument. Diese Operation ist nützlich, wenn mehrere Dokumente, die eine explizite 'GoTo'-Aktion beim Start verwenden, zusammengefügt werden.
type: docs
weight: 430
url: /de/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction-Methode

Entfernt die Öffnungsaktion aus dem Dokument. Diese Operation ist nützlich, wenn mehrere Dokumente, die eine explizite 'GoTo'-Aktion beim Start verwenden, zusammengefügt werden.

```csharp
public void RemoveDocumentOpenAction()
```

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)