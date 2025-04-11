---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Belge yöntemi. Belgeyi akışa kaydeder
type: docs
weight: 830
url: /tr/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Belgeyi akışa kaydeder.

```csharp
public void Save(Stream output)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | Stream | Belgenin kaydedileceği akış. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Belgeyi belirtilen dosyaya kaydeder.

```csharp
public void Save(string outputFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | String | Belgenin kaydedileceği dosyanın yolu. |

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save() {#save}

Belgeyi artımlı olarak kaydeder (yani artımlı güncelleme tekniği kullanarak).

```csharp
public void Save()
```

## Açıklamalar

Belgeyi artımlı olarak kaydetmek için belge dosyasını yazma için açmalıyız. Bu nedenle Document, aşağıdaki kod parçasında olduğu gibi yazılabilir bir akış ile başlatılmalıdır: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // bazı değişiklikler yapın ve belgeyi artımlı olarak kaydedin doc.Save();

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Belgeyi kaydetme seçenekleri ile kaydeder.

```csharp
public void Save(SaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | SaveOptions | Kaydetme seçenekleri. |

### Ayrıca Bakınız

* sınıf [SaveOptions](../../saveoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Belgeyi yeni bir ad ile birlikte bir dosya formatında kaydeder.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | String | Belgenin kaydedileceği dosyanın yolu. |
| format | SaveFormat | Format seçenekleri. |

### Ayrıca Bakınız

* enum [SaveFormat](../../saveformat/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Belgeyi yeni bir ad ile birlikte bir dosya formatında kaydeder.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Belgenin kaydedileceği akış. |
| format | SaveFormat | Format seçenekleri. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) bir metoda geçirildiğinde ArgumentException. Belgeyi html akışına kaydetmek desteklenmiyor. Lütfen dosyaya kaydetme yöntemini kullanın. |

### Ayrıca Bakınız

* enum [SaveFormat](../../saveformat/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Belgeyi yeni bir ad ile kaydeder ve kaydetme seçeneklerini ayarlar.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | String | Belgenin kaydedileceği dosyanın yolu. |
| options | SaveOptions | Kaydetme seçenekleri. |

### Ayrıca Bakınız

* sınıf [SaveOptions](../../saveoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Belgeyi kaydetme seçenekleri ile bir akışa kaydeder.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Belgenin kaydedileceği akış. |
| options | SaveOptions | Kaydetme seçenekleri. |

### İstisnalar

| istisna | durum |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) bir metoda geçirildiğinde ArgumentException. Belgeyi html akışına kaydetmek desteklenmiyor. Lütfen dosyaya kaydetme yöntemini kullanın. |

### Ayrıca Bakınız

* sınıf [SaveOptions](../../saveoptions/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)