---
title: "License"
linktitle: "License"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar. Bu örnekte, bileşeni içeren klasörde MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır, içinde."
type: docs
weight: 2670
url: /tr/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Bileşeni lisanslamak için yöntemler sağlar. Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. License license = new License(); license.setLicense("MyLicense.lic");

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License](#License--) | Bu sınıfın yeni bir örneğini başlatır. Bu örnekte, bileşeni içeren klasörde, çağıran derlemenin bulunduğu klasörde, giriş derlemesinin bulunduğu klasörde ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. License license = new License(); license.setLicense("MyLicense.lic"); |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clearLicense](#clearLicense--) | Mevcut lisansı temizler. |
| [getLicenseInfo](#getLicenseInfo--) | Mevcut lisans bilgilerini alır. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Varsayılan olarak, varsayılan jdk güvenliğini kullanıyoruz. Varsayılan değer == false. Bazı durumlarda özelleştirilmiş java ortamı gerekli algoritmaları destekleyemeyebilir, bu yüzden dahili yerleşik FIPS güvenliğini kullanmayı önerebiliriz. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Varsayılan olarak, varsayılan jre güvenliğini kullanıyoruz. Varsayılan değer == false. Bazı durumlarda özelleştirilmiş java ortamı gerekli algoritmaları destekleyemeyebilir, bu yüzden dahili yerleşik FIPS güvenliğini kullanmayı önerebiliriz. <p> Ayrıca: JVM SecureRandom algoritmasına göre bazı işletim sistemlerinde /dev/random, sonuç döndürmeden önce ana makinede belirli bir miktarda “gürültü” üretilmesini bekler. Oracle’ın JVM’sinde rastgele sayı üretimi için kullanılan kütüphane, UNIX platformları için varsayılan olarak /dev/random’a dayanır. /dev/random daha güvenli olsa da, varsayılan JVM yapılandırması gecikmelere neden oluyorsa /dev/urandom kullanılması önerilir veya /dev/random için entropi üreten cihazlar eklenir. <p> Aşağıdaki java seçeneği gecikmeleri önlemeye ve securerandom.source ayarını geçersiz kılmaya yardımcı olabilir. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. Lisansı içeren bir akış. Bu yöntemi bir akıştan lisans yüklemek için kullanın. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Bileşeni lisanslar. Lisansı aşağıdaki konumlardan bulmaya çalışır: 1. Açık yol. 2. Bileşen jar dosyasının klasörü. Bu örnekte, bileşeni içeren klasörde, çağıran derlemenin bulunduğu klasörde, giriş derlemesinin bulunduğu klasörde ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Bu sınıfın yeni bir örneğini başlatır. Bu örnekte, bileşeni içeren klasörde, çağıran derlemenin bulunduğu klasörde, giriş derlemesinin bulunduğu klasörde ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Mevcut lisansı temizler.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Mevcut lisans bilgilerini alır.

**Returns:**
LicenseInfo örneği

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Varsayılan olarak, varsayılan jdk güvenliğini kullanıyoruz. Varsayılan değer == false. Bazı durumlarda özelleştirilmiş java ortamı gerekli algoritmaları destekleyemeyebilir, bu yüzden dahili yerleşik FIPS güvenliğini kullanmayı önerebiliriz.

**Returns:**
boolean değer

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Varsayılan olarak, varsayılan jre güvenliğini kullanıyoruz. Varsayılan değer == false. Bazı durumlarda özelleştirilmiş java ortamı gerekli algoritmaları destekleyemeyebilir, bu yüzden dahili yerleşik FIPS güvenliğini kullanmayı önerebiliriz. <p> Ayrıca: JVM SecureRandom algoritmasına göre bazı işletim sistemlerinde /dev/random, sonuç döndürmeden önce ana makinede belirli bir miktarda “gürültü” üretilmesini bekler. Oracle’ın JVM’sinde rastgele sayı üretimi için kullanılan kütüphane, UNIX platformları için varsayılan olarak /dev/random’a dayanır. /dev/random daha güvenli olsa da, varsayılan JVM yapılandırması gecikmelere neden oluyorsa /dev/urandom kullanılması önerilir veya /dev/random için entropi üreten cihazlar eklenir. <p> Aşağıdaki java seçeneği gecikmeleri önlemeye ve securerandom.source ayarını geçersiz kılmaya yardımcı olabilir. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| internalFIPSSecurity |  | boolean değer |

### setLicense {#setLicense-java.io.InputStream-}
Bileşeni lisanslar. Lisansı içeren bir akış. Bu yöntemi bir akıştan lisans yüklemek için kullanın. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Bileşeni lisanslar. Lisansı aşağıdaki konumlardan bulmaya çalışır: 1. Açık yol. 2. Bileşen jar dosyasının klasörü. Bu örnekte, bileşeni içeren klasörde, çağıran derlemenin bulunduğu klasörde, giriş derlemesinin bulunduğu klasörde ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. License license = new License(); license.setLicense("MyLicense.lic");
