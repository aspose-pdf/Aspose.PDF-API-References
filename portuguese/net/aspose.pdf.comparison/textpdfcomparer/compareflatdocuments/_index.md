---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: Método TextPdfComparer. Compara dois documentos página por página. Os documentos são comparados como um todo. Antes de comparar o texto, os textos das páginas do documento são combinados em um único texto
type: docs
weight: 50
url: /pt/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Compara dois documentos página por página. Os documentos são comparados como um todo. Antes de comparar o texto, os textos das páginas do documento são combinados em um único texto.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document1 | Document | Primeiro documento. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opções de comparação. |

### Valor de Retorno

Lista de alterações.

### Veja Também

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Compara dois documentos página por página. O resultado é salvo em um arquivo PDF. Os documentos são comparados como um todo. Antes de comparar o texto, os textos das páginas do documento são combinados em um único texto.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document1 | Document | Primeiro documento. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opções de comparação. |
| resultPdfDocumentPath | String | Caminho para o arquivo pdf para salvar os resultados da comparação. |

### Valor de Retorno

Lista de alterações.

### Veja Também

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)