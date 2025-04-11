---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form sınıfı. Form nesnesini temsil eden sınıf
type: docs
weight: 5070
url: /tr/net/aspose.pdf.forms/form/
---
## Form sınıfı

Form nesnesini temsil eden sınıf.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Ayarlandığında, herhangi bir alan değiştiğinde tüm form alanları yeniden hesaplanacaktır. Varsayılan değer doğrudur. Hesaplanan alanların büyük miktarda doldurulması sırasında performansı artırmak için false olarak ayarlayın. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Ayarlandığında, eksik form alanları, eğer anotasyonlarda mevcutsa otomatik olarak oluşturulacaktır. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Alan hesaplama sırasını ayarlamaya olanak tanır. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Bu form üzerindeki alanların sayısını alır. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Formun varsayılan görünümünü alır veya ayarlar (form üzerindeki alanlar için varsayılan yazı tipi, metin boyutu ve rengini tanımlayan nesne). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Bu formda yer alan varsayılan kaynakları alır. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Bu özellik doğruysa, gerekli Xfa exclGroup öğeleri konteynerleri için ek kırmızı sınır dikdörtgenleri çizilecektir. Bu özellik, formların Xfa temsilinin standart hale dönüştürülmesi sırasında exclGroup için benzerlerinin olmaması nedeniyle tanıtılmıştır. Varsayılan olarak false'dur. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Hiyerarşik formun en alt seviyesindeki tüm alanların listesini alır. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Bu özellik doğruysa, XFA formunun standart forma dönüştürülmesi sırasında NeedsRendering anahtarının değeri göz ardı edilecektir. Varsayılan olarak false'dur. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Nesnenin thread-safe olup olmadığını belirtir. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Alan adını kullanarak formun alanını alır. Alan bulunamazsa istisna fırlatır. (2 indeksleyici) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Bu özellik doğruysa, dinamik belgelerin standart hale dönüştürülmesinden sonra "Perms" sözlüğü pdf belgesinden kaldırılacaktır. "Perms" sözlüğü, Adobe Acrobat okuyucusunda zorunlu alanların seçimlerinin görüntülenmesini engelleyen kurallar içerebilir. Varsayılan olarak false'dur. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Ayarlandığında, belge, dosyanın önceki içeriğini değiştiren bir şekilde kaydedilirse (yazılırsa) geçersiz kılınabilecek imzalar içerir; bu, artımlı bir güncellemenin tersidir. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Ayarlandığında, belge en az bir imza alanı içerir. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Senkronizasyon nesnesini döndürür. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Formun türünü alır. Olası değerler: Standart, Statik, Dinamik. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Formun XFA verilerini alır (varsa). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Formda alan ekler. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Formda alan ekler. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Formda yeni bir alan ekler; Eğer bu alan başka bir formda veya bu formda zaten yer alıyorsa, alanın bir kopyası oluşturulur. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Belirtilen konumda, belgenin belirtilen sayfasına alanın ek görünümünü ekler. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Formun XFA'sını belirtilen değere ayarlar. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Formda yer alan alanları bir diziye kopyalar. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Formdan alanı siler. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Alanı adını kullanarak formdan siler. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | PDF form alanlarını JSON formatına aktarır ve sonucu sağlanan akışa yazar. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | PDF form alanlarını JSON formatına aktarır ve sonucu belirtilen dosyaya yazar. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Tüm form alanlarını kaldırır ve değerlerini doğrudan sayfaya yerleştirir. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Form alanlarının enumerasyonunu alır. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Belirtilen dikdörtgenin içindeki alanları döndürür. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Formun belirtilen alanı zaten içerip içermediğini kontrol eder. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Belirtilen adı taşıyan alanın zaten Form'a eklenip eklenmediğini belirler. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Belirtilen adı taşıyan alanın zaten Form'a eklenip eklenmediğini belirler, alanların çocuk hiyerarşisine bakma yeteneği ile. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Akışta sağlanan JSON formatındaki PDF form alanlarını içe aktarır. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Belirtilen dosyada sağlanan JSON formatındaki PDF form alanlarını içe aktarır. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Form alanı anotasyonlarını bağımsız hale getirir. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Belirtilen indeksteki alanın görünümünü kaldırır. Eğer yalnızca bir çocuk görünüm kalmışsa, yöntem onu alanın içine gömer. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Formlar imza bilgisi içerebilir, yani imzalı veya imzasız olabilir. Ve formun görünümü bazen formun imzalı olup olmamasına bağlı olmalıdır. Bu özellik, formun dönüştürücüsüne (örneğin, XFA formunun standart forma dönüştürülmesi sırasında) sonuç formunun imzalı mı yoksa imzasız mı olarak render edilmesi gerektiğini söyler. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Form düzleştirme prosedürü için ayarları tanımlayan sınıf. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Formlar imza bilgisi içerebilir ve imzalı veya imzasız olabilir. Bazen görüntüleyicideki formların görünümü, formun imzalı olup olmamasına bağlı olmalıdır. Bu enum, imza ile ilgili form türünün dönüştürülmesi sırasında olası render modlarını sıralar. |

### Ayrıca Bakınız

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)