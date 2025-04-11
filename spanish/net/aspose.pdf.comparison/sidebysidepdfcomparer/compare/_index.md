---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: Método SideBySidePdfComparer. Compara dos páginas. El resultado se guarda en un documento PDF en el que se escribe primero la primera página y luego la segunda. Puedes abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios uno al lado del otro. Las eliminaciones se anotan en la página de la izquierda y las inserciones se anotan en la página de la derecha.
type: docs
weight: 10
url: /es/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Compara dos páginas. El resultado se guarda en un documento PDF en el que se escribe primero la primera página y luego la segunda. Puedes abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios uno al lado del otro. Las eliminaciones se anotan en la página de la izquierda y las inserciones se anotan en la página de la derecha.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | La primera página a comparar. |
| page2 | Page | La segunda página a comparar. |
| targetPdfPath | String | La ruta al archivo PDF para guardar el resultado de la comparación. |
| options | SideBySideComparisonOptions | Las opciones de comparación. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Compara dos documentos. Las páginas se comparan una por una. Las páginas de los documentos comparados se copian una tras otra en el documento resultante. Primero la primera página del primer documento, luego la primera página del segundo documento. A continuación, la segunda del primer documento y luego la segunda del segundo documento, etc. Puedes abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios uno al lado del otro. Las eliminaciones se anotan en la página de la izquierda y las inserciones se anotan en la página de la derecha.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | El primer documento a comparar. |
| document2 | Document | El segundo documento a comparar. |
| targetPdfPath | String | La ruta al archivo PDF para guardar el resultado de la comparación. |
| options | SideBySideComparisonOptions | Las opciones de comparación. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)