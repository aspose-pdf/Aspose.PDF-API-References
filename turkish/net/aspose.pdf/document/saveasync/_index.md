---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Belge yöntemi. Belgeyi akışa kaydeder
type: docs
weight: 840
url: /tr/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Belgeyi akışa kaydeder.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | Stream | Belgenin kaydedileceği akış. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Belgeyi belirtilen dosyaya kaydeder.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | String | Belgenin kaydedileceği dosyanın yolu. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Belgeyi kademeli olarak kaydeder (yani, kademeli güncelleme tekniği kullanarak).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

## Açıklamalar

Belgeyi kademeli olarak kaydetmek için belge dosyasını yazma için açmalıyız. Bu nedenle, Document, aşağıdaki kod parçasında olduğu gibi yazılabilir bir akış ile başlatılmalıdır: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // bazı değişiklikler yapın ve belgeyi kademeli olarak kaydedin doc.Save();

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Belgeyi kaydetme seçenekleri ile kaydeder.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | SaveOptions | Kaydetme seçenekleri. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### Ayrıca Bakınız

* sınıf [SaveOptions](../../saveoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Belgeyi yeni bir ad ile ve dosya formatı ile kaydeder.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | String | Belgenin kaydedileceği dosyanın yolu. |
| format | SaveFormat | Format seçenekleri. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### Ayrıca Bakınız

* enum [SaveFormat](../../saveformat/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Belgeyi yeni bir ad ile ve dosya formatı ile kaydeder.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Belgenin kaydedileceği akış. |
| format | SaveFormat | Format seçenekleri. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) bir metoda geçirildiğinde ArgumentException. Belgeyi html akışına kaydetmek desteklenmiyor. Lütfen dosyaya kaydetme metodunu kullanın. |

### Ayrıca Bakınız

* enum [SaveFormat](../../saveformat/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Belgeyi yeni bir ad ile kaydederek kaydetme seçeneklerini ayarlar.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | String | Belgenin kaydedileceği dosyanın yolu. |
| options | SaveOptions | Kaydetme seçenekleri. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### Ayrıca Bakınız

* sınıf [SaveOptions](../../saveoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Belgeyi kaydetme seçenekleri ile bir akışa kaydeder.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Belgenin kaydedileceği akış. |
| options | SaveOptions | Kaydetme seçenekleri. |
| cancellationToken | CancellationToken | İptal tokeni. |

### Dönüş Değeri

Asenkron görev.

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) bir metoda geçirildiğinde ArgumentException. Belgeyi html akışına kaydetmek desteklenmiyor. Lütfen dosyaya kaydetme metodunu kullanın. |

### Ayrıca Bakınız

* sınıf [SaveOptions](../../saveoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)