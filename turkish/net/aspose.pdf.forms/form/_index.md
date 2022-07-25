---
title: Form
second_title: Aspose.PDF for .NET API Referansı
description: Form nesnesini temsil eden sınıf.
type: docs
weight: 3020
url: /tr/net/aspose.pdf.forms/form/
---
## Form class

Form nesnesini temsil eden sınıf.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Ayarlanırsa, herhangi bir alan değiştirildiğinde tüm form alanları yeniden hesaplanacaktır. Varsayılan değer doğrudur. Formu büyük miktarda hesaplanmış alanla doldururken performansı artırmak için false olarak ayarlayın. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Ayarlanırsa, ek açıklamalarda mevcutlarsa eksik form alanları otomatik olarak oluşturulur. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Alan hesaplama sırasını belirlemeye izin verir. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Bu formdaki alanların sayısını alır. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Formun varsayılan görünümünü alır veya ayarlar (formdaki alanlar için varsayılan yazı tipini, metin boyutunu ve rengini tanımlayan nesne). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Bu forma yerleştirilmiş varsayılan kaynakları alır. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Bu özellik doğruysa, gerekli Xfa için ek kırmızı sınır dikdörtgenleri çizilir exclGroup elemanları container Bu özellik, dönüştürme sırasında exclGroup için analogların olmaması nedeniyle tanıtıldı formlarının standarda Xfa gösterimi. Varsayılan olarak yanlıştır. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | En düşük hiyerarşik form düzeyindeki tüm alanların listesini alır. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Bu özellik doğruysa, XFA formunun Standart forma dönüştürülmesi sırasında NeedsRendering anahtarının değeri yok sayılır. Varsayılan olarak yanlıştır. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Nesne iş parçacığı için güvenliyse true değerini döndürür. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Formun alanını alan adına göre alır. Alan bulunamadıysa istisna atar. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Bu özellik doğruysa, dinamik belgeleri standarda dönüştürdükten sonra "İzinler" sözlüğü pdf belgesinden kaldırılacaktır. "İzinler" sözlüğü, Adobe Acrobat okuyucuda zorunlu alanların seçiminin görüntülenmesini engelleyen kurallar içerebilir. Varsayılan olarak yanlıştır. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Ayarlanırsa, belge, dosya önceki içeriğini değiştirecek şekilde kaydedilirse (yazılırsa) geçersiz kılınabilecek imzalar içerir, artımlı güncelleme yerine . |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Ayarlanırsa, belge en az bir imza alanı içerir. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Eşitleme nesnesini döndürür. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Formun türünü alır. Olası değerler şunlardır: Standart, Statik, Dinamik. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Formun XFA verilerini alır (varsa). |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Forma alan ekler. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Forma alan ekler. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Forma yeni alan ekler; Bu alan zaten başka bir forma veya bu forma yerleştirilmişse, alanın kopyası oluşturulur. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Belirtilen konumdaki belgenin belirtilen sayfasına alanın ek görünümünü ekler. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Formun XFA'sını belirtilen değere ayarlar. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Forma yerleştirilen alanları diziye kopyalar. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Alanı formdan silin. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Alanı adıyla formdan siler. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Tüm form alanlarını kaldırır ve değerlerini doğrudan sayfaya yerleştirir. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Form alanlarının numaralandırılmasını alır. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Belirtilen dikdörtgenin içindeki alanları döndürür. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Formda zaten belirtilen alan olup olmadığını kontrol edin. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Belirtilen ada sahip alanın Form'a önceden eklenmiş olup olmadığını belirler. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Formlar imzalama bilgisi içerebilir, yani imzalı veya imzasız olabilir. Ve formun görünümü bazen formun imzalanıp imzalanmadığına bağlı olmalıdır. Bu özellik formun dönüştürücüsüne (fe XFA formunun Standart forma dönüştürülmesi sırasında) sonuç formunun olup olmadığını söyler imzalı veya imzasız olarak oluşturulmalıdır. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Form düzleştirme prosedürü için ayarları açıklayan sınıf. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Formlar imzalama bilgisi içerebilir ve imzalı veya imzasız olabilir. Bazen formların görüntüleyicideki görünümü, formun imzalı olup olmamasına bağlı olmalıdır. Bu numaralandırma, form türünün dönüştürülmesi sırasında imzaya göre olası oluşturma modlarını sıralar. |

### Ayrıca bakınız

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
