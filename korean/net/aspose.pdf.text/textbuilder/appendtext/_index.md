---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder 메서드. Pdf 페이지에 텍스트 조각을 추가합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Pdf 페이지에 텍스트 조각을 추가합니다.

```csharp
public void AppendText(TextFragment textFragment)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textFragment | TextFragment | 텍스트 조각 객체입니다. |

## 예제

이 예제는 텍스트 조각 객체를 생성하고, 텍스트 세그먼트를 사용자 정의하며, 이를 Pdf 페이지에 추가하는 방법을 보여줍니다.

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

* 클래스 [TextFragment](../../textfragment/)
* 클래스 [TextBuilder](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Pdf 페이지에 텍스트 조각 목록을 추가합니다.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textFragments | List`1 | 텍스트 조각의 컬렉션입니다. |

### 참조

* 클래스 [TextFragment](../../textfragment/)
* 클래스 [TextBuilder](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)