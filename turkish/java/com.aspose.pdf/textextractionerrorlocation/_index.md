---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin çıkarma hatasının ortaya çıktığı PDF belgesindeki konumu temsil eder."
type: docs
weight: 5050
url: /tr/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Metin çıkarma hatasının ortaya çıktığı PDF belgesindeki konumu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Metin çıkarma hatasına neden olan operatörü göstermek için kullanılan PDF Yazı Tipi nesnesinin anahtarı (adı). |
| [getFormKey](#getFormKey--) | İçerik akışı metin çıkarma hatasının bulunduğu PDF Form XObject'inin anahtarı (adı). ObjectType == 'xForm' ise boş değildir. |
| [getObjectType](#getObjectType--) | İçerik akışı metin çıkarma hatasının bulunduğu PDF nesnesinin (Sayfa veya xForm) türü. |
| [getOperatorIndex](#getOperatorIndex--) | Metin çıkarma hatasına neden olan içerik akışı (operatör koleksiyonu) içindeki metin gösterme operatörünün indeksi. |
| [getOperatorString](#getOperatorString--) | Metin çıkarma hatasına neden olan metin gösterme operatörü. |
| [getPageNumber](#getPageNumber--) | Metin çıkarma hatasının bulunduğu belge sayfasının numarası. |
| [getPath](#getPath--) | Metin çıkarma hatasının ortaya çıktığı PDF belgesinin konumu. |
| [getTextStartPoint](#getTextStartPoint--) | Metin çıkarma hatasına neden olan operatörü göstermek için kullanılan PDF Yazı Tipi nesnesinin anahtarı (adı). |
| [toString](#toString--) | Dize temsilini döndürür. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Metin çıkarma hatasına neden olan operatörü göstermek için kullanılan PDF Yazı Tipi nesnesinin anahtarı (adı).

**Returns:**
String değeri

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

İçerik akışı metin çıkarma hatasının bulunduğu PDF Form XObject'inin anahtarı (adı). ObjectType == 'xForm' ise boş değildir.

**Returns:**
String değeri

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

İçerik akışı metin çıkarma hatasının bulunduğu PDF nesnesinin (Sayfa veya xForm) türü.

**Returns:**
String değeri

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Metin çıkarma hatasına neden olan içerik akışı (operatör koleksiyonu) içindeki metin gösterme operatörünün indeksi.

**Returns:**
int değer

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Metin çıkarma hatasına neden olan metin gösterme operatörü.

**Returns:**
String değeri

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Metin çıkarma hatasının bulunduğu belge sayfasının numarası.

**Returns:**
int değer

### getPath {#getPath--}
```
public String getPath()
```

Metin çıkarma hatasının ortaya çıktığı PDF belgesinin konumu.

**Returns:**
String değeri

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Metin çıkarma hatasına neden olan operatörü göstermek için kullanılan PDF Yazı Tipi nesnesinin anahtarı (adı).

**Returns:**
Nokta örneği

### toString {#toString--}
```
public String toString()
```

Dize temsilini döndürür.

**Returns:**
Dize temsili.
