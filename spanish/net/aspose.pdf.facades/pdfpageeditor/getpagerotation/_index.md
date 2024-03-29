---
title: GetPageRotation
second_title: Referencia de API de Aspose.PDF para .NET
description: Devuelve la rotación de la página especificada.
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

Devuelve la rotación de la página especificada.

```csharp
public int GetPageRotation(int page)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | Int32 | Índice de páginas. Las páginas del documento están numeradas a partir del 1. |

### Valor_devuelto

Rotación de página en grados.

### Ejemplos

El siguiente ejemplo muestra cómo obtener la rotación de página:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Ver también

* class [PdfPageEditor](../../pdfpageeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfpageeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
