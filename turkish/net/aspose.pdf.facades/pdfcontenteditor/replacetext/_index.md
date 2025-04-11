---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. Değiştirilen metin için TextState nesnesi yazı tipi ailesi rengi belirtilebilir
type: docs
weight: 450
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. [`TextState`](../../../aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) değiştirilen metin için belirtilebilir.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| thePage | Int32 | Sayfa numarası (0 "tüm sayfalar" anlamına gelir). |
| destString | String | Değiştirilen dize. |
| textState | TextState | Metin durumu (Metin Rengi, Yazı tipi vb). |

### Dönüş Değeri

Değiştirmenin yapılıp yapılmadığını belirtmek için true döner.

## Örnekler

Örnek, PDF belgesinin ilk sayfasındaki metni nasıl değiştireceğinizi ve yeni metin için [`TextState`](../../../aspose.pdf.text/textstate/) metin özelliklerini nasıl ayarlayacağınızı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### Ayrıca Bakınız

* sınıf [TextState](../../../aspose.pdf.text/textstate/)
* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

PDF dosyasındaki metni değiştirir.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| destString | String | Değiştiren dize. |

### Dönüş Değeri

Değiştirmenin yapılıp yapılmadığını belirtmek için true döner.

## Örnekler

Örnek, PDF belgesindeki metni nasıl değiştireceğinizi gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Belirtilen sayfadaki PDF dosyasındaki metni değiştirir.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| thePage | Int32 | Sayfa numarası (tüm sayfalar için 0) |
| destString | String | Değiştiren dize. |

### Dönüş Değeri

Değiştirmenin yapılıp yapılmadığını belirtmek için true döner.

## Örnekler

Örnek, belirtilen sayfadaki PDF belgesindeki metni nasıl değiştireceğinizi gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Belirtilen [`TextState`](../../../aspose.pdf.text/textstate/) nesnesini kullanarak PDF dosyasındaki metni değiştirir.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize |
| destString | String | Değiştiren dize |
| textState | TextState | Metin durumu (Metin Rengi, Yazı tipi vb) |

### Dönüş Değeri

Değiştirmenin yapılıp yapılmadığını belirtmek için true döner.

## Örnekler

Örnek, metni nasıl değiştireceğinizi ve yeni metin için [`TextState`](../../../aspose.pdf.text/textstate/) metin özelliklerini nasıl ayarlayacağınızı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### Ayrıca Bakınız

* sınıf [TextState](../../../aspose.pdf.text/textstate/)
* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

PDF dosyasındaki metni değiştirir ve yazı tipi boyutunu ayarlar.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| destString | String | Değiştiren dize. |
| fontSize | Int32 | Yazı tipi boyutu. |

### Dönüş Değeri

Değiştirmenin yapılıp yapılmadığını belirtmek için true döner.

## Örnekler

Örnek, metni nasıl değiştireceğinizi ve yeni metin için yazı tipi boyutunu nasıl ayarlayacağınızı gösterir.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)