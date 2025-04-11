---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: ComHelper metodu. Sadece dosya adını kullanarak belge oluşturur ve döndürür. Belge ile aynıdır
type: docs
weight: 20
url: /tr/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Sadece *dosya adı* kullanarak belge oluşturur ve döndürür. [`Document`](../../document/document/) ile aynıdır.

```csharp
public Document OpenFile(string filename)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | String | PDF belge dosyasının adı. |

### Dönüş Değeri

Belge nesnesi

### Ayrıca Bakınız

* sınıf [Document](../../document/)
* sınıf [ComHelper](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Şifreli belge ile çalışmak için [`Document`](../../document/) sınıfının yeni bir örneğini başlatır ve döndürür.

```csharp
public Document OpenFile(string filename, string password)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | String | Belge dosya adı. |
| şifre | String | Kullanıcı veya sahip şifresi. |

### Dönüş Değeri

Belge nesnesi

### Ayrıca Bakınız

* sınıf [Document](../../document/)
* sınıf [ComHelper](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Şifreli belge ile çalışmak için [`Document`](../../document/) sınıfının yeni bir örneğini başlatır.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | String | Belge dosya adı. |
| şifre | String | Kullanıcı veya sahip şifresi. |
| isManagedStream | Boolean | `true` olarak ayarlandığında iç akış çıkıştan önce kapatılır; aksi takdirde, kapatılmaz. |

### Dönüş Değeri

Belge nesnesi

### Ayrıca Bakınız

* sınıf [Document](../../document/)
* sınıf [ComHelper](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Gerekli dönüştürme seçeneklerini sağlayarak bir dosyadan mevcut bir belgeyi açar ve PDF belgesi alır.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | String | PDF belgesine dönüştürülecek giriş dosyası. |
| seçenekler | LoadOptions | *dosya adını* PDF belgesine dönüştürmek için özellikleri temsil eder. |

### Dönüş Değeri

Belge nesnesi

### Ayrıca Bakınız

* sınıf [Document](../../document/)
* sınıf [LoadOptions](../../loadoptions/)
* sınıf [ComHelper](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)