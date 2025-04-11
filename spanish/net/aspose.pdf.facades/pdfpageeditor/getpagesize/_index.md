---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Devuelve el tamaño de la página de la página especificada
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## Método PdfPageEditor.GetPageSize

Devuelve el tamaño de la página de la página especificada.

```csharp
public PageSize GetPageSize(int page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | Índice de la página. Las páginas del documento están numeradas desde 1. |

### Valor de Retorno

El resultado es una instancia de PageSize. Utilice las propiedades Width y Height del objeto devuelto para obtener el ancho y la altura de la página.

## Ejemplos

El siguiente ejemplo demuestra el uso del método GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)