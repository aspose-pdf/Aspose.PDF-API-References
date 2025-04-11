---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: Método SideBySidePdfComparer. Compara duas páginas. O resultado é salvo em um documento PDF no qual a primeira página é escrita primeiro e depois a segunda. Você pode abri-lo no Adobe Acrobat na visualização de duas páginas para ver as alterações lado a lado. As exclusões são anotadas na página à esquerda e as inserções são anotadas na página à direita.
type: docs
weight: 10
url: /pt/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Compara duas páginas. O resultado é salvo em um documento PDF no qual a primeira página é escrita primeiro, e depois a segunda. Você pode abri-lo no Adobe Acrobat na visualização de duas páginas para ver as alterações lado a lado. As exclusões são anotadas na página à esquerda, e as inserções são anotadas na página à direita.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | A primeira página a ser comparada. |
| page2 | Page | A segunda página a ser comparada. |
| targetPdfPath | String | O caminho para o arquivo PDF para salvar o resultado da comparação. |
| options | SideBySideComparisonOptions | As opções de comparação. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Compara dois documentos. As páginas são comparadas uma a uma. As páginas dos documentos comparados são copiadas uma após a outra no documento resultante. Primeiro a primeira página do primeiro documento, depois a primeira página do segundo documento. Em seguida, a segunda do primeiro documento e depois a segunda do segundo documento, etc. Você pode abri-lo no Adobe Acrobat na visualização de duas páginas para ver as alterações lado a lado. As exclusões são anotadas na página à esquerda, e as inserções são anotadas na página à direita.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | O primeiro documento a ser comparado. |
| document2 | Document | O segundo documento a ser comparado. |
| targetPdfPath | String | O caminho para o arquivo PDF para salvar o resultado da comparação. |
| options | SideBySideComparisonOptions | As opções de comparação. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)