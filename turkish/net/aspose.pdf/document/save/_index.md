---
title: Save
second_title: Aspose.PDF for .NET API Referansı
description: Belgeyi aşamalı olarak kaydedin yani artımlı güncelleme tekniğini kullanarak.
type: docs
weight: 720
url: /tr/net/aspose.pdf/document/save/
---
## Save() {#save}

Belgeyi aşamalı olarak kaydedin (yani artımlı güncelleme tekniğini kullanarak).

```csharp
public void Save()
```

### Notlar

Belgeyi aşamalı olarak kaydetmek için belge dosyasını yazmak için açmalıyız. Bu nedenle Document sonraki kod parçacığında olduğu gibi yazılabilir akışla başlatılmalıdır: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // bazı değişiklikler yapın ve kaydedin belge aşamalı olarak doc.Save();

### Ayrıca bakınız

* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Belgeyi kaydetme seçenekleriyle kaydeder.

```csharp
public void Save(SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | SaveOptions | Seçenekleri kaydedin. |

### Ayrıca bakınız

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Belgeyi bir dosya biçimiyle birlikte yeni bir adla kaydeder.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFileName | String | Belgenin saklanacağı dosyanın yolu. |
| format | SaveFormat | Biçim seçenekleri. |

### Ayrıca bakınız

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Belgeyi bir dosya biçimiyle birlikte yeni bir adla kaydeder.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Belgenin depolanacağı akış. |
| format | SaveFormat | Biçim seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ArgumentException ne zaman[`HtmlSaveOptions`](../../htmlsaveoptions) bir metoda geçilir. Bir belgeyi html akışına kaydetme desteklenmez. Lütfen dosyaya kaydetme yöntemini kullanın. |

### Ayrıca bakınız

* enum [SaveFormat](../../saveformat)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

Belgeyi, kaydetme seçeneklerini ayarlayan yeni bir adla kaydeder.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFileName | String | Belgenin saklanacağı dosyanın yolu. |
| options | SaveOptions | Seçenekleri kaydedin. |

### Ayrıca bakınız

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Belgeyi kaydetme seçenekleriyle bir akışa kaydeder.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Belgenin depolanacağı akış. |
| options | SaveOptions | Seçenekleri kaydedin. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ArgumentException ne zaman[`HtmlSaveOptions`](../../htmlsaveoptions) bir metoda geçilir. Bir belgeyi html akışına kaydetme desteklenmez. Lütfen dosyaya kaydetme yöntemini kullanın. |

### Ayrıca bakınız

* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(HttpResponse, string, ContentDisposition, SaveOptions) {#save_8}

Belgeyi, kaydetme seçenekleriyle bir yanıt akışına kaydeder.

```csharp
public void Save(HttpResponse response, string outputFileName, ContentDisposition disposition, 
    SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| response | HttpResponse | HTTP yanıt bilgilerini kapsüller. |
| outputFileName | String | Basit dosya adı, yani yolsuz. |
| disposition | ContentDisposition | Bir MIME protokolü Content-Disposition üstbilgisini temsil eder. |
| options | SaveOptions | Seçenekleri kaydedin. |

### Ayrıca bakınız

* enum [ContentDisposition](../../contentdisposition)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

Belgeyi akışta depolar.

```csharp
public void Save(Stream output)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| output | Stream | Belge kabuğunun depolandığı akış. |

### Ayrıca bakınız

* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Belgeyi belirtilen dosyaya kaydeder.

```csharp
public void Save(string outputFileName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFileName | String | Belgenin saklanacağı dosyanın yolu. |

### Ayrıca bakınız

* class [Document](../../document)
* ad alanı [Aspose.Pdf](../../document)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
