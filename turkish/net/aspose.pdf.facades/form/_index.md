---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Form sınıfı. Acro form nesnesini temsil eden sınıf
type: docs
weight: 4290
url: /tr/net/aspose.pdf.facades/form/
---
## Form sınıfı

Acro form nesnesini temsil eden sınıf.

```csharp
public sealed class Form : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Form](form/#constructor)() | Parametresiz Form yapıcısı. |
| [Form](form/#constructor_1)(Document) | *belge* temelinde yeni `Form` nesnesini başlatır. |
| [Form](form/#constructor_4)(Stream) | Form için yapıcı. |
| [Form](form/#constructor_7)(string) | Form yapıcısı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya varsayılan PDF formatında kaydedilecektir. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Form üzerindeki alan adlarının listesini alır. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Tüm form gönderme buton adlarını alır. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Son içe aktarma işleminin sonucu. Her alan için içe aktarma sonucunu tanımlayan nesnelerin dizisi. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Açık dosyaları herhangi bir değişiklik olmadan kapatır. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | PDF alanlarının içeriğini fdf akışına aktarır. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Belgedeki tüm alanların içeriğini bir JSON akışına aktarır. Buton alan değerleri aktarılmaz. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | PDF alanlarının içeriğini xml akışına aktarır. Buton alanının değeri aktarılmaz. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | PDF alanlarının içeriğini xml akışına aktarır. Buton alanının değeri aktarılmaz. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | XFA veri paketini çıkarır. |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Tam nitelikli alan adına göre bir barkod alanını doldurur. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Onay kutusu alanını bir boolean değeri ile doldurur. Not: Sadece Onay Kutusuna uygulanır. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin, alanın tam adı "Form.Subform.CheckBoxField" ise tam adını belirtmelisiniz, "CheckBoxField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Tam nitelikli alan adına göre geçerli bir indeks değeri ile radyo kutusu alanını doldurur. Alanları doldurmadan önce yalnızca alanın adı bilinmelidir. Değer, indeksi ile belirtilebilir. Not: Sadece Radyo Kutusu, Kombinasyon Kutusu ve Liste Kutusu alanlarına uygulanır. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin, alanın tam adı "Form.Subform.ListBoxField" ise tam adını belirtmelisiniz, "ListBoxField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Tam nitelikli alan adına göre geçerli bir değer ile alanı doldurur. Alanları doldurmadan önce her alanın adları ve karşılık gelen geçerli değerleri bilinmelidir. Hem alan adları hem de değerler büyük/küçük harf duyarlıdır. Lütfen Aspose.Pdf.Facades'ın yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit ile karşılaştırıldığında kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin, alanın tam adı "Form.Subform.TextField" ise tam adını belirtmelisiniz, "TextField" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Bir alanı birden fazla seçim ile doldurur. Not: yalnızca AcroForm Liste Kutusu Alanı için. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Belirtilen değer ile alanı doldurur. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Metin kutusu alanlarını metin değerleri ile doldurur ve belgeyi kaydeder. İmzalı belgeler için geçerlidir. Not: Sadece Metin Kutusuna uygulanır. Hem alan adları hem de değerler büyük/küçük harf duyarlıdır. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | FillImageField işlevini aşırı yükler. Girdi bir resim akışıdır. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Tam nitelikli alan adına göre mevcut buton alanına bir resmi yapıştırır. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Tüm alanları düzleştirir. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Belirtilen alanı tam nitelikli alan adı ile düzleştirir. Diğer alanlar değişmez kalır. Eğer fieldName geçersizse, tüm alanlar değişmez kalır. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Radyo buton seçenek alanları için mevcut değeri döndürür. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Alan adına dayalı radyo buton seçenek alanlarını ve ilgili değerleri alır. Bu yöntem radyo buton grupları için anlam taşır. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Alan adının karşılık gelen değerini alır. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Tüm görünüm özelliklerini içeren FrofmFieldFacade nesnesini döndürür. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Alanın bayraklarını döndürür. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Metin alanının sınırlamasını alır. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Alanın türünü döndürür. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Kısa alan adına göre tam alan adını alır. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Bir Zengin Metin alanının değerini, her karakterin biçimlendirme bilgilerini de içerecek şekilde alır. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Gönderim butonunun gönderim bayraklarını döndürür. |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Fdf dosyasından alanların içeriğini içe aktarır ve bunları yeni pdf'ye koyar. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Bir JSON akışından tüm alan verilerini belge alanlarına içe aktarır, alanları tam adlarıyla eşleştirir. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Xfdf(xml) dosyasından alanların içeriğini içe aktarır ve bunları yeni pdf'ye koyar. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Xml dosyasından alanların içeriğini içe aktarır ve bunları yeni pdf'ye koyar. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Xml dosyasından alanların içeriğini içe aktarır ve bunları yeni pdf'ye koyar. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Alanın gerekli olup olmadığını belirler. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Bir alanın adını değiştirir. Hem AcroForm alanı hem de XFA alanı geçerlidir. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Belgeyi belirtilen akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Belgeyi belirtilen dosyaya kaydeder. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | XFA verisini belirtilen veri paketi ile değiştirir. Veri paketi ExtractXfaData kullanılarak çıkarılabilir. |

## Diğer Üyeler

| İsim | Açıklama |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Alan içe aktarma sonucunu tanımlayan sınıf. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | İçe aktarılan alanın durumu |

### Ayrıca Bakınız

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)