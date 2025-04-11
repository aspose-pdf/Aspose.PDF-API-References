---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer 메서드. 두 페이지를 비교합니다. 결과는 첫 번째 페이지가 먼저 작성되고 두 번째 페이지가 그 뒤에 작성된 PDF 문서에 저장됩니다. Adobe Acrobat에서 두 페이지 보기로 열어 변경 사항을 나란히 볼 수 있습니다. 삭제는 왼쪽 페이지에 표시되고 삽입은 오른쪽 페이지에 표시됩니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

두 페이지를 비교합니다. 결과는 첫 번째 페이지가 먼저 작성되고 두 번째 페이지가 그 뒤에 작성된 PDF 문서에 저장됩니다. Adobe Acrobat에서 두 페이지 보기로 열어 변경 사항을 나란히 볼 수 있습니다. 삭제는 왼쪽 페이지에 표시되고 삽입은 오른쪽 페이지에 표시됩니다.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | 비교할 첫 번째 페이지입니다. |
| page2 | Page | 비교할 두 번째 페이지입니다. |
| targetPdfPath | String | 비교 결과를 저장할 PDF 파일의 경로입니다. |
| options | SideBySideComparisonOptions | 비교 옵션입니다. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

두 문서를 비교합니다. 페이지는 하나씩 비교됩니다. 비교된 문서의 페이지는 결과 문서에 차례로 복사됩니다. 먼저 첫 번째 문서의 첫 페이지, 그 다음 두 번째 문서의 첫 페이지입니다. 다음은 첫 번째 문서의 두 번째 페이지와 두 번째 문서의 두 번째 페이지입니다. Adobe Acrobat에서 두 페이지 보기로 열어 변경 사항을 나란히 볼 수 있습니다. 삭제는 왼쪽 페이지에 표시되고 삽입은 오른쪽 페이지에 표시됩니다.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | 비교할 첫 번째 문서입니다. |
| document2 | Document | 비교할 두 번째 문서입니다. |
| targetPdfPath | String | 비교 결과를 저장할 PDF 파일의 경로입니다. |
| options | SideBySideComparisonOptions | 비교 옵션입니다. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)