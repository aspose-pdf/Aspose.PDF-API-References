---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Aspose.PDF for Java API Referansı"
description: "İmzalama sürecinde kullanılan ocsp ayarlarını temsil eder."
type: docs
weight: 5360
url: /tr/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

İmzalama sürecinde kullanılan ocsp ayarlarını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Yeni bir {@code TimestampSettings} sınıfı örneğini başlatır. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Yeni bir {@code TimestampSettings} sınıfı örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Temel kimlik doğrulama kimlik bilgilerini alır, Kullanıcı adı ve şifre bir "username:password" dizesine birleştirilir. |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | İç hash fonksiyonları için özet algoritmasını alır/ayarlar. |
| [getServerUrl](#getServerUrl--) | Zaman damgası sunucusu URL'sini alır. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Temel kimlik doğrulama kimlik bilgilerini ayarlar, Kullanıcı adı ve şifre bir "username:password" dizesine birleştirilir. |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | İç hash fonksiyonları için özet algoritmasını alır/ayarlar. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Zaman damgası sunucusu URL'sini ayarlar. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Yeni bir {@code TimestampSettings} sınıfı örneğini başlatır.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Yeni bir {@code TimestampSettings} sınıfı örneğini başlatır.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Temel kimlik doğrulama kimlik bilgilerini alır, Kullanıcı adı ve şifre bir "username:password" dizesine birleştirilir.

**Returns:**
String değeri

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

İç hash fonksiyonları için özet algoritmasını alır/ayarlar.

**Returns:**
DigestHashAlgorithm öğesi @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Zaman damgası sunucusu URL'sini alır.

**Returns:**
String değeri

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Temel kimlik doğrulama kimlik bilgilerini ayarlar, Kullanıcı adı ve şifre bir "username:password" dizesine birleştirilir.

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
İç hash fonksiyonları için özet algoritmasını alır/ayarlar.

### setServerUrl {#setServerUrl-java.lang.String-}
Zaman damgası sunucusu URL'sini ayarlar.
