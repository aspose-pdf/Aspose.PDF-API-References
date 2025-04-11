---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: Método TextPdfComparer. Compara dois documentos página por página
type: docs
weight: 40
url: /pt/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Compara dois documentos página por página.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document1 | Document | Primeiro documento.. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opções de comparação. |

### Valor de Retorno

Lista de alterações por página.

### Veja Também

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Compara dois documentos página por página. O resultado é salvo em um arquivo PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document1 | Document | Primeiro documento.. |
| document2 | Document | Segundo documento. |
| options | ComparisonOptions | Opções de comparação. |
| resultPdfDocumentPath | String | Caminho para o arquivo pdf para salvar os resultados da comparação. |

### Valor de Retorno

Lista de alterações por página.

### Veja Também

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)