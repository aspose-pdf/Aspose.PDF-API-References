---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinden çıkarılan imzalanmamış içerik öğelerini kapsüller. Bu sınıf, imzalanmamış olan sayfalara, form alanlarına, XForm'lara ve ek açıklamalara erişim sağlar."
type: docs
weight: 50
url: /tr/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Bir PDF belgesinden çıkarılan imzasız içerik öğelerini kapsüller. Bu sınıf, belgedeki imzasız içeriğin bir parçası olan sayfalara, form alanlarına, XForm'lara ve açıklamalara erişim sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Değiştirilebilecek veya eklenebilecek değiştirilmiş ek açıklamaların bir sözlüğünü alır. |
| [getForms](#getForms--) | Kademeli olarak değiştirilmiş veya eklenmiş form alanlarını alır. |
| [getPages](#getPages--) | İçeriği imzasız olan veya kademeli olarak değiştirilmiş sayfaların bir listesini alır. Sayfa değiştirilmiş olarak kabul edilir ve XForms kontrol edilmez ve XForms listesinde görünmez. |
| [getXForms](#getXForms--) | Sayfa kendisi değişmemiş olsa da (Sayfalar listesinde bulunmayan) değişmiş olabilecek XForm nesnelerinin bir sözlüğünü alır. |
| [setXForms](#setXForms-java.util.HashMap-) | Sayfa kendisi değişmemiş olsa da (Sayfalar listesinde bulunmayan) değişmiş olabilecek XForm nesnelerinin bir sözlüğü. |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Değiştirilebilecek veya eklenebilecek değiştirilmiş ek açıklamaların bir sözlüğünü alır.

**Returns:**
Değişmiş veya eklenmiş olabilecek değiştirilmiş açıklamaların bir sözlüğü.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Kademeli olarak değiştirilmiş veya eklenmiş form alanlarını alır.

**Returns:**
Kademeli olarak değiştirilmiş veya eklenmiş form alanları.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

İçeriği imzasız olan veya kademeli olarak değiştirilmiş sayfaların bir listesini alır. Sayfa değiştirilmiş olarak kabul edilir ve XForms kontrol edilmez ve XForms listesinde görünmez.

**Returns:**
İçeriği imzasız olan veya kademeli olarak değiştirilmiş sayfaların bir listesi.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Sayfa kendisi değişmemiş olsa da (Sayfalar listesinde bulunmayan) değişmiş olabilecek XForm nesnelerinin bir sözlüğünü alır.

**Returns:**
Sayfa kendisi değişmemiş olsa da (Sayfalar listesinde bulunmayan) değişmiş olabilecek XForm nesnelerinin bir sözlüğü.

### setXForms {#setXForms-java.util.HashMap-}
Sayfa kendisi değişmemiş olsa da (Sayfalar listesinde bulunmayan) değişmiş olabilecek XForm nesnelerinin bir sözlüğü.
