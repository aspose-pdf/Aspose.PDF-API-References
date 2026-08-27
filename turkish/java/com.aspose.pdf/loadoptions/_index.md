---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "LoadOptions türü, bireysel yükleme seçenekleri üzerinde soyutlama seviyesini tutar."
type: docs
weight: 2790
url: /tr/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

LoadOptions türü, bireysel yükleme seçenekleri üzerinde soyutlama seviyesini tutar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | {@code LoadOptions} tarafından tanımlanan dosya biçimini temsil eder. |
| [getWarningHandler](#getWarningHandler--) | Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Load işlemi devam eder, ancak kullanıcı Abort döndürürse Load işlemi durmalıdır. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Dosya yüklenirken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. {@code } olduğunda, bu yazı tipinin lisansı tarafından yasaklanan işlemleri yürütmeye izin verir; örneğin, lisans kuralları bu yazı tipinin gömülmesini engellese bile bir PDF belgesine yazı tipi gömmeye izin verir. Varsayılan olarak {@code }'dur. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasal ihlallerin sorumluluğunu tamamen üstlenmesi anlamına gelir. Bu yüzden kendi riskine göre hareket eder. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle önerilir. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Dosya yüklenirken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. {@code } olduğunda, bu yazı tipinin lisansı tarafından yasaklanan işlemleri yürütmeye izin verir; örneğin, lisans kuralları bu yazı tipinin gömülmesini engellese bile bir PDF belgesine yazı tipi gömmeye izin verir. Varsayılan olarak {@code }'dur. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasal ihlallerin sorumluluğunu tamamen üstlenmesi anlamına gelir. Bu yüzden kendi riskine göre hareket eder. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle önerilir. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Load işlemi devam eder, ancak kullanıcı Abort döndürürse Load işlemi durmalıdır. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

{@code LoadOptions} tarafından tanımlanan dosya biçimini temsil eder.

**Returns:**
LoadFormat öğesi @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Load işlemi devam eder, ancak kullanıcı Abort döndürürse Load işlemi durmalıdır.

**Returns:**
IWarningCallback değeri

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Dosya yüklenirken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. {@code } olduğunda, bu yazı tipinin lisansı tarafından yasaklanan işlemleri yürütmeye izin verir; örneğin, lisans kuralları bu yazı tipinin gömülmesini engellese bile bir PDF belgesine yazı tipi gömmeye izin verir. Varsayılan olarak {@code }'dur. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasal ihlallerin sorumluluğunu tamamen üstlenmesi anlamına gelir. Bu yüzden kendi riskine göre hareket eder. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle önerilir.

**Returns:**
boolean değer

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Dosya yüklenirken tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakma bayrağını alır veya ayarlar. {@code } olduğunda, bu yazı tipinin lisansı tarafından yasaklanan işlemleri yürütmeye izin verir; örneğin, lisans kuralları bu yazı tipinin gömülmesini engellese bile bir PDF belgesine yazı tipi gömmeye izin verir. Varsayılan olarak {@code }'dur. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasal ihlallerin sorumluluğunu tamamen üstlenmesi anlamına gelir. Bu yüzden kendi riskine göre hareket eder. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle önerilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Load işlemi devam eder, ancak kullanıcı Abort döndürürse Load işlemi durmalıdır.
