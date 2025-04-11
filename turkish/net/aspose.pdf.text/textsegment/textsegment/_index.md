---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: TextSegment yapıcısı. TextSegment nesnesi oluşturur
type: docs
weight: 10
url: /tr/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

TextSegment nesnesi oluşturur.

```csharp
public TextSegment()
```

## Örnekler

Örnek, metin parçası nesnesi oluşturmayı, metin parçası koleksiyonuna bir metin segmenti eklemeyi ve bunu Pdf sayfasına eklemeyi göstermektedir.

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

### Ayrıca Bakınız

* sınıf [TextSegment](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

TextSegment nesnesi oluşturur.

```csharp
public TextSegment(string text)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | String | Metin segmentinin metni. |

## Örnekler

Örnek, metin parçası nesnesi oluşturmayı, metin parçası koleksiyonuna bir metin segmenti eklemeyi ve bunu Pdf sayfasına eklemeyi göstermektedir.

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

### Ayrıca Bakınız

* sınıf [TextSegment](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)