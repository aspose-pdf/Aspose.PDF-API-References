---
title: "XFA"
linktitle: "XFA"
second_title: "Aspose.PDF for Java API Referansı"
description: "XML Forms Architecture (XFA) ile ilgili XML formunu temsil eder."
type: docs
weight: 5550
url: /tr/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

XML Forms Architecture (XFA) ile ilgili XML formunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | XPath ifadesiyle eşleşen şablon düğümüne XML değerini ekle |
| [beginCachedUpdates](#beginCachedUpdates--) | Önbellekli güncellemeler modunu başlat. XFA'ya yapılan tüm değişiklikler önbelleğe alınacak ve EndCachedUpdates çağrısında belge yapısına kaydedilecektir. Bu, XFA'da çok sayıda değişiklik yapıldığında XML paketlerini belgeye kaydederken tekrarlayan işlemlerden kaçınarak performansı artırmayı sağlar. |
| [endCachedUpdates](#endCachedUpdates--) | Önbellekli güncellemeleri sonlandırır ve tüm verileri belge yapısına kaydeder. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | XFA form alanını düzleştir. |
| [get_Item](#get_Item-java.lang.String-) | Veri düğümünün değerini {@code path} göre alır. |
| [getConfig](#getConfig--) | XFA formunun XFA Config bileşeni. |
| [getDatasets](#getDatasets--) | XFA formunun XFA Datasets bileşeni. |
| [getFieldNames](#getFieldNames--) | Form şablonundaki alan adlarının listesi. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Tüm alanlar için kısa alan adı ve onun dize değerini içeren haritayı döndürür. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | XFA alan şablonunun XML düğümünü döndürür. |
| [getFieldTemplates](#getFieldTemplates--) | XFA formundaki tüm alan şablonlarının listesini döndürür. |
| [getForm](#getForm--) | XFA formunun XFA Form Component bileşenini alır. |
| [getNamespaceManager_](#getNamespaceManager_--) | XFA formu için ad alanını alır. Aşağıdaki ad alanları tanımlanmıştır: form verileri için "data" ve form şablonu için "tpl". |
| [getNamespaceManager](#getNamespaceManager--) | Şablon ve veri için kullanılan ad alanlarıyla namespace yöneticisini döndürür. |
| [getTemplate](#getTemplate--) | XFA formunun XFA Template bileşeni. |
| [getXDP](#getXDP--) | XML Veri Paketi (çevreleyen bir XML konteyneri içindeki tüm XFA form bileşenleri). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Veri düğümünün değerini {@code path} göre alır. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | XFA alanı için resmi ayarlar. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | XFA formundan hesaplama betiğini dışa aktarmaya çalışır. Aksi takdirde boş dize döndürür; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
XPath ifadesiyle eşleşen şablon düğümüne XML değerini ekle

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Önbellekli güncellemeler modunu başlat. XFA'ya yapılan tüm değişiklikler önbelleğe alınacak ve EndCachedUpdates çağrısında belge yapısına kaydedilecektir. Bu, XFA'da çok sayıda değişiklik yapıldığında XML paketlerini belgeye kaydederken tekrarlayan işlemlerden kaçınarak performansı artırmayı sağlar.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Önbellekli güncellemeleri sonlandırır ve tüm verileri belge yapısına kaydeder.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
XFA form alanını düzleştir.

### get_Item {#get_Item-java.lang.String-}
Veri düğümünün değerini {@code path} göre alır.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

XFA formunun XFA Config bileşeni.

**Returns:**
XmlNode nesnesi

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

XFA formunun XFA Datasets bileşeni.

**Returns:**
XmlNode nesnesi

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Form şablonundaki alan adlarının listesi.

**Returns:**
String değerlerinin dizisi

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Tüm alanlar için kısa alan adı ve onun dize değerini içeren haritayı döndürür. </p>

**Returns:**
{@code HashMap<String, String>} nesnesi

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
XFA alan şablonunun XML düğümünü döndürür.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

XFA formundaki tüm alan şablonlarının listesini döndürür.

**Returns:**
Alan şablonlarının listesi.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

XFA formunun XFA Form Component bileşenini alır.

**Returns:**
XmlNode nesnesi

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

XFA formu için ad alanını alır. Aşağıdaki ad alanları tanımlanmıştır: form verileri için "data" ve form şablonu için "tpl".

**Returns:**
XmlNamespaceManager nesnesi

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Şablon ve veri için kullanılan ad alanlarıyla namespace yöneticisini döndürür.

**Returns:**
XmlNamespaceManager nesnesi

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

XFA formunun XFA Template bileşeni.

**Returns:**
XmlNode nesnesi

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

XML Veri Paketi (çevreleyen bir XML konteyneri içindeki tüm XFA form bileşenleri).

**Returns:**
XmlDocument nesnesi

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Veri düğümünün değerini {@code path} göre alır.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
XFA alanı için resmi ayarlar.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
XFA formundan hesaplama betiğini dışa aktarmaya çalışır. Aksi takdirde boş dize döndürür;
