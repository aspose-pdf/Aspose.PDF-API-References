---
title: "SideBySidePdfComparer.Compare"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "SideBySidePdfComparer 메서드. 두 페이지를 비교합니다. 결과는 첫 번째 페이지가 먼저, 두 번째 페이지가 그 다음에 기록된 PDF 문서에 저장됩니다. Adobe Acrobat의 두 페이지 보기에서 열어 변경 사항을 나란히 확인할 수 있습니다. 삭제는 왼쪽 페이지에 표시되고 삽입은 오른쪽 페이지에 표시됩니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

두 페이지를 비교합니다. 결과는 첫 페이지가 먼저 기록되고 그 다음에 두 번째 페이지가 기록되는 PDF 문서에 저장됩니다. Adobe Acrobat에서 두 페이지 보기 모드로 열어 변경 사항을 나란히 확인할 수 있습니다. 삭제된 내용은 왼쪽 페이지에 표시되고, 삽입된 내용은 오른쪽 페이지에 표시됩니다.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page1 | 페이지 | 비교할 첫 번째 페이지. |
| page2 | 페이지 | 비교할 첫 번째 페이지. |
| targetPdfPath | String | 비교 결과를 저장할 PDF 파일의 경로. |
| 옵션 | SideBySideComparisonOptions | 비교 옵션. |

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

두 문서를 비교합니다. 페이지를 하나씩 비교합니다. 비교된 문서의 페이지들을 결과 문서에 하나씩 차례대로 복사합니다. 먼저 첫 번째 문서의 첫 페이지, 그 다음 두 번째 문서의 첫 페이지가 들어갑니다. 다음은 첫 번째 문서의 두 번째 페이지, 그 다음 두 번째 문서의 두 번째 페이지가 들어가는 식입니다. Adobe Acrobat에서 두 페이지 보기 모드로 열어 변경 사항을 나란히 확인할 수 있습니다. 삭제된 내용은 왼쪽 페이지에 표시되고, 삽입된 내용은 오른쪽 페이지에 표시됩니다.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document1 | Document | 첫 번째 document을 비교합니다. |
| document2 | Document | 두 번째 document을 비교합니다. |
| targetPdfPath | String | 비교 결과를 저장할 PDF 파일의 경로. |
| 옵션 | SideBySideComparisonOptions | 비교 옵션. |

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


