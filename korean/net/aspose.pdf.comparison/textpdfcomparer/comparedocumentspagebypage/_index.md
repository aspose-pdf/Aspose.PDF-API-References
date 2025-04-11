---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer 메서드. 두 문서를 페이지별로 비교합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

두 문서를 페이지별로 비교합니다.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 첫 번째 문서.. |
| document2 | Document | 두 번째 문서. |
| options | ComparisonOptions | 비교 옵션. |

### 반환 값

페이지별 변경 사항 목록.

### 참조

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

두 문서를 페이지별로 비교합니다. 결과는 PDF 파일에 저장됩니다.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 첫 번째 문서.. |
| document2 | Document | 두 번째 문서. |
| options | ComparisonOptions | 비교 옵션. |
| resultPdfDocumentPath | String | 비교 결과를 저장할 PDF 파일의 경로. |

### 반환 값

페이지별 변경 사항 목록.

### 참조

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)