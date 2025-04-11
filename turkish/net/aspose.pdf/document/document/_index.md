---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Document yapıcısı. Giriş akışından yeni bir Document örneği başlatın
type: docs
weight: 10
url: /tr/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

*input* akışından yeni bir Document örneği başlatın.

```csharp
public Document(Stream input)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | Stream | PDF belgesi içeren akış. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

*input* akışından yeni bir Document örneği başlatın.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | Stream | PDF belgesi içeren akış. |
| isManagedStream | Boolean | `true` olarak ayarlandığında, iç akış çıkıştan önce kapatılır; aksi takdirde, kapatılmaz. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

*input* akışından yeni bir Document örneği başlatın.

```csharp
public Document(Stream input, string password)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | Stream | Giriş akış nesnesi, ilgili PDF şifre korumalıdır. |
| password | String | Kullanıcı veya sahip şifresi. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

*input* akışından yeni bir Document örneği başlatın.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | Stream | PDF belgesi içeren akış. |
| password | String | Kullanıcı veya sahip şifresi. |
| isManagedStream | Boolean | `true` olarak ayarlandığında, iç akış çıkıştan önce kapatılır; aksi takdirde, kapatılmaz. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Sadece *filename* kullanarak Document başlatın. `Document` ile aynı.

```csharp
public Document(string filename)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | String | PDF belgesi dosyasının adı. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Sadece *filename* kullanarak Document başlatın. `Document` ile aynı.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | String | PDF belgesi dosyasının adı. |
| isManagedStream | Boolean | `true` olarak ayarlandığında, iç akış çıkıştan önce kapatılır; aksi takdirde, kapatılmaz. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Şifreli belge ile çalışmak için [`Document`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public Document(string filename, string password)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | String | Belge dosya adı. |
| password | String | Kullanıcı veya sahip şifresi. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Şifreli belge ile çalışmak için [`Document`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | String | Belge dosya adı. |
| password | String | Kullanıcı veya sahip şifresi. |
| isManagedStream | Boolean | `true` olarak ayarlandığında, iç akış çıkıştan önce kapatılır; aksi takdirde, kapatılmaz. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document() {#constructor}

Boş belgeyi başlatır.

```csharp
public Document()
```

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Versiyona göre boş belgeyi başlatır.

```csharp
public Document(PdfVersion version)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| version | PdfVersion | PDF versiyonu. |

### Ayrıca Bakınız

* enum [PdfVersion](../../pdfversion/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

PDF belgesini elde etmek için gerekli dönüştürme seçeneklerini sağlayarak mevcut bir belgeyi bir dosyadan açar.

```csharp
public Document(string filename, LoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | String | PDF belgesine dönüştürmek için giriş dosyası. |
| options | LoadOptions | *filename*'ı PDF belgesine dönüştürmek için özellikleri temsil eder. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../../loadoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

PDF belgesini elde etmek için gerekli dönüştürmeyi sağlayarak mevcut bir belgeyi bir akıştan açar.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | Stream | PDF belgesine dönüştürmek için giriş akışı. |
| options | LoadOptions | *input*'ı PDF belgesine dönüştürmek için özellikleri temsil eder. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../../loadoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)