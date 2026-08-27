---
title: "TextFragmentAbsorber.Visit"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragmentAbsorber 메서드. 지정된 페이지에서 검색을 수행합니다."
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
| 페이지 | 페이지 | PDF 문서 페이지 객체. |

## 예제

이 예제는 첫 번째 PDF 문서 페이지에서 텍스트를 찾고 해당 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
absorber.Visit(doc.Pages[1]);

// 검색된 모든 항목의 텍스트를 변경합니다.
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

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

이 예제는 PDF 문서에서 텍스트를 찾고 검색된 모든 항목의 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 문서 텍스트 폰트를 변경하는 데 사용할 폰트를 찾습니다.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
absorber.Visit(doc);

// 첫 번째 텍스트 발생의 텍스트를 변경합니다.
absorber.TextFragments[1].Text = "hi world";

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

지정된 폼 객체에서 검색을 수행합니다.

```csharp
public void Visit(XForm xForm)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xForm | XForm | Pdf 양식 개체. |

### 또 보기

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


