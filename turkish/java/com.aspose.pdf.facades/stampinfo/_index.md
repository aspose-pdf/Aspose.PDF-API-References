---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "Damga bilgilerini temsil eden sınıf."
type: docs
weight: 710
url: /tr/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Damga bilgilerini temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getForm](#getForm--) | Damganın XFormunu alır. |
| [getImage](#getImage--) | Damganın görüntüsünü alır. Damga görüntü içermiyorsa (örneğin metin damgası) null olabilir. |
| [getImageInternal](#getImageInternal--) | Damganın görüntüsünü alır. Damga görüntü içermiyorsa (örneğin metin damgası) null olabilir. |
| [getIndexOnPage](#getIndexOnPage--) | Sayfadaki damga indeksini alır. |
| [getRectangle](#getRectangle--) | Damganın yerleştirildiği dikdörtgeni alır. |
| [getStampId](#getStampId--) | Damganın tanımlayıcısını alır. |
| [getStampType](#getStampType--) | Damga tipini alır (görüntü / form). |
| [getText](#getText--) | Damgadaki metni alır. |
| [getVisible](#getVisible--) | Damganın görünürlüğünü alır. Yanlış ise damga gizlenir (HideStampById ile). Gizli damga, ShowStampById ile geri getirilebilir. |

### getForm {#getForm--}
```
public XForm getForm()
```

Damganın XFormunu alır.

**Returns:**
XForm nesnesi

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Damganın görüntüsünü alır. Damga görüntü içermiyorsa (örneğin metin damgası) null olabilir.

**Returns:**
BufferedImage nesnesi

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Damganın görüntüsünü alır. Damga görüntü içermiyorsa (örneğin metin damgası) null olabilir.

**Returns:**
Görüntü nesnesi

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Sayfadaki damga indeksini alır.

**Returns:**
int değer

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Damganın yerleştirildiği dikdörtgeni alır.

**Returns:**
Dikdörtgen öğesi

### getStampId {#getStampId--}
```
public int getStampId()
```

Damganın tanımlayıcısını alır.

**Returns:**
int değer

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Damga tipini alır (görüntü / form).

**Returns:**
StampType öğesi @see StampType

### getText {#getText--}
```
public String getText()
```

Damgadaki metni alır.

**Returns:**
String değeri

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Damganın görünürlüğünü alır. Yanlış ise damga gizlenir (HideStampById ile). Gizli damga, ShowStampById ile geri getirilebilir.

**Returns:**
boolean değer
