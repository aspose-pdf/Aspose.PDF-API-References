---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormEditor sınıfı. Formları düzenlemek için sınıf, alan ekleme/silme vb.
type: docs
weight: 4330
url: /tr/net/aspose.pdf.facades/formeditor/
---
## FormEditor sınıfı

Formları düzenlemek için sınıf (alan ekleme/silme vb.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | FormEditor için yapıcı. |
| [FormEditor](formeditor/#constructor_1)(Document) | *belge* temelinde yeni bir `FormEditor` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya varsayılan PDF formatında kaydedilecektir. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | İhracat değerleri ile combo kutusu için seçenekleri ayarlar. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Alanın görsel özelliklerini ayarlar. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri ayarlar. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Radyo butonu öğesinin boyutunu alır veya ayarlar (yeni radyo butonu alanı eklendiğinde). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | İki komşu radyo butonu arasındaki boşluğu piksel cinsinden kaydeden üye, varsayılan 50'dir. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Radyo butonlarının yatay mı yoksa dikey mi düzenlendiğini belirten bayrak, varsayılan değer doğrudur. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Gönderim düğmesinin gönderim bayraklarını ayarlar |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Belirtilen türde alanı forma ekler. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Belirtilen türde alanı forma ekler. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Bir PushButton alanı için JavaScript ekler. Eski bir olay varsa, yeni olay onun sonrasına eklenir. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Liste kutusuna yeni bir öğe ekler. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Mevcut liste kutusu alanına İhracat değeri ile yeni bir öğe ekler, yalnızca AcroForm combo kutusu alanı için. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Forma gönderim düğmesi ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Yüzeyi kapatır. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar. Yeni bir belge üretilecektir, bu belge kaynak belgenin sahip olduğu her şeyi içerir, yeni kopyalanan alan hariç. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Mevcut bir alanı hem sayfa numarası hem de koordinatlarla belirtilen yeni bir konuma kopyalar. Yeni bir belge üretilecektir, bu belge kaynak belgenin sahip olduğu her şeyi içerir, yeni kopyalanan alan hariç. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Mevcut bir alanı bir PDF belgesinden diğerine orijinal sayfa numarası ve koordinatlarla kopyalar. Not: Sadece AcroForm alanları için (radyo kutusu hariç). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Mevcut bir alanı bir PDF belgesinden diğerine belirtilen sayfa numarası ve orijinal koordinatlarla kopyalar. Not: Sadece AcroForm alanları için (radyo kutusu hariç). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Mevcut bir alanı bir PDF belgesinden diğerine belirtilen sayfa numarası ve koordinatlarla kopyalar. Not: Sadece AcroForm alanları için (radyo kutusu hariç). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Belirtilen alan türündeki tüm alanların görsel özelliklerini değiştirir. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Belirtilen alanın görsel özelliklerini değiştirir. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Liste alanından öğeyi siler. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Alan bayraklarını alır. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Alanın yeni konumunu ayarlar. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Alanı formdan kaldırır. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Alanın gönderim eylemini kaldırır. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Alanın adını değiştirir. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Tüm görsel özellikleri boş değere sıfırlar. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | İç yüzeyin tüm görsel özelliklerini boş değere sıfırlar. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Bir metin alanının hizalama stilini ayarlar. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Bir metin alanının dikey hizalama stilini ayarlar. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Alan bayraklarını ayarlar |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Alanın özelliklerini ayarlar. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Tek satırlık bir metin alanı için kombine sayısını ayarlar (alan, combNumber parametresinin değeri kadar eşit aralıklı pozisyona veya kombine bölünür). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Metin alanının maksimum karakter sayısını ayarlar. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Bir PushButton alanı için JavaScript ayarlar. Eski JavaScript varsa, yeni ile değiştirilir. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Gönderim düğmesinin gönderim bayrağını ayarlar. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Düğmenin URL'sini ayarlar. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Tek satırlı bir metin alanını çok satırlı bir alana dönüştürür. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)