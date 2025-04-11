---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer 메서드. 두 문서를 페이지별로 비교합니다. 문서는 전체적으로 비교됩니다. 텍스트를 비교하기 전에 문서 페이지의 텍스트가 하나의 텍스트로 결합됩니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

두 문서를 페이지별로 비교합니다. 문서는 전체적으로 비교됩니다. 텍스트를 비교하기 전에 문서 페이지의 텍스트가 하나의 텍스트로 결합됩니다.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | 첫 번째 문서. |
| document2 | Document | 두 번째 문서. |
| options | ComparisonOptions | 비교 옵션. |

### Return Value

변경 사항 목록.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

두 문서를 페이지별로 비교합니다. 결과는 PDF 파일에 저장됩니다. 문서는 전체적으로 비교됩니다. 텍스트를 비교하기 전에 문서 페이지의 텍스트가 하나의 텍스트로 결합됩니다.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | 첫 번째 문서. |
| document2 | Document | 두 번째 문서. |
| options | ComparisonOptions | 비교 옵션. |
| resultPdfDocumentPath | String | 비교 결과를 저장할 PDF 파일의 경로. |

### Return Value

변경 사항 목록.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)