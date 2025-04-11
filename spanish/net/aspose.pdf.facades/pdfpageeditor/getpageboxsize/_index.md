---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Devuelve el tamaño de la caja especificada en el documento
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## Método PdfPageEditor.GetPageBoxSize

Devuelve el tamaño de la caja especificada en el documento.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | Índice de la página. Las páginas del documento están numeradas desde 1. |
| pageBoxName | String | Nombre del tipo de caja. Los valores válidos son: "art", "bleed", "crop", "media", "trim". |

### Valor de Retorno

Rectángulo que contiene la caja solicitada.

## Ejemplos

El siguiente ejemplo demuestra cómo obtener la caja de medios de la primera página:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Ver También

* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)