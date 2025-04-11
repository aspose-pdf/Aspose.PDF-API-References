---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: Método TextPdfComparer. Compara dos documentos página por página. Los documentos se comparan en su totalidad. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto.
type: docs
weight: 50
url: /es/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Compara dos documentos página por página. Los documentos se comparan en su totalidad. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | Document | Primer documento. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opciones de comparación. |

### Valor de Retorno

Lista de cambios.

### Véase También

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Compara dos documentos página por página. El resultado se guarda en un archivo PDF. Los documentos se comparan en su totalidad. Antes de comparar el texto, los textos de las páginas del documento se combinan en un solo texto.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | Document | Primer documento. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opciones de comparación. |
| resultPdfDocumentPath | String | Ruta al archivo pdf para guardar los resultados de la comparación. |

### Valor de Retorno

Lista de cambios.

### Véase También

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)