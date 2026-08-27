---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir belge koleksiyonu şema alan sınıfını temsil eder."
type: docs
weight: 620
url: /tr/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Bir belge koleksiyonu şema alan sınıfını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getE](#getE--) | Etkileşimli PDF işlemcisi tarafından alan değerinin düzenlenmesi desteği sağlanıp sağlanmayacağını gösteren bir bayrak alır. Varsayılan değer: false |
| [getFiledType](#getFiledType--) | Şema koleksiyonundaki bir alan değerinin tipini alır. Bu alan, {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) ile eşleşen değer tipini tanımlar. |
| [getN](#getN--) | Etkileşimli PDF işlemcisi tarafından kullanıcıya sunulacak metinsel alan adını alır. |
| [getO](#getO--) | Kullanıcı arayüzündeki alan adının göreceli sırasını alır. Alanlar, etkileşimli PDF işlemcisi tarafından artan sırada sıralanır. |
| [getSubtype](#getSubtype--) | Şema koleksiyonundaki bir alan değerinin alt tipini alır. Bu sözlüğün tanımladığı koleksiyon alanı veya dosya ile ilgili alanın alt tipi. Bu giriş, alanda depolanacak veri tipini belirler. |
| [getV](#getV--) | Kullanıcı arayüzündeki alanın başlangıç görünürlüğünü alır. Varsayılan değer: true. |

### getE {#getE--}
```
public final boolean getE()
```

Etkileşimli PDF işlemcisi tarafından alan değerinin düzenlenmesi desteği sağlanıp sağlanmayacağını gösteren bir bayrak alır. Varsayılan değer: false

**Returns:**
boolean değer

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Şema koleksiyonundaki bir alan değerinin tipini alır. Bu alan, {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) ile eşleşen değer tipini tanımlar.

**Returns:**
FieldValueType öğesi

### getN {#getN--}
```
public final String getN()
```

Etkileşimli PDF işlemcisi tarafından kullanıcıya sunulacak metinsel alan adını alır.

**Returns:**
String değeri

### getO {#getO--}
```
public final Integer [] getO()
```

Kullanıcı arayüzündeki alan adının göreceli sırasını alır. Alanlar, etkileşimli PDF işlemcisi tarafından artan sırada sıralanır.

**Returns:**
Integer dizisi

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Şema koleksiyonundaki bir alan değerinin alt tipini alır. Bu sözlüğün tanımladığı koleksiyon alanı veya dosya ile ilgili alanın alt tipi. Bu giriş, alanda depolanacak veri tipini belirler.

**Returns:**
CollectionFieldSubtype öğesi

### getV {#getV--}
```
public final boolean getV()
```

Kullanıcı arayüzündeki alanın başlangıç görünürlüğünü alır. Varsayılan değer: true.

**Returns:**
boolean değer
