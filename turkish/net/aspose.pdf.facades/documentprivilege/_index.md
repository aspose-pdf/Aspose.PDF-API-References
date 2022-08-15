---
title: DocumentPrivilege
second_title: Aspose.PDF for .NET API Referansı
description: Pdf dosyasına erişim ayrıcalıklarını temsil eder. bkz.PdfFileSecurity./pdffilesecurity . Bu sınıfı kullanmanın 4 yolu vardır 1.Önceden tanımlanmış ayrıcalığı doğrudan kullanma. 2.Önceden tanımlanmış bir ayrıcalığı temel alır ve bazı özel izinleri değiştirir. 3.Önceden tanımlanmış bir ayrıcalığı temel alır ve bazı belirli Adobe Professional izin kombinasyonlarını değiştirir. 4. way2 ve way3. yollarını karıştırır
type: docs
weight: 2240
url: /tr/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Pdf dosyasına erişim ayrıcalıklarını temsil eder. bkz.[`PdfFileSecurity`](../pdffilesecurity) . Bu sınıfı kullanmanın 4 yolu vardır: 1.Önceden tanımlanmış ayrıcalığı doğrudan kullanma. 2.Önceden tanımlanmış bir ayrıcalığı temel alır ve bazı özel izinleri değiştirir. 3.Önceden tanımlanmış bir ayrıcalığı temel alır ve bazı belirli Adobe Professional izin kombinasyonlarını değiştirir. 4. way2 ve way3. yollarını karıştırır

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Tümüne izin verilir. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Dosyanın birleştirilmesine izin verir. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Dosyanın kopyalanmasına izin verir. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Azaltılmış yazdırmaya izin verir. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Dosyadaki formların doldurulmasına izin verir. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Her Şey Yasaktır. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Dosyanın ek açıklamalarının değiştirilmesine izin verir. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Dosyanın değiştirilmesine izin verir. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Dosyanın yazdırılmasına izin verir. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Yalnızca ekranda okumaya izin verir. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Montaja izin verilip verilmeyeceğini belirler. true izin verilir ve false yasaktır. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Kopyalamaya izin veren veya vermeyen izni ayarlar. true izin verilir ve false yasaktır. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Azaltılmış yazdırmaya izin veren veya vermeyen izni ayarlar. true izin verilir ve false yasaktır. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Formların doldurulmasına izin verilip verilmeyeceğini belirler. true izin verilir ve false yasaktır. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Açıklamaların değiştirilmesine izin verilip verilmeyeceğini belirler. true izin verilir ve false yasaktır. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | İçeriğin değiştirilmesine izin verilip verilmeyeceğini belirler. true izin verilir ve false yasaktır. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Yazdırmaya izin verilip verilmeyeceğini belirler. true izin verilir ve false yasaktır. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Ekran okuyuculara izin verilip verilmeyeceğini belirler. true izin verilir ve false yasaktır. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Belgenin ayrıcalığının değişiklik düzeyini ayarlar. Tıpkı Adobe Professional'ın Değişikliklere İzin Verildiği ayarlarında olduğu gibi. 0: Yok. 1: Sayfaları ekleme, silme ve döndürme. 2: Form alanlarını doldurma ve mevcut imza alanlarını imzalama. 3: Yorum yapma, form alanlarını doldurma ve mevcutları imzalama imza alanları. 4: Sayfaların çıkarılması dışında herhangi biri. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Belge ayrıcalığının kopyalama düzeyini ayarlar. Tıpkı Adobe Professional'ın izin ayarları gibi. 0: Yok. 1: Görme engelliler için ekran okuyucu aygıtlar için metin erişimini etkinleştirin. 2: Metin, resim ve diğer içeriğin kopyalanmasını etkinleştir. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Belge ayrıcalığının yazdırma düzeyini ayarlar. Tıpkı Adobe Professional'ın Yazdırmaya İzin Verilen ayarlarında olduğu gibi. 0: Yok. 1: Düşük Çözünürlük (150 dpi). 2: Yüksek Çözünürlük. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | İkisini karşılaştırır[`DocumentPrivilege`](../documentprivilege) nesneler.  Karşılaştırılacak nesne. Bu örneğin ve değerin göreli değerlerini gösteren işaretli bir tamsayı. Sıfırdan küçük bu örnek değerden küçük. Sıfır bu örnek değere eşittir. Sıfırdan büyük bu örnek değerden büyük. |

### Örnekler

```csharp
[C#]	
//Yol1: Önceden tanımlanmış ayrıcalığı doğrudan kullanma.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Önceden tanımlanmış bir ayrıcalığa dayalıdır ve bazı özel izinleri değiştirir.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Önceden tanımlanmış bir ayrıcalığı temel alır ve bazı özel Adobe Professional izinleri kombinasyonunu değiştirir.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: way2 ve way3'ü karıştırır
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Önceden tanımlanmış ayrıcalığı doğrudan kullanma.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Önceden tanımlanmış bir ayrıcalığa dayanarak ve bazı özel izinleri değiştirin.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Önceden tanımlanmış bir ayrıcalığa dayanarak ve bazı belirli Adobe Professional izinleri kombinasyonunu değiştirin.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: way2 ve way3'ü karıştırır
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Ayrıca bakınız

* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
