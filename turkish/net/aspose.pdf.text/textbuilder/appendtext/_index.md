---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder metodu. Pdf sayfasına metin parçası ekler
type: docs
weight: 30
url: /tr/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Pdf sayfasına metin parçası ekler

```csharp
public void AppendText(TextFragment textFragment)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFragment | TextFragment | Metin parçası nesnesi. |

## Örnekler

Örnek, metin parçası nesnesi oluşturmayı, metin segmentlerini özelleştirmeyi ve bunu Pdf sayfasına eklemeyi gösterir.

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

* sınıf [TextFragment](../../textfragment/)
* sınıf [TextBuilder](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Pdf sayfasına metin parçaları listesini ekler.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFragments | List`1 | Metin parçaları koleksiyonu |

### Ayrıca Bakınız

* sınıf [TextFragment](../../textfragment/)
* sınıf [TextBuilder](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)