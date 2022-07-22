---
title: ReplaceText
second_title: Aspose.PDF for .NET API Referansı
description: Belirtilen sayfadaki PDF dosyasındaki metni değiştirir.TextStateaspose.pdf.text/textstate nesne yazı tipi ailesi renk değiştirilecek metin olarak belirtilebilir.
type: docs
weight: 450
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Belirtilen sayfadaki PDF dosyasındaki metni değiştirir.[`TextState`](../../../aspose.pdf.text/textstate) nesne (yazı tipi ailesi, renk) değiştirilecek metin olarak belirtilebilir.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| thePage | Int32 | Sayfa numarası (0 "tüm sayfalar" anlamına gelir). |
| destString | String | Değiştirilen dize. |
| textState | TextState | Metin durumu (Metin Rengi, Yazı Tipi vb.). |

### Geri dönüş değeri

Değiştirme yapıldıysa true değerini döndürür.

### Örnekler

Örnek, PDF belgesinin ilk sayfasındaki metnin nasıl değiştirileceğini ve[`TextState`](../../../aspose.pdf.text/textstate) yeni metin için metin özellikleri.

```csharp
// belgeyi aç
Document doc = new Document(inFile);

// Font oluştur ve gömülü olarak işaretle
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// metni düzenlemek için PdfContentEditor nesnesi oluşturun
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// textState nesnesi oluştur
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// metni belirtilen yazı tipiyle değiştir
editor.ReplaceText("hello world", 1, "hi world", textState);

// belgeyi kaydet
doc.Save(outFile);
```

### Ayrıca bakınız

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

PDF dosyasındaki metni değiştirir.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| destString | String | Dize değiştiriliyor. |

### Geri dönüş değeri

Değiştirme yapıldıysa true değerini döndürür.

### Örnekler

Örnek, PDF belgesindeki metnin nasıl değiştirileceğini gösterir.

```csharp
// belgeyi aç
Document doc = new Document(inFile);

// metni düzenlemek için PdfContentEditor nesnesi oluşturun
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// metni değiştir 
editor.ReplaceText("hello world", "hi world");

// belgeyi kaydet
doc.Save(outFile);
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Belirtilen sayfadaki PDF dosyasındaki metni değiştirir.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcString | String | Değiştirilecek iğne. |
| thePage | Int32 | Sayfa numarası (tüm sayfalar için 0) |
| destString | String | Dize değiştiriliyor. |

### Geri dönüş değeri

Değiştirme yapıldıysa true değerini döndürür.

### Örnekler

Örnek, belirtilen sayfada PDF belgesindeki metnin nasıl değiştirileceğini gösterir.

```csharp
// belgeyi aç
Document doc = new Document(inFile);

// metni düzenlemek için PdfContentEditor nesnesi oluşturun
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// metni değiştir 
editor.ReplaceText("hello world", 1, "hi world");

// belgeyi kaydet
doc.Save(outFile);
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Belirtilen kullanarak PDF dosyasındaki metni değiştirir[`TextState`](../../../aspose.pdf.text/textstate) nesne.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize |
| destString | String | dize değiştiriliyor |
| textState | TextState | Metin durumu (Metin Rengi, Yazı Tipi vb.) |

### Geri dönüş değeri

Değiştirme yapıldıysa true değerini döndürür.

### Örnekler

Örnek, metnin nasıl değiştirileceğini ve[`TextState`](../../../aspose.pdf.text/textstate) yeni metin için metin özellikleri.

```csharp
// belgeyi aç
Document doc = new Document(inFile);

// Font oluştur ve gömülü olarak işaretle
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// metni düzenlemek için PdfContentEditor nesnesi oluşturun
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// textState nesnesi oluştur
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// metni belirtilen yazı tipiyle değiştir
editor.ReplaceText("hello world", "hi world", textState);

// belgeyi kaydet
doc.Save(outFile);
```

### Ayrıca bakınız

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

PDF dosyasındaki metni değiştirir ve yazı tipi boyutunu ayarlar.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcString | String | Değiştirilecek dize. |
| destString | String | Dize değiştiriliyor. |
| fontSize | Int32 | Yazı Boyutu. |

### Geri dönüş değeri

Değiştirme yapıldıysa true değerini döndürür.

### Örnekler

Örnek, metnin nasıl değiştirileceğini ve yeni metin için yazı tipi boyutunun nasıl ayarlanacağını gösterir.

```csharp
// belgeyi aç
Document doc = new Document(inFile);

// Font oluştur ve gömülü olarak işaretle
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// metni düzenlemek için PdfContentEditor nesnesi oluşturun
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// metni belirtilen yazı tipiyle değiştir
editor.ReplaceText("hello world", "hi world", 14);

// belgeyi kaydet
doc.Save(outFile);
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
