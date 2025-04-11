---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode enum. Bir PDF belgesinin nasıl bir kelime işleme belgesine dönüştürüleceğini kontrol etmeye olanak tanır
type: docs
weight: 3770
url: /tr/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumerasyonu

Bir PDF belgesinin nasıl bir kelime işleme belgesine dönüştürüleceğini kontrol etmeye olanak tanır.

```csharp
public enum RecognitionMode
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| Textbox | `0` | Bu mod hızlıdır ve PDF dosyasının orijinal görünümünü maksimum düzeyde korumak için iyidir, ancak ortaya çıkan belgenin düzenlenebilirliği sınırlı olabilir. |
| Flow | `1` | Tam tanıma modu, motor gruplama ve çok seviyeli analiz yaparak orijinal belge yazarının niyetini geri yükler ve maksimum düzeyde düzenlenebilir bir belge üretir. Dezavantajı, çıktı belgesinin orijinal PDF dosyasından farklı görünebileceğidir. |
| EnhancedFlow | `2` | Tablo tanımasını destekleyen alternatif bir Akış modudur. |

## Notlar

Sonuçta elde edilen belge fazla düzenlenmeyecekse Textbox modunu kullanın. Textbox'lar, yapılacak çok şey yoksa kolayca değiştirilebilir.

Çıktı belgesinin daha fazla düzenlenmesi gerekiyorsa Akış modunu kullanın. Akış modundaki paragraflar ve metin satırları, metni kolayca değiştirmeye olanak tanır, ancak desteklenmeyen biçimlendirme nesneleri Textbox moduna göre daha kötü görünecektir.

### Ayrıca Bakınız

* sınıf [DocSaveOptions](../docsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)