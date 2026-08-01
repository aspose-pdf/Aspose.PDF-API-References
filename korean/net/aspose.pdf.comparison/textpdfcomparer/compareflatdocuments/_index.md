---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextPdfComparer 메서드. 두 문서를 페이지별로 비교합니다. 문서는 전체적으로 비교됩니다. 텍스트를 비교하기 전에 문서 페이지의 텍스트를 하나의 텍스트로 결합합니다."
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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 첫 번째 문서. |
| document2 | Document | 두 번째 문서. |
| 옵션 | ComparisonOptions | 비교 옵션. |

### 반환 값

변경 목록.

### 또 보기

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

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 첫 번째 문서. |
| document2 | Document | 두 번째 문서. |
| 옵션 | ComparisonOptions | 비교 옵션. |
| resultPdfDocumentPath | String | 비교 결과를 저장할 pdf 파일 경로. |

### 반환 값

변경 목록.

### 또 보기

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


