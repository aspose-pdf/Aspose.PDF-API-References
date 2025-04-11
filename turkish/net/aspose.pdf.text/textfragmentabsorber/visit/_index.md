---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber metodu. Belirtilen sayfada arama yapar
type: docs
weight: 150
url: /tr/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Belirtilen sayfada arama yapar.

```csharp
public override void Visit(Page page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Page | PDF belge sayfa nesnesi. |

## Örnekler

Örnek, ilk PDF belge sayfasında metin bulmayı ve metni değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Belirtilen belgede arama yapar.

```csharp
public override void Visit(Document pdf)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdf | Document | PDF belge nesnesi. |

## Örnekler

Örnek, PDF belgesinde metin bulmayı ve tüm arama sonuçlarının metnini değiştirmeyi gösterir.

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

### Ayrıca Bakınız

* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Belirtilen form nesnesinde arama yapar.

```csharp
public void Visit(XForm xForm)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xForm | XForm | Pdf form nesnesi. |

### Ayrıca Bakınız

* sınıf [XForm](../../../aspose.pdf/xform/)
* sınıf [TextFragmentAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)