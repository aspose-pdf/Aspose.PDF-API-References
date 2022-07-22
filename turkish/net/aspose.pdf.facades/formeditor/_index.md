---
title: FormEditor
second_title: Aspose.PDF for .NET API Referansı
description: Formların düzenlenmesi için sınıf alanları reklam/silme vb.
type: docs
weight: 2340
url: /tr/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Formların düzenlenmesi için sınıf (alanları reklam/silme vb.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [FormEditor](formeditor#constructor)() | FormEditor için Oluşturucu. |
| [FormEditor](formeditor#constructor_1)(Document) | Yeniyi başlatır[`FormEditor`](../formeditor) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | İşlem sonucu ek olarak HttpResponse nesnelerinde depolandığında ekin adını alır veya ayarlar. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | İşlem sonucu HttpResponse nesnesine depolandığında içeriğin nasıl depolanacağını alır veya ayarlar. Olası değer: satır içi / ek. Varsayılan: satır içi. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | PDF dosya biçimini ayarlar. Sonuç dosyası, belirtilen dosya biçiminde kaydedilecektir. Bu özellik belirtilmezse, dosya dönüştürme yapılmadan varsayılan PDF formatında kaydedilecektir. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Dışa aktarma değerlerine sahip birleşik giriş kutusu seçeneklerini ayarlar. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Alanın görsel özelliklerini ayarlar. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Yeni oluşturulan liste kutusuna veya birleşik giriş kutusuna eklenecek öğeleri ayarlar. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Radyo düğmesi öğe boyutunu alır veya ayarlar (yeni radyo düğmesi alanı eklendiğinde). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydedecek üye, varsayılan değer 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | Telsizlerin yatay veya dikey olarak düzenlendiğini gösteren bayrak, varsayılan değer true'dur. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | İşlem sonucunun depolanacağı Response nesnesini alır veya ayarlar. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Sonuç HttpResponse. olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Gönder düğmesinin gönderim bayraklarını ayarlayın |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Belirtilen türdeki alanı forma ekleyin. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Belirtilen türdeki alanı forma ekleyin. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Bir PushButton alanı için JavaScript ekleyin. Eski olay varsa, ondan sonra yeni olay eklenir. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Liste kutusuna yeni öğe ekler. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Varolan liste kutusu alanına, yalnızca AcroForm birleşik giriş kutusu alanı için Dışa Aktarma değeri olan yeni bir öğe ekleyin. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Forma gönder düğmesi ekleyin. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Cepheyi kapatır. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Mevcut bir alanı belirtilen sayfa numarasında aynı konuma kopyalar. Yeni kopyalanan alan dışında kaynak belgenin sahip olduğu her şeyi içeren yeni bir belge oluşturulur. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Mevcut bir alanı hem sayfa numarası hem de ordinatlar tarafından belirtilen yeni bir konuma kopyalar. Yeni kopyalanan alan dışında kaynak belgenin sahip olduğu her şeyi içeren yeni bir belge üretilecektir. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Mevcut bir alanı bir PDF belgesinden başka bir belgeye orijinal sayfa numarası ve ordinatlarıyla kopyalar. Uyarı: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Mevcut bir alanı bir PDF belgesinden belirtilen sayfa numarası ve orijinal koordinatlarla başka bir belgeye kopyalar. Uyarı: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Mevcut bir alanı bir PDF belgesinden belirtilen sayfa numarası ve ordinatlarla başka bir belgeye kopyalar. Uyarı: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Belirtilen alan türüyle tüm alanların görsel özelliklerini değiştirir. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Belirtilen alanın görsel özelliklerini değiştirir. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Liste alanından öğeyi silin. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Alan bayraklarını alın. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Alanın yeni konumunu ayarlayın. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Alanı formdan kaldırın. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Alanın gönderme işlemini kaldırın. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Alanın adını değiştirin. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Tüm görsel nitelikleri boş değere sıfırlayın. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | İç cephenin tüm görsel özelliklerini boş değere sıfırlayın. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Bir metin alanının hizalama stilini ayarlayın. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Bir metin alanının dikey hizalama stilini ayarlayın. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Alan bayraklarını ayarla |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Alanın özniteliklerini ayarlayın. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Normal bir tek satırlık metin alanı için tarak sayısını ayarlar (alan otomatik olarak birçok eşit aralıklı konuma veya taraklara bölünür, tarakNumarası parametresinin değeri kadar). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Metin alanının maksimum karakter sayısını ayarlar. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | Bir PushButton alanı için JavaScript'i ayarlayın. Eski JavaScript mevcutsa, yenisiyle değiştirilecektir. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Gönder düğmesinin gönder bayrağını ayarlayın. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Düğmenin URL'sini ayarlar. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Tek satırlı bir metin alanını çok satırlı bir metin alanıyla değiştirin. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
