---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptionsRecognitionMode enum. Genellikle sabit düzeni olan PDF dosyası dönüştürülürken, dönüştürme motoru orijinal belge yazarının niyetini geri yüklemek ve akış düzeninde sonuç üretmek için gruplama ve çok seviyeli analiz yapmaya çalışır. Bu özellik, içeriğin tanınması için bu veya o istenen yönteme göre dönüşümü ayarlar.
type: docs
weight: 4070
url: /tr/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumerasyonu

PDF dosyası (genellikle sabit düzeni olan) dönüştürülürken, dönüştürme motoru orijinal belge yazarının niyetini geri yüklemek ve akış düzeninde sonuç üretmek için gruplama ve çok seviyeli analiz yapmaya çalışır. Bu özellik, içeriğin tanınması için bu veya o istenen yönteme göre dönüşümü ayarlar.

```csharp
public enum RecognitionMode
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| Akış | `0` | Tam tanıma modu, motor gruplama ve çok seviyeli analiz yapmaya çalışarak orijinal belge yazarının niyetini geri yüklemeye ve akış düzeninde xhtml üretmeye çalışır. |
| PdfAkış | `1` | Bu dönüşümün ana fikri, pdf belgelerinin işlenmesi sırasında oluşan içeriğin "doğal" sırasını korumaya dayanmaktadır. Genel durumlarda pdf belgeleri yukarıdan aşağıya, soldan sağa render sırasını korur (bkz. ek yönlendirmeler.png). Bu varsayım, konumları (sabit düzen) olan Aps öğelerini HTML, EPUB, DOC gibi akış formatlarına dönüştürecek tek yol algoritması oluşturmayı sağlar. Bu mod, PDF(APS) den EPUB'a dönüştürme için özellikle yararlı olacaktır, çünkü EPUB formatı Kindle veya akıllı telefonlar gibi e-okuyucular için geliştirilmiştir. Bu cihazların ekran boyutu genellikle sıradan bir PC'nin ekran boyutundan daha küçüktür. Bu nedenle, EPUB belgelerinin içeriğinin farklı boyutlardaki ekranlarda doğru render edilmesi için akış formatında saklanması daha iyidir. Bu modda her sütun, önceki sütunun sonuna eklenir, bu da "sayfalama" sırasında dönüştürülen belgenin mantıksal yapısını korumayı sağlar. Bu başarı, bilimsel veya dergi makalelerinin doğru bir şekilde render edilmesini sağlar. |
| Sabit | `2` | Bu mod hızlıdır ve orijinal sayfa görünümünü maksimum düzeyde korumak için iyidir, ancak ne yazık ki birçok EPUB okuyucu sabit düzenli xhtml'i desteklememektedir. |

### Ayrıca Bakınız

* sınıf [EpubSaveOptions](../epubsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)