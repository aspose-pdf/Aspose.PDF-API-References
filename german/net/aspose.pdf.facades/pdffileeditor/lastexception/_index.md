---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Eigenschaft. Gibt die zuletzt aufgetretene Ausnahme zurück. Kann verwendet werden, um den Grund für das Scheitern zu überprüfen
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## PdfFileEditor.LastException-Eigenschaft

Gibt die zuletzt aufgetretene Ausnahme zurück. Kann verwendet werden, um den Grund für das Scheitern zu überprüfen.

```csharp
public Exception LastException { get; }
```

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
if (!pfe.TryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
{
   Console.WriteLine("Error occured:");
   if (pfe.LastException != null)
   {
       Console.WriteLine(pfe.LastException.Message);
       if (pfe.LastException.InnerException != null)
           Console.WriteLine(pfe.LastException.InnerException.Message);
   }
}
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)