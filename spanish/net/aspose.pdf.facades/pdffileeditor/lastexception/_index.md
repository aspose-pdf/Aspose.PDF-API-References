---
title: PdfFileEditor.LastException
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfFileEditor. Obtiene la última excepción ocurrida. Puede ser utilizada para verificar la razón del fallo
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdffileeditor/lastexception/
---
## Propiedad PdfFileEditor.LastException

Obtiene la última excepción ocurrida. Puede ser utilizada para verificar la razón del fallo.

```csharp
public Exception LastException { get; }
```

## Ejemplos

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

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)