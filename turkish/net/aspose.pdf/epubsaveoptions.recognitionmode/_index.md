---
title: EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Referansı
description: PDF dosyası genellikle sabit bir düzene sahiptir dönüştürülürken dönüştürme motoru orijinal belge yazarının amacını geri yüklemek ve akış düzeninde sonuç üretmek için gruplandırma ve çok düzeyli analiz gerçekleştirmeye çalışır. Bu özellik bu dönüşümü bunun için ayarlar. veya that içeriğin tanınması için istenen yöntem.
type: docs
weight: 2110
url: /tr/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

PDF dosyası (genellikle sabit bir düzene sahiptir) dönüştürülürken, dönüştürme motoru, orijinal belge yazarının amacını geri yüklemek ve akış düzeninde sonuç üretmek için gruplandırma ve çok düzeyli analiz gerçekleştirmeye çalışır. Bu özellik, bu dönüşümü bunun için ayarlar. veya that içeriğin tanınması için istenen yöntem.

```csharp
public enum RecognitionMode
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Flow | `0` | Tam tanıma modu, motor, orijinal belge yazarının amacını geri yüklemek ve akış düzeninde xhtml üretmek için gruplandırma ve çok düzeyli analiz gerçekleştirmeye çalışır. |
| PdfFlow | `1` | Bu dönüştürmenin ana fikri, pdf belgelerinin işlenmesi sırasında oluşan "doğal" içerik oluşturma sırasını kaydetmeye dayanır. Genel durumlarda pdf belgeleri yukarıdan aşağıya\sol-sağ oluşturma sırasını korur (bkz. ek yönergeleri.png ). Bu varsayım, to 'nin konumları (sabit yerleşim) olan Aps öğelerini HTML,EPUB,DOC. gibi akış biçimlerine dönüştürecek tek yollu bir algoritma oluşturmasını sağlar. çünkü EPUB formatı Kindle veya akıllı telefonları gibi e-okuyucular için geliştirildi. Bu cihazların ekran boyutu genellikle sıradan bir bilgisayarın ekran boyutundan daha küçüktür. Bu nedenle, EPUB belgelerinin içeriğinin, farklı boyutlardaki ekranlarda doğru oluşturma için akış biçiminde kaydedilmesi daha iyidir. Bu modda, her sütun önceki sütunun sonuna eklenecektir, bu, dönüştürülmüş belgenin sırasında mantıksal yapısını korumaya izin verir. EPUB okuyucularında "sayfalandırma". Bu başarı, bilimsel makalelerin veya dergi makalelerinin doğru bir şekilde oluşturulmasını sağlar. |
| Fixed | `2` | Bu mod, orijinal görünüm sayfalarını maksimum düzeyde korumak için hızlı ve iyidir, ancak ne yazık ki birçok EPUB okuyucusu sabit yerleşimli xhtml'yi desteklemiyor |

### Ayrıca bakınız

* class [EpubSaveOptions](../epubsaveoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
