---
title: Convert
second_title: Aspose.PDF for .NET API Referansı
description: Kaynak biçimindeki kaynak dosyayı hedef biçimindeki hedef dosyaya dönüştürür.
type: docs
weight: 790
url: /tr/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Kaynak biçimindeki kaynak dosyayı, hedef biçimindeki hedef dosyaya dönüştürür.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcFileName | String | Kaynak dosya adı. |
| loadOptions | LoadOptions | Kaynak dosya biçimi. |
| dstFileName | String | Hedef dosya adı. |
| saveOptions | SaveOptions | Hedef dosya biçimi. |

### Ayrıca bakınız

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Kaynak biçimindeki akışı hedef biçimindeki hedef dosyaya dönüştürür.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcStream | Stream | Kaynak akışı. |
| loadOptions | LoadOptions | Kaynak akış biçimi. |
| dstFileName | String | Hedef dosya adı. |
| saveOptions | SaveOptions | Hedef dosya biçimi. |

### Ayrıca bakınız

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Kaynak biçimindeki kaynak dosyayı hedef biçimindeki akışa dönüştürür.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcFileName | String | Kaynak dosya adı. |
| loadOptions | LoadOptions | Kaynak dosya biçimi. |
| dstStream | Stream | Hedef akışı. |
| saveOptions | SaveOptions | Hedef akış biçimi. |

### Ayrıca bakınız

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Kaynak biçimindeki akışı hedef biçimindeki akışa dönüştürür.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| srcStream | Stream | Kaynak akışı. |
| loadOptions | LoadOptions | Kaynak akış biçimi. |
| dstStream | Stream | Hedef akışı. |
| saveOptions | SaveOptions | Hedef dosya biçimi. |

### Ayrıca bakınız

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputLogFileName | String | Yorumların saklanacağı dosyanın yolu. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |
| transparencyAction | ConvertTransparencyAction | Görüntü maskeli nesneler için eylem |

### Geri dönüş değeri

operasyon sonucu

### Ayrıca bakınız

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputLogStream | Stream | Yorumların depolanacağı akış. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |
| transparencyAction | ConvertTransparencyAction | Görüntü maskeli nesneler için eylem |

### Geri dönüş değeri

operasyon sonucu

### Ayrıca bakınız

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputLogFileName | String | Yorumların saklanacağı dosyanın yolu. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |

### Geri dönüş değeri

operasyon sonucu

### Ayrıca bakınız

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Belirtilen dönüştürme seçeneklerini kullanarak belgeyi dönüştürün

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | PdfFormatConversionOptions | PDF belgesini dönüştürmek için bir dizi seçenek |

### Geri dönüş değeri

operasyon sonucu

### Ayrıca bakınız

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Belgeyi dönüştürün ve hataları belirtilen dosyaya kaydedin.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| callback | CallBackGetHocr | Dönüştürülemeyen nesneler için eylem |

### Geri dönüş değeri

operasyon sonucu

### Ayrıca bakınız

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Belgeyi dönüştürün ve hataları belirtilen akışa kaydedin.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputLogStream | Stream | Yorumların depolanacağı akış. |
| format | PdfFormat | Pdf formatı. |
| action | ConvertErrorAction | Dönüştürülemeyen nesneler için eylem |

### Geri dönüş değeri

operasyon sonucu

### Ayrıca bakınız

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Düzeltmeyi uygulayarak belgeyi dönüştürün.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fixup | Fixup | Düzeltme türü. |
| outputLog | Stream | İşlem günlüğü. |
| onlyValidation | Boolean | Yalnızca belge doğrulama. |
| parameters | Object[] | Ayarlanamayan Düzeltme özellikleri. |

### Geri dönüş değeri

İşlem sonucu.

### Ayrıca bakınız

* enum [Fixup](../../fixup)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Düzeltmeyi uygulayarak belgeyi dönüştürün.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fixup | Fixup | Düzeltme türü. |
| outputLog | String | İşlem günlüğü. |
| onlyValidation | Boolean | Yalnızca belge doğrulama. |
| parameters | Object[] | Ayarlanamayan Düzeltme özellikleri. |

### Geri dönüş değeri

İşlem sonucu.

### Ayrıca bakınız

* enum [Fixup](../../fixup)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
