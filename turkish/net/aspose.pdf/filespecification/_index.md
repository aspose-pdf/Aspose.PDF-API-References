---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification sınıfı. Gömülü dosyayı temsil eden sınıf
type: docs
weight: 4850
url: /tr/net/aspose.pdf/filespecification/
---
## FileSpecification sınıfı

Gömülü dosyayı temsil eden sınıf.

```csharp
public sealed class FileSpecification : IDisposable
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Yeni boş dosya spesifikasyonu oluşturur. |
| [FileSpecification](filespecification/#constructor_3)(string) | FileSpecification için yapıcı |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Dosya spesifikasyonu için yapıcı. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | FileSpecification için yapıcı. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | FileSpecification için yapıcı. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | FileSpecification için yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | İlişkili dosya ilişkisi. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Dosya spesifikasyonunun bir koleksiyon öğesini alır. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | İçerik dosyasını alır veya ayarlar. Bu özellik, belleğe yüklenen verileri döndürür ve büyük veriler için bellek yetersizliği hatasına neden olabilir. Bellek kullanımını azaltmak için lütfen StreamContents kullanın. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Dosya spesifikasyonu ile ilişkili metni alır veya ayarlar. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Kodlama formatını alır veya ayarlar. Olası değerler: Zip - dosya ZIP ile sıkıştırılmış, None - dosya sıkıştırılmamış. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Şifreli yükü alır. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Dosya sisteminin adını alır veya ayarlar. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Eğer doğruysa, dosyanın içeriği dosya spesifikasyonuna dahil edilecektir. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Gömülü dosyanın alt türünü alır |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Dosya spesifikasyonu adını alır veya ayarlar. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Dosya parametrelerini alır. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Dosyanın içeriğini akış olarak alır. İçerik belleğe yüklenmez, bu da bellek kullanımını azaltır. Ancak bu akış konumlandırmayı ve Length özelliğini desteklemez. Bu özelliklere ihtiyacınız varsa lütfen bunun yerine Contents özelliğini kullanın. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Dosya spesifikasyonu unicode adını alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | İçerikleri serbest bırakır. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Uygulamaya özgü parametreyi alır. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Uygulamaya özgü parametreyi ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)