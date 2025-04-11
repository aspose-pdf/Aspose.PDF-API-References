---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: Método TextPdfComparer. Compara dos documentos página por página
type: docs
weight: 40
url: /es/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Compara dos documentos página por página.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | Document | Primer documento.. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opciones de comparación. |

### Valor de Retorno

Lista de cambios por página.

### Véase También

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Compara dos documentos página por página. El resultado se guarda en un archivo PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | Document | Primer documento.. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opciones de comparación. |
| resultPdfDocumentPath | String | Ruta al archivo pdf para guardar los resultados de la comparación. |

### Valor de Retorno

Lista de cambios por página.

### Véase También

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)