---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.DocumentPrivilege sınıfı. Pdf dosyasına erişim için ayrıcalıkları temsil eder. [`PdfFileSecurity`](../pdffilesecurity/) referansına bakın. Bu sınıfı kullanmanın 4 yolu vardır 1. Önceden tanımlanmış ayrıcalığı doğrudan kullanma. 2. Önceden tanımlanmış bir ayrıcalığa dayanarak bazı özel izinleri değiştirme. 3. Önceden tanımlanmış bir ayrıcalığa dayanarak bazı özel Adobe Professional izin kombinasyonlarını değiştirme. 4. yol2 ve yol3'ü karıştırma.
type: docs
weight: 4230
url: /tr/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege sınıfı

Pdf dosyasına erişim için ayrıcalıkları temsil eder. [`PdfFileSecurity`](../pdffilesecurity/) referansına bakın. Bu sınıfı kullanmanın 4 yolu vardır: 1. Önceden tanımlanmış ayrıcalığı doğrudan kullanma. 2. Önceden tanımlanmış bir ayrıcalığa dayanarak bazı özel izinleri değiştirme. 3. Önceden tanımlanmış bir ayrıcalığa dayanarak bazı özel Adobe Professional izin kombinasyonlarını değiştirme. 4. yol2 ve yol3'ü karıştırma.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Tüm izin verildi. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Dosyayı birleştirmeye izin verir. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Dosyayı kopyalamaya izin verir. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Kalitesiz baskıya izin verir. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Dosyadaki formları doldurmaya izin verir. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Tüm yasaklandı. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Dosyanın notlarını değiştirmeye izin verir. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Dosyayı değiştirmeye izin verir. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Dosyayı yazdırmaya izin verir. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Sadece ekranda okumaya izin verir. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Birleştirmeye izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Kopyalamaya izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Kalitesiz baskıya izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Formları doldurmaya izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Notları değiştirmeye izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | İçeriği değiştirmeye izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Yazdırmaya izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Ekran okuyucularına izin verip vermediğini ayarlar. true izin verir ve false yasaklar. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Belgenin ayrıcalık değişim seviyesini alır ve ayarlar. Adobe Professional'ın İzin Verilen Değişiklikler ayarlarına benzer. 0: Hiçbiri. 1: Sayfa ekleme, silme ve döndürme. 2: Form alanlarını doldurma ve mevcut imza alanlarını imzalama. 3: Yorum yapma, form alanlarını doldurma ve mevcut imza alanlarını imzalama. 4: Sayfaları çıkarmak hariç her şey. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Belgenin kopyalama seviyesini alır ve ayarlar. Adobe Professional'ın izin ayarlarına benzer. 0: Hiçbiri. 1: Görme engelliler için ekran okuyucu cihazları için metin erişimini etkinleştirir. 2: Metin, resim ve diğer içeriklerin kopyalanmasını etkinleştirir. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Belgenin yazdırma seviyesini alır ve ayarlar. Adobe Professional'ın Yazdırmaya İzin Verilen ayarlarına benzer. 0: Hiçbiri. 1: Düşük Çözünürlük (150 dpi). 2: Yüksek Çözünürlük. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | İki `DocumentPrivilege` nesnesini karşılaştırır. Karşılaştırılacak nesne. Bu örneğin ve değerin göreceli değerlerini belirten imzalı bir tam sayı. Sıfırdan küçükse bu örnek değerden küçüktür. Sıfırsa bu örnek değere eşittir. Sıfırdan büyükse bu örnek değerden büyüktür. |

## Örnekler

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)