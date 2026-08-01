---
title: "TextSegment.TextSegment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextSegment 생성자. TextSegment 객체를 생성합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

TextSegment 객체를 생성합니다.

```csharp
public TextSegment()
```

## 예제

예제에서는 텍스트 조각 객체를 생성하고, 텍스트 조각 컬렉션에 텍스트 세그먼트를 추가한 뒤 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

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

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

TextSegment 객체를 생성합니다.

```csharp
public TextSegment(string text)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 텍스트 | String | 텍스트 세그먼트의 텍스트. |

## 예제

예제에서는 텍스트 조각 객체를 생성하고, 텍스트 조각 컬렉션에 텍스트 세그먼트를 추가한 뒤 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

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
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// TextBuilder 객체를 생성합니다
TextBuilder builder = new TextBuilder(page);

// 텍스트 조각을 PDF 페이지에 추가합니다
builder.AppendText(tf);

//문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


