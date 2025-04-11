---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Belge yöntemi. Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet
type: docs
weight: 580
url: /tr/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputLogFileName | String | Yorumların saklanacağı dosyanın yolu. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |
| transparencyAction | ConvertTransparencyAction | Resim maskeli nesneler için eylem |

### Dönüş Değeri

İşlem sonucu

### Ayrıca Bakınız

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputLogStream | Stream | Yorumların saklanacağı akış. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |
| transparencyAction | ConvertTransparencyAction | Resim maskeli nesneler için eylem |

### Dönüş Değeri

İşlem sonucu

### Ayrıca Bakınız

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Belgeyi dönüştür ve hataları belirtilen dosyaya kaydet.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputLogFileName | String | Yorumların saklanacağı dosyanın yolu. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |

### Dönüş Değeri

İşlem sonucu

### Ayrıca Bakınız

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Belgeyi belirtilen dönüştürme seçeneklerini kullanarak dönüştür

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | PdfFormatConversionOptions | PDF belgesini dönüştürmek için seçenekler seti |

### Dönüş Değeri

İşlem sonucu

### Ayrıca Bakınız

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Belge içindeki resimleri tanıyın ve üzerine hocr dizeleri ekleyin.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Hocr tanıma ile işlenecek resimler için eylem. |
| flattenImages | Boolean | PDF resimlerindeki metin maskelerin mekanizması kullanılarak boyanabilir, bu durumda resimler düzleştirilmelidir. |

### Dönüş Değeri

İşlem sonucu. Belge içinde resim yoksa !:false döner.

### Ayrıca Bakınız

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Belge içindeki resimleri tanıyın ve üzerine hocr dizeleri ekleyin.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | CallBackGetHocr | Hocr tanıma ile işlenecek resimler için eylem. |
| flattenImages | Boolean | PDF resimlerindeki metin maskelerin mekanizması kullanılarak boyanabilir, bu durumda resimler düzleştirilmelidir. |

### Dönüş Değeri

İşlem sonucu. Belge içinde resim yoksa !:false döner.

### Ayrıca Bakınız

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Belgeyi dönüştür ve hataları belirtilen akışa kaydet.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputLogStream | Stream | Yorumların saklanacağı akış. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |

### Dönüş Değeri

İşlem sonucu

### Ayrıca Bakınız

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Düzeltme uygulayarak belgeyi dönüştür.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fixup | Fixup | Düzeltme türü. |
| outputLog | Stream | Sürecin kaydı. |
| onlyValidation | Boolean | Sadece belge doğrulaması. |
| parameters | Object[] | Ayarlanamayan Düzeltme özellikleri. |

### Dönüş Değeri

İşlem sonucu.

### Ayrıca Bakınız

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Düzeltme uygulayarak belgeyi dönüştür.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fixup | Fixup | Düzeltme türü. |
| outputLog | String | Sürecin kaydı. |
| onlyValidation | Boolean | Sadece belge doğrulaması. |
| parameters | Object[] | Ayarlanamayan Düzeltme özellikleri. |

### Dönüş Değeri

İşlem sonucu.

### Ayrıca Bakınız

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Kaynak dosyayı kaynak formatında hedef dosyaya hedef formatında dönüştür.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcFileName | String | Kaynak dosya adı. |
| loadOptions | LoadOptions | Kaynak dosya formatı. |
| dstFileName | String | Hedef dosya adı. |
| saveOptions | SaveOptions | Hedef dosya formatı. |

### Ayrıca Bakınız

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Kaynak formatındaki akışı hedef dosyaya hedef formatında dönüştür.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcStream | Stream | Kaynak akış. |
| loadOptions | LoadOptions | Kaynak akış formatı. |
| dstFileName | String | Hedef dosya adı. |
| saveOptions | SaveOptions | Hedef dosya formatı. |

### Ayrıca Bakınız

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Kaynak dosyayı kaynak formatında hedef akışta hedef formatında dönüştür.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcFileName | String | Kaynak dosya adı. |
| loadOptions | LoadOptions | Kaynak dosya formatı. |
| dstStream | Stream | Hedef akış. |
| saveOptions | SaveOptions | Hedef akış formatı. |

### Ayrıca Bakınız

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Kaynak formatındaki akışı hedef formatındaki akışa dönüştür.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| srcStream | Stream | Kaynak akış. |
| loadOptions | LoadOptions | Kaynak akış formatı. |
| dstStream | Stream | Hedef akış. |
| saveOptions | SaveOptions | Hedef dosya formatı. |

### Ayrıca Bakınız

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)