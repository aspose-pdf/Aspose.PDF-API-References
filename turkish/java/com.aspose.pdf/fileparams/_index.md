---
title: "FileParams"
linktitle: "FileParams"
second_title: "Aspose.PDF for Java API Referansı"
description: "Ek dosya parametre sözlüğünü tanımlar; bu sözlük ek dosyaya özgü ek bilgileri içermelidir."
type: docs
weight: 1490
url: /tr/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Ek dosya parametre sözlüğünü tanımlar; bu sözlük ek dosyaya özgü ek bilgileri içermelidir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | FileParams sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCheckSum](#getCheckSum--) | Sıkıştırılmamış gömülü dosyanın baytlarının kontrol toplamı olan 16 baytlık bir dizedir. Kontrol toplamı, gömülü dosya akışının baytlarına standart MD5 mesaj özeti algoritması uygulanarak hesaplanır. |
| [getCreationDate](#getCreationDate--) | Gömülü dosyanın oluşturulduğu tarih ve saati al. |
| [getModDate](#getModDate--) | Gömülü dosyanın son değiştirildiği tarih ve saati al. |
| [getSize](#getSize--) | Sıkıştırılmamış gömülü dosyanın boyutu, bayt cinsinden. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Gömülü dosyanın oluşturulduğu tarih ve saati ayarla. |
| [setModDate](#setModDate-java.util.Date-) | Gömülü dosyanın son değiştirildiği tarih ve saati ayarla. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
FileParams sınıfı için yapıcı.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

Sıkıştırılmamış gömülü dosyanın baytlarının kontrol toplamı olan 16 baytlık bir dizedir. Kontrol toplamı, gömülü dosya akışının baytlarına standart MD5 mesaj özeti algoritması uygulanarak hesaplanır.

**Returns:**
String değeri

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Gömülü dosyanın oluşturulduğu tarih ve saati al.

**Returns:**
Date nesnesi

### getModDate {#getModDate--}
```
public Date getModDate()
```

Gömülü dosyanın son değiştirildiği tarih ve saati al.

**Returns:**
Date nesnesi

### getSize {#getSize--}
```
public int getSize()
```

Sıkıştırılmamış gömülü dosyanın boyutu, bayt cinsinden.

**Returns:**
int değer

### setCreationDate {#setCreationDate-java.util.Date-}
Gömülü dosyanın oluşturulduğu tarih ve saati ayarla.

### setModDate {#setModDate-java.util.Date-}
Gömülü dosyanın son değiştirildiği tarih ve saati ayarla.
