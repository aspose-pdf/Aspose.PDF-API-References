---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.EncryptionOptions sınıfı. Güvenlik eklentisi için Şifreleme Seçeneklerini temsil eder
type: docs
weight: 8540
url: /tr/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions sınıfı

[`Security`](../security/) eklentisi için Şifreleme Seçeneklerini temsil eder.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Varsayılan seçeneklerle `EncryptionOptions` nesnesinin yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | İşlem tamamlandıktan sonra giriş akışlarını kapatır. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | İşlem tamamlandıktan sonra çıkış akışlarını kapatır. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Kriptografik algoritma, ayrıntılar için [`CryptoAlgorithm`](./cryptoalgorithm/) sayfasına bakın. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Belge izinleri, ayrıntılar için [`Permissions`](../../aspose.pdf/permissions/) sayfasına bakın. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions eklentisi veri koleksiyonunu döndürür. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Kaydetme işlemi sonuçları için eklenen hedeflerin koleksiyonunu alır. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Sahip parolası. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Kullanıcı parolası. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer eklentisi veri koleksiyonuna yeni bir veri kaynağı ekler. |

### Ayrıca Bakınız

* sınıf [OrganizerBaseOptions](../organizerbaseoptions/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)