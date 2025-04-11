---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Devuelve la rotación de la página especificada
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## Método PdfPageEditor.GetPageRotation

Devuelve la rotación de la página especificada.

```csharp
public int GetPageRotation(int page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | Índice de la página. Las páginas del documento están numeradas desde 1. |

### Valor de Retorno

Rotación de la página en grados.

## Ejemplos

El siguiente ejemplo demuestra cómo obtener la rotación de la página:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Véase También

* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)