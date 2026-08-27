---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu enum, şifre korumalı pdf belgelerinde kullanılan bilinen şifre türlerini temsil eder."
type: docs
weight: 3520
url: /tr/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Bu enum, şifre korumalı pdf belgelerinde kullanılan bilinen şifre türlerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Inaccessible](#Inaccessible) | Pdf belgesi şifre korumalıdır ancak hem kullanıcı hem de sahibi şifreleri boş değildir ve şifrelerden hiçbiri tanımlanmamış veya sağlanan şifre yanlıştır. |
| [None](#None) | Pdf belgesi şifre korumalı değildir. |
| [Owner](#Owner) | Pdf belgesi izin değiştirme şifresi (tam erişim) kullanılarak açıldı. |
| [User](#User) | Pdf belgesi belge açma şifresi (kısıtlı erişim) kullanılarak açıldı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Pdf belgesi şifre korumalıdır ancak hem kullanıcı hem de sahibi şifreleri boş değildir ve şifrelerden hiçbiri tanımlanmamış veya sağlanan şifre yanlıştır.

### None {#None}
```
public static final PasswordType None
```

Pdf belgesi şifre korumalı değildir.

### Owner {#Owner}
```
public static final PasswordType Owner
```

Pdf belgesi izin değiştirme şifresi (tam erişim) kullanılarak açıldı.

### User {#User}
```
public static final PasswordType User
```

Pdf belgesi belge açma şifresi (kısıtlı erişim) kullanılarak açıldı.

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static PasswordType [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
