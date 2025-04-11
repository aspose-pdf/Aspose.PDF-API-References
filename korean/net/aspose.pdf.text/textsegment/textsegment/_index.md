---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: TextSegment 생성자. TextSegment 객체를 생성합니다.
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

이 예제는 텍스트 조각 객체를 생성하고, 텍스트 조각 컬렉션에 텍스트 세그먼트를 추가한 다음, 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### 참조

* 클래스 [TextSegment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

TextSegment 객체를 생성합니다.

```csharp
public TextSegment(string text)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | 문자열 | 텍스트 세그먼트의 텍스트. |

## 예제

이 예제는 텍스트 조각 객체를 생성하고, 텍스트 조각 컬렉션에 텍스트 세그먼트를 추가한 다음, 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### 참조

* 클래스 [TextSegment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)