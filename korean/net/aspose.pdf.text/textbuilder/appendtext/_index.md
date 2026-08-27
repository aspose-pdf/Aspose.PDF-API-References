---
title: "TextBuilder.AppendText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextBuilder 메서드. 텍스트 조각을 Pdf 페이지에 추가합니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Pdf 페이지에 텍스트 조각을 추가합니다

```csharp
public void AppendText(TextFragment textFragment)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textFragment | TextFragment | 텍스트 조각 객체. |

## 예제

이 예제는 텍스트 조각 객체를 생성하고, 텍스트 세그먼트를 사용자 정의한 뒤 Pdf 페이지에 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// 텍스트 조각 생성
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// 텍스트 속성을 설정합니다.
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// 텍스트 조각의 Segments 컬렉션에 세그먼트를 하나 더 추가합니다
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// TextBuilder 객체를 생성합니다
TextBuilder builder = new TextBuilder(page);

// 텍스트 조각을 PDF 페이지에 추가합니다
builder.AppendText(tf);

//문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Pdf 페이지에 텍스트 조각 목록을 추가합니다.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textFragments | List`1 | 텍스트 조각 컬렉션 |

### 또 보기

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


