---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber 메서드. 지정된 페이지에서 테이블을 추출합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

지정된 페이지에서 테이블을 추출합니다.

```csharp
public virtual void Visit(Page page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Page | Pdf 문서 페이지 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 테이블을 추출하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

지정된 문서에서 테이블을 추출합니다.

```csharp
public void Visit(Document pdf)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdf | Document | Pdf 문서 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 테이블을 추출하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)