---
title: Form
second_title: Aspose.PDF for .NET API Referansı
description: Acro form nesnesini temsil eden sınıf.
type: docs
weight: 2300
url: /tr/net/aspose.pdf.facades/form/
---
## Form class

Acro form nesnesini temsil eden sınıf.

```csharp
public sealed class Form : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Form](form#constructor)() | Parametresiz Form Yapısı. |
| [Form](form#constructor_1)(Document) | Yeniyi başlatır[`Form`](../form) temelinde nesne*document* . |
| [Form](form#constructor_4)(Stream) | Form için oluşturucu. |
| [Form](form#constructor_8)(string) | Form Oluşturucusu. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | İşlem sonucu ek olarak HttpResponse nesnelerinde depolandığında ekin adını alır veya ayarlar. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | İşlem sonucu HttpResponse nesnesine depolandığında içeriğin nasıl depolanacağını alır veya ayarlar. Olası değer: satır içi / ek. Varsayılan: satır içi. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | PDF dosya biçimini ayarlar. Sonuç dosyası, belirtilen dosya biçiminde kaydedilecektir. Bu özellik belirtilmezse, dosya dönüştürme yapılmadan varsayılan PDF formatında kaydedilecektir. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Formdaki alan adlarının listesini alır. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Tüm form gönderme düğmesi adlarını alır. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Son içe aktarma işleminin sonucu. Her alan için içe aktarmanın sonucunu açıklayan nesne dizisi. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | İşlem sonucunun depolanacağı Response nesnesini alır veya ayarlar. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Sonuç HttpResponse. olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| override [Close](../../aspose.pdf.facades/form/close)() | Açılan dosyaları herhangi bir değişiklik yapmadan kapatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | pdf alanlarının içeriğini fdf akışına aktarır. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | pdf alanlarının içeriğini xml akışına aktarır. Düğme alanının değeri dışa aktarılmaz. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | pdf alanlarının içeriğini xml akışına aktarır. Düğme alanının değeri dışa aktarılmaz. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | XFA veri paketini çıkarır |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Barkod alanını tam nitelikli alan adına göre doldurun. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Onay kutusu alanını bir boole değeriyle doldurur. Uyarı: Yalnızca Check Box'a uygulanır. Lütfen unutmayın, Aspose.Pdf.Facades yalnızca tam alan adlarını destekler ve Aspose.Pdf'nin aksine kısmi alan adlarıyla çalışmaz .Kit; Örneğin, alanın tam adı "Form.Subform.CheckBoxField" ise, "CheckBoxField" yerine tam adı belirtmelisiniz. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Radyo kutusu alanını tam nitelikli alan adına göre geçerli bir dizin değeriyle doldurur. Alanları doldurmadan önce yalnızca alanın adının bilinmesi gerekir. Değer, indeksi ile belirtilebilirken. Uyarı: Yalnızca Radio Box, Combo Box ve List Box alanlarına uygulanabilir. Aspose.Pdf.Facades'in yalnızca tam alan adlarını desteklediğini ve kısmi alan adlarıyla çalışmadığını lütfen unutmayın. Aspose.Pdf.Kit'in aksine; Örneğin, alanın tam adı "Form.Subform.ListBoxField" ise, "ListBoxField" yerine tam adı belirtmelisiniz. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Alanı, tam nitelikli alan adına göre geçerli bir değerle doldurur. Alanları doldurmadan önce, her alanın adı ve buna karşılık gelen geçerli değerleri bilinmelidir. Hem alanların adı hem de değerleri büyük/küçük harf duyarlıdır. Lütfen şunu unutmayın: Aspose.Pdf.Facades yalnızca tam alan adlarını destekler ve Aspose.Pdf.Kit; 'nin aksine kısmi alan adlarıyla çalışmaz. "Metin alanı". Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Bir alanı birden çok seçimle doldurun.Not: yalnızca AcroForm Liste Kutusu Alanı için. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Alanı belirtilen değerle doldurur. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Metin kutusu alanlarını bir metin değerleriyle doldurur ve belgeyi kaydeder. İmzalı belgeler için geçerlidir. Uyarı: Yalnızca Metin Kutusuna uygulanır. Hem alanların adı hem de değerleri büyük/küçük harfe duyarlıdır. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | FillImageField'in aşırı yükleme işlevi. Giriş, bir görüntü akışıdır. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Bir görüntüyü, tam nitelikli alan adına göre görünümü olarak mevcut düğme alanına yapıştırır. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Tüm alanları düzleştirir. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Belirtilen alanı tam nitelikli alan adıyla düzleştirir. Diğer tüm alanlar değiştirilemez olarak kalacaktır. fieldName geçersizse, tüm alanlar değiştirilemez olarak kalacaktır. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Radyo düğmesi seçenek alanları için geçerli değeri döndürür. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Alan adına göre radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu yöntemin radyo düğmesi grupları için anlamı vardır. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Alan adına göre alanın değerini alır. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Tüm görünüm niteliklerini içeren FrofmFieldFacade nesnesini döndürür. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Alanın bayraklarını döndürür. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Metin alanı sınırlamasını alın. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Alan türünü döndürür. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Kısa alan adına göre tam alan adını alır. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Her karakterin biçimlendirme bilgisi dahil olmak üzere Zengin Metin alanının değerini alın. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Gönder düğmesinin gönderim flags değerini döndürür |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Alanların içeriğini fdf dosyasından içe aktarır ve yeni pdf'ye koyar. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni pdf'ye koyar. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Alanların içeriğini xml dosyasından içe aktarır ve bunları yeni pdf'ye koyar. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Alanların içeriğini xml dosyasından içe aktarır ve bunları yeni pdf'ye koyar. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Alanın gerekli olup olmadığını belirler. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Bir alanı yeniden adlandırır. AcroForm alanı veya XFA alanı uygundur. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Belgeyi belirtilen akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Belgeyi belirtilen dosyaya kaydeder. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | XFA verilerini belirtilen veri paketiyle değiştirir. Veri paketi ExtractXfaData kullanılarak çıkarılabilir. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Alan içe aktarılırsa sonucu açıklayan sınıf. |
| enum [ImportStatus](form.importstatus) | İçe aktarılan alanın durumu |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
