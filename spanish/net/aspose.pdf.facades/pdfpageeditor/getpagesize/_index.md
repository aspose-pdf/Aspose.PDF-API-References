---
title: GetPageSize
second_title: Referencia de API de Aspose.PDF para .NET
description: Devuelve el tamaño de página de la página especificada.
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Devuelve el tamaño de página de la página especificada.

```csharp
public PageSize GetPageSize(int page)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | Int32 | Índice de páginas. Las páginas del documento están numeradas a partir del 1. |

### Valor_devuelto

El resultado es una instancia de PageSize. Utilice las propiedades Ancho y Alto del objeto devuelto para obtener el ancho y el alto de la página.

### Ejemplos

El siguiente ejemplo demuestra el uso del método GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfPageEditor](../../pdfpageeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfpageeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->