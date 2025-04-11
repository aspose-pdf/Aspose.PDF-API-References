---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber yapıcısı. TextAbsorber'ın yeni bir örneğini başlatır
type: docs
weight: 10
url: /tr/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

[`TextAbsorber`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public TextAbsorber()
```

## Açıklamalar

Metin çıkarımı yapar ve çıkarılan metne [`Text`](../text/) nesnesi aracılığıyla erişim sağlar.

## Örnekler

Örnek, PDF belgesinin tüm sayfalarından metin çıkarmayı göstermektedir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Ayrıca Bakınız

* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Çıkarma seçenekleri ile [`TextAbsorber`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Metin çıkarım seçenekleri |

## Açıklamalar

Metin çıkarımı yapar ve çıkarılan metne [`Text`](../text/) nesnesi aracılığıyla erişim sağlar.

## Örnekler

Örnek, PDF belgesinin tüm sayfalarından metin çıkarmayı göstermektedir.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Ayrıca Bakınız

* sınıf [TextExtractionOptions](../../textextractionoptions/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Çıkarma ve metin arama seçenekleri ile [`TextAbsorber`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Metin çıkarım seçenekleri |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri |

## Açıklamalar

Metin çıkarımı yapar ve çıkarılan metne [`Text`](../text/) nesnesi aracılığıyla erişim sağlar.

### Ayrıca Bakınız

* sınıf [TextExtractionOptions](../../textextractionoptions/)
* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Metin arama seçenekleri ile [`TextAbsorber`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Metin arama seçenekleri |

## Açıklamalar

Metin çıkarımı yapar ve çıkarılan metne [`Text`](../text/) nesnesi aracılığıyla erişim sağlar.

### Ayrıca Bakınız

* sınıf [TextSearchOptions](../../textsearchoptions/)
* sınıf [TextAbsorber](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)