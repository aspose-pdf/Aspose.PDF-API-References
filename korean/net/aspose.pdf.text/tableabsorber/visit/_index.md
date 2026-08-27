---
title: "TableAbsorber.Visit"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TableAbsorber 메서드. 지정된 페이지에서 표를 추출합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

지정된 Page에서 테이블을 추출합니다.

```csharp
public virtual void Visit(Page page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | 페이지 | Pdf 문서 페이지 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 표를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 테이블을 찾기 위해 TableAbsorber 객체를 생성합니다
TableAbsorber absorber = new TableAbsorber();

// 흡수기를 사용하여 첫 번째 Page를 방문합니다
absorber.Visit(doc.Pages[1]);

// Page에서 첫 번째 테이블, 해당 첫 번째 셀 및 그 안의 텍스트 조각에 접근합니다
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 셀 안의 첫 번째 텍스트 조각의 텍스트를 변경합니다
fragment.Text = "hi world";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

지정된 Document에서 테이블을 추출합니다.

```csharp
public void Visit(Document pdf)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdf | Document | Pdf 문서 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 표를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 테이블을 찾기 위해 TableAbsorber 객체를 생성합니다
TableAbsorber absorber = new TableAbsorber();

// 흡수기를 사용하여 첫 번째 Page를 방문합니다
absorber.Visit(doc);

// Page에서 첫 번째 테이블, 해당 첫 번째 셀 및 그 안의 텍스트 조각에 접근합니다
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// 셀 안의 첫 번째 텍스트 조각의 텍스트를 변경합니다
fragment.Text = "hi world";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


