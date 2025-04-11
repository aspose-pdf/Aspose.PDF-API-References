---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 메서드. 지정된 페이지에서 검색을 수행합니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

지정된 페이지에서 검색을 수행합니다.

```csharp
public override void Visit(Page page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Page | PDF 문서 페이지 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

지정된 문서에서 검색을 수행합니다.

```csharp
public override void Visit(Document pdf)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdf | Document | PDF 문서 객체. |

## 예제

이 예제는 PDF 문서에서 텍스트를 찾고 모든 검색 발생의 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

지정된 양식 객체에서 검색을 수행합니다.

```csharp
public void Visit(XForm xForm)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xForm | XForm | PDF 양식 객체. |

### 참조

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)