---
title: "Form"
linktitle: "Form"
second_title: "Aspose.PDF for Java API Referansı"
description: "Form nesnesini temsil eden sınıf."
type: docs
weight: 1740
url: /tr/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Form nesnesini temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Formda alan ekler. |
| [add](#add-com.aspose.pdf.Field-int-) | Formda alan ekler. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Forma yeni bir alan ekler; Bu alan başka bir formda veya bu formda zaten yer alıyorsa, alanın bir kopyası oluşturulur. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Formda alan ekler. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Belirtilen konumda, belgenin belirtilen sayfasına alanın ek bir görünümünü ekler. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Belgenin belirtilen sayfasına alanın ek bir görünümünü ekler. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Formun XFA'sını belirtilen değere ayarlar. |
| [clear](#clear--) | Formdaki tüm alanları siler. Desteklenmiyor. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Alanının formda sunulup sunulmadığını belirler. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Formda yer alan alanları diziye kopyalar. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Formun alanlarını diziye kopyalar. |
| [delete](#delete-com.aspose.pdf.Field-) | Formdan alanı sil. |
| [delete](#delete-java.lang.String-) | Formdaki alanı adını kullanarak siler. |
| [flatten](#flatten--) | Tüm statik form alanlarını kaldırır ve değerlerini doğrudan sayfaya yerleştirir. |
| [get_Item](#get_Item-int-) | Formdaki alanı alan indeksine göre alır. |
| [get_Item](#get_Item-java.lang.String-) | Formdaki alanı alan adına göre alır. Alan bulunamazsa excpetion fırlatır. |
| [get_xfa](#get_xfa--) | Yalnızca dahili kullanım için |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Alanı alan adına göre arar. Alan bulunamazsa null döndürür. |
| [getAutoRecalculate](#getAutoRecalculate--) | Ayarlanırsa, herhangi bir alan değiştiğinde tüm form alanları yeniden hesaplanır. Varsayılan değer true'tır. Hesaplanan alanların çok olduğu formları doldururken performansı artırmak için false olarak ayarlayın. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Ayarlanırsa, eksik form alanları ek açıklamalarda bulunuyorlarsa otomatik olarak oluşturulur. |
| [getDefaultAppearance](#getDefaultAppearance--) | Formun varsayılan görünümünü alır (formdaki alanlar için varsayılan yazı tipi, metin boyutu ve rengi tanımlayan nesne). |
| [getDefaultResources](#getDefaultResources--) | Bu formda yer alan varsayılan kaynakları alır. |
| [getDocument](#getDocument--) | Yalnızca dahili kullanım için |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Bu özellik true ise, gerekli Xfa exclGroup öğe kapsayıcıları için ek kırmızı sınır dikdörtgenleri çizilir. Bu özellik, formların Xfa temsiliğinin standart formata dönüştürülmesi sırasında exclGroup için benzerliklerin bulunmaması nedeniyle tanıtıldı. Varsayılan olarak false'tur. |
| [getFields](#getFields--) | Hiyerarşik formun en düşük seviyesindeki tüm alanların listesini alır. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Belirtilen dikdörtgen içindeki alanları döndürür. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Bu özellik true ise, XFA formunun Standart forma dönüştürülmesi sırasında NeedsRendering anahtarının değeri göz ardı edilir. Varsayılan olarak false'tur. |
| [getNeedsRendering](#getNeedsRendering--) | Belgenin dinamik XFA formunu kaldırması gerekip gerekmediğini gösteren bir değer alır. Bu özellik, XFA formu mevcut olduğunda ve {@code NeedsRendering}({@link #getNeedsRendering}) false olduğunda XFA formunu kaldırmak için {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) kullanılıp kullanılmayacağını belirlemek amacıyla tanıtıldı. |
| [getRemovePermission](#getRemovePermission--) | Bu özellik true ise, dinamik belgelerin standart formata dönüştürülmesinden sonra pdf belgesinden "Perms" sözlüğü kaldırılacaktır. "Perms" sözlüğü, Adobe Acrobat okuyucusunda zorunlu alanların seçiminin görüntülenmesini bozabilecek kurallar içerebilir. Varsayılan olarak false'tur. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Ayarlanırsa, dosya önceki içeriğini değiştiren bir şekilde (artımlı bir güncelleme yerine) kaydedildiğinde (yazıldığında) geçersiz hale gelebilecek imzalar belge içinde bulunur. |
| [getSignaturesExist](#getSignaturesExist--) | Ayarlanırsa, belgede en az bir imza alanı bulunur. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Formlar imzalama bilgisi içerebilir, yani imzalı ya da imzasız olabilir. Ve formun görünümü bazen formun imzalı olup olmamasına bağlı olmalıdır. Bu özellik, form dönüştürücüsüne (ör. XFA formunun Standart forma dönüştürülmesi sırasında) sonuç formun imzalı mı yoksa imzasız mı render edilmesi gerektiğini bildirir. |
| [getSyncRoot](#getSyncRoot--) | Eşitleme nesnesini döndürür. |
| [getType](#getType--) | Formun tipini alır. Olası değerler: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Formun XFA verilerini alır (varsa). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Formun belirtilen alana zaten sahip olup olmadığını kontrol eder. |
| [hasField](#hasField-java.lang.String-) | Belirtilen isimdeki alanın Form'a zaten eklenip eklenmediğini belirler. |
| [hasField](#hasField-java.lang.String-boolean-) | Belirtilen isimdeki alanın Form'a zaten eklenip eklenmediğini, alanların alt hiyerarşisine bakma yeteneğiyle belirler. |
| [hasXfa](#hasXfa--) | Belgenin XFA formu içerip içermediğini gösteren bir değer alır. Bu özellik, XFA formu mevcut olduğunda ve {@code NeedsRendering}({@link #getNeedsRendering}) false olduğunda XFA formunu kaldırmak için {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) kullanılıp kullanılmayacağını belirlemek amacıyla tanıtıldı. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını belirler. Her zaman false döndürür. |
| [isSynchronized](#isSynchronized--) | Nesne iş parçacığı güvenli ise true döndürür. |
| [iterator](#iterator--) | Form alanlarının enumarasyonunu alır. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * PDF form alanlarını JSON formatına dışa aktarır ve sonucu verilen akıma yazar. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Formdan alanı siler. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Belirtilen indeksteki alanın görünümünü kaldırır. Eğer sadece bir alt görünüm kalırsa, yöntem bunu alana gömer. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Ayarlanırsa, herhangi bir alan değiştiğinde tüm form alanları yeniden hesaplanır. Varsayılan değer true'tır. Hesaplanan alanların çok olduğu formları doldururken performansı artırmak için false olarak ayarlayın. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Ayarlanırsa, eksik form alanları ek açıklamalarda bulunuyorlarsa otomatik olarak oluşturulur. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Alan hesaplamasının sırasını ayarlamaya izin verir. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Formun varsayılan görünümünü ayarlar (formdaki alanlar için varsayılan yazı tipi, metin boyutu ve rengi tanımlayan nesne). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Bu özellik true ise, gerekli Xfa exclGroup öğe kapsayıcıları için ek kırmızı sınır dikdörtgenleri çizilir. Bu özellik, formların Xfa temsiliğinin standart formata dönüştürülmesi sırasında exclGroup için benzerliklerin bulunmaması nedeniyle tanıtıldı. Varsayılan olarak false'tur. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Bu özellik true ise, XFA formunun Standart forma dönüştürülmesi sırasında NeedsRendering anahtarının değeri göz ardı edilir. Varsayılan olarak false'tur. |
| [setRemovePermission](#setRemovePermission-boolean-) | Bu özellik true ise, dinamik belgelerin standart formata dönüştürülmesinden sonra pdf belgesinden "Perms" sözlüğü kaldırılacaktır. "Perms" sözlüğü, Adobe Acrobat okuyucusunda zorunlu alanların seçiminin görüntülenmesini bozabilecek kurallar içerebilir. Varsayılan olarak false'tur. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Ayarlanırsa, dosya önceki içeriğini değiştiren bir şekilde (artımlı bir güncelleme yerine) kaydedildiğinde (yazıldığında) geçersiz hale gelebilecek imzalar belge içinde bulunur. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Ayarlanırsa, belgede en az bir imza alanı bulunur. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Formlar imzalama bilgisi içerebilir, yani imzalı ya da imzasız olabilir. Ve formun görünümü bazen formun imzalı olup olmamasına bağlı olmalıdır. Bu özellik, form dönüştürücüsüne (ör. XFA formunun Standart forma dönüştürülmesi sırasında) sonuç formun imzalı mı yoksa imzasız mı render edilmesi gerektiğini bildirir. |
| [setType](#setType-com.aspose.pdf.FormType-) | Formun tipini alır. Olası değerler: Standard, Static, Dynamic. |
| [size](#size--) | Bu formdaki alanların sayısını alır. |

### Form {#Form-com.aspose.pdf.IDocument-}
Yapıcı

### add {#add-com.aspose.pdf.Field-}
Formda alan ekler.

### add {#add-com.aspose.pdf.Field-int-}
Formda alan ekler.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Forma yeni bir alan ekler; Bu alan başka bir formda veya bu formda zaten yer alıyorsa, alanın bir kopyası oluşturulur.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Formda alan ekler.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Belirtilen konumda, belgenin belirtilen sayfasına alanın ek bir görünümünü ekler.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Belgenin belirtilen sayfasına alanın ek bir görünümünü ekler.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Formun XFA'sını belirtilen değere ayarlar.

### clear {#clear--}
```
public void clear()
```

Formdaki tüm alanları siler. Desteklenmiyor.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Alanının formda sunulup sunulmadığını belirler.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Formda yer alan alanları diziye kopyalar.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Formun alanlarını diziye kopyalar.

### delete {#delete-com.aspose.pdf.Field-}
Formdan alanı sil.

### delete {#delete-java.lang.String-}
Formdaki alanı adını kullanarak siler.

### flatten {#flatten--}
```
public void flatten()
```

Tüm statik form alanlarını kaldırır ve değerlerini doğrudan sayfaya yerleştirir.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Formdaki alanı alan indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Alan indeksi. |

**Returns:**
Alınan alan.

### get_Item {#get_Item-java.lang.String-}
Formdaki alanı alan adına göre alır. Alan bulunamazsa excpetion fırlatır.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Yalnızca dahili kullanım için

**Returns:**
XFA nesnesi

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Alanı alan adına göre arar. Alan bulunamazsa null döndürür.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Ayarlanırsa, herhangi bir alan değiştiğinde tüm form alanları yeniden hesaplanır. Varsayılan değer true'tır. Hesaplanan alanların çok olduğu formları doldururken performansı artırmak için false olarak ayarlayın.

**Returns:**
boolean değer

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Ayarlanırsa, eksik form alanları ek açıklamalarda bulunuyorlarsa otomatik olarak oluşturulur.

**Returns:**
boolean değer

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Formun varsayılan görünümünü alır (formdaki alanlar için varsayılan yazı tipi, metin boyutu ve rengi tanımlayan nesne).

**Returns:**
DefaultAppearance nesnesi

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Bu formda yer alan varsayılan kaynakları alır.

**Returns:**
Kaynaklar değeri

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Yalnızca dahili kullanım için

**Returns:**
IDocument nesnesi

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Bu özellik true ise, gerekli Xfa exclGroup öğe kapsayıcıları için ek kırmızı sınır dikdörtgenleri çizilir. Bu özellik, formların Xfa temsiliğinin standart formata dönüştürülmesi sırasında exclGroup için benzerliklerin bulunmaması nedeniyle tanıtıldı. Varsayılan olarak false'tur.

**Returns:**
boolean değer

### getFields {#getFields--}
```
public Field [] getFields()
```

Hiyerarşik formun en düşük seviyesindeki tüm alanların listesini alır.

**Returns:**
Bulunan alanları içeren dizi.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Belirtilen dikdörtgen içindeki alanları döndürür.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Bu özellik true ise, XFA formunun Standart forma dönüştürülmesi sırasında NeedsRendering anahtarının değeri göz ardı edilir. Varsayılan olarak false'tur.

**Returns:**
boolean değer

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Belgenin dinamik XFA formunu kaldırması gerekip gerekmediğini gösteren bir değer alır. Bu özellik, XFA formu mevcut olduğunda ve {@code NeedsRendering}({@link #getNeedsRendering}) false olduğunda XFA formunu kaldırmak için {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) kullanılıp kullanılmayacağını belirlemek amacıyla tanıtıldı.

**Returns:**
boolean değer

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Bu özellik true ise, dinamik belgelerin standart formata dönüştürülmesinden sonra pdf belgesinden "Perms" sözlüğü kaldırılacaktır. "Perms" sözlüğü, Adobe Acrobat okuyucusunda zorunlu alanların seçiminin görüntülenmesini bozabilecek kurallar içerebilir. Varsayılan olarak false'tur.

**Returns:**
boolean değer

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Ayarlanırsa, dosya önceki içeriğini değiştiren bir şekilde (artımlı bir güncelleme yerine) kaydedildiğinde (yazıldığında) geçersiz hale gelebilecek imzalar belge içinde bulunur.

**Returns:**
boolean değer

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Ayarlanırsa, belgede en az bir imza alanı bulunur.

**Returns:**
boolean değer

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Formlar imzalama bilgisi içerebilir, yani imzalı ya da imzasız olabilir. Ve formun görünümü bazen formun imzalı olup olmamasına bağlı olmalıdır. Bu özellik, form dönüştürücüsüne (ör. XFA formunun Standart forma dönüştürülmesi sırasında) sonuç formun imzalı mı yoksa imzasız mı render edilmesi gerektiğini bildirir.

**Returns:**
SignDependentElementsRenderingModes öğesi @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Eşitleme nesnesini döndürür.

**Returns:**
Eşitleme için nesne

### getType {#getType--}
```
public FormType getType()
```

Formun tipini alır. Olası değerler: Standard, Static, Dynamic.

**Returns:**
FormType değeri @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Formun XFA verilerini alır (varsa).

**Returns:**
XFA değeri

### hasField {#hasField-com.aspose.pdf.Field-}
Formun belirtilen alana zaten sahip olup olmadığını kontrol eder.

### hasField {#hasField-java.lang.String-}
Belirtilen isimdeki alanın Form'a zaten eklenip eklenmediğini belirler.

### hasField {#hasField-java.lang.String-boolean-}
Belirtilen isimdeki alanın Form'a zaten eklenip eklenmediğini, alanların alt hiyerarşisine bakma yeteneğiyle belirler.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Belgenin XFA formu içerip içermediğini gösteren bir değer alır. Bu özellik, XFA formu mevcut olduğunda ve {@code NeedsRendering}({@link #getNeedsRendering}) false olduğunda XFA formunu kaldırmak için {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) kullanılıp kullanılmayacağını belirlemek amacıyla tanıtıldı.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını belirler. Her zaman false döndürür.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Nesne iş parçacığı güvenli ise true döndürür.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Form alanlarının enumarasyonunu alır.

**Returns:**
Alan sayacı.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * PDF form alanlarını JSON formatına dışa aktarır ve sonucu verilen akıma yazar. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Formdan alanı siler.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Belirtilen indeksteki alanın görünümünü kaldırır. Eğer sadece bir alt görünüm kalırsa, yöntem bunu alana gömer.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Ayarlanırsa, herhangi bir alan değiştiğinde tüm form alanları yeniden hesaplanır. Varsayılan değer true'tır. Hesaplanan alanların çok olduğu formları doldururken performansı artırmak için false olarak ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Ayarlanırsa, eksik form alanları ek açıklamalarda bulunuyorlarsa otomatik olarak oluşturulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Alan hesaplamasının sırasını ayarlamaya izin verir.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Formun varsayılan görünümünü ayarlar (formdaki alanlar için varsayılan yazı tipi, metin boyutu ve rengi tanımlayan nesne).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Bu özellik true ise, gerekli Xfa exclGroup öğe kapsayıcıları için ek kırmızı sınır dikdörtgenleri çizilir. Bu özellik, formların Xfa temsiliğinin standart formata dönüştürülmesi sırasında exclGroup için benzerliklerin bulunmaması nedeniyle tanıtıldı. Varsayılan olarak false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Bu özellik true ise, XFA formunun Standart forma dönüştürülmesi sırasında NeedsRendering anahtarının değeri göz ardı edilir. Varsayılan olarak false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Bu özellik true ise, dinamik belgelerin standart formata dönüştürülmesinden sonra pdf belgesinden "Perms" sözlüğü kaldırılacaktır. "Perms" sözlüğü, Adobe Acrobat okuyucusunda zorunlu alanların seçiminin görüntülenmesini bozabilecek kurallar içerebilir. Varsayılan olarak false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Ayarlanırsa, dosya önceki içeriğini değiştiren bir şekilde (artımlı bir güncelleme yerine) kaydedildiğinde (yazıldığında) geçersiz hale gelebilecek imzalar belge içinde bulunur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Ayarlanırsa, belgede en az bir imza alanı bulunur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Formlar imzalama bilgisi içerebilir, yani imzalı ya da imzasız olabilir. Ve formun görünümü bazen formun imzalı olup olmamasına bağlı olmalıdır. Bu özellik, form dönüştürücüsüne (ör. XFA formunun Standart forma dönüştürülmesi sırasında) sonuç formun imzalı mı yoksa imzasız mı render edilmesi gerektiğini bildirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | SignDependentElementsRenderingModes öğesi @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Formun tipini alır. Olası değerler: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Bu formdaki alanların sayısını alır.

**Returns:**
int değer
