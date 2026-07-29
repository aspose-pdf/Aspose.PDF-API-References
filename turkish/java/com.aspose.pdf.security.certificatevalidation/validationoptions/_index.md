---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinde bir dijital imzayı doğrulama seçeneklerini temsil eder."
type: docs
weight: 30
url: /tr/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

PDF belgesinde bir dijital imzayı doğrulama seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Bir {@link ValidationOptions} sınıfının örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Doğrulama süreci sırasında sertifika zincirinin kontrol edilip edilmeyeceğini belirten bir değeri alır veya ayarlar. Özellik ayarlandığında, sertifika zincirinin varlığı kontrol edilir; eğer yoksa, doğrulama sonucu {@link ValidationStatus#Undefined} olur ve bu, Adobe Acrobat davranışına karşılık gelir. Yalnızca çevrimiçi iptal durumunu kontrol etmek istiyorsanız, alanı {@code false} olarak ayarlayın. Varsayılan değer {@code false}'tir. |
| [getRequestTimeout](#getRequestTimeout--) | Doğrulama süreci sırasında ağ ile ilgili işlemler için milisaniye cinsinden zaman aşımı süresini alır veya ayarlar. RequestTimeout özelliği, iptal durumu veya OCSP sunucuları gibi çevrimiçi kaynaklara erişilirken sistemin bir ağ yanıtı için bekleyeceği azami süreyi tanımlar. |
| [getValidationMethod](#getValidationMethod--) | Bir sertifikanın doğrulanması için kullanılan yöntemi alır veya ayarlar. |
| [getValidationMode](#getValidationMode--) | PDF belgesindeki dijital imzalar için doğrulama modunu alır veya ayarlar. ValidationMode özelliği, doğrulama sürecinin katılığı belirler. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Doğrulama süreci sırasında sertifika zincirinin kontrol edilip edilmeyeceğini belirten bir değeri alır veya ayarlar. Özellik ayarlandığında, sertifika zincirinin varlığı kontrol edilir; eğer yoksa, doğrulama sonucu {@link ValidationStatus#Undefined} olur ve bu, Adobe Acrobat davranışına karşılık gelir. Yalnızca çevrimiçi iptal durumunu kontrol etmek istiyorsanız, alanı {@code false} olarak ayarlayın. Varsayılan değer {@code false}'tir. |
| [setRequestTimeout](#setRequestTimeout-int-) | Doğrulama süreci sırasında ağ ile ilgili işlemler için milisaniye cinsinden zaman aşımı süresini alır veya ayarlar. RequestTimeout özelliği, iptal durumu veya OCSP sunucuları gibi çevrimiçi kaynaklara erişilirken sistemin bir ağ yanıtı için bekleyeceği azami süreyi tanımlar. |
| [setValidationMethod](#setValidationMethod-int-) | Bir sertifikanın doğrulanması için kullanılan yöntemi alır veya ayarlar. |
| [setValidationMode](#setValidationMode-int-) | PDF belgesindeki dijital imzalar için doğrulama modunu alır veya ayarlar. ValidationMode özelliği, doğrulama sürecinin katılığı belirler. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Bir {@link ValidationOptions} sınıfının örneğini oluşturur.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Doğrulama süreci sırasında sertifika zincirinin kontrol edilip edilmeyeceğini belirten bir değeri alır veya ayarlar. Özellik ayarlandığında, sertifika zincirinin varlığı kontrol edilir; eğer yoksa, doğrulama sonucu {@link ValidationStatus#Undefined} olur ve bu, Adobe Acrobat davranışına karşılık gelir. Yalnızca çevrimiçi iptal durumunu kontrol etmek istiyorsanız, alanı {@code false} olarak ayarlayın. Varsayılan değer {@code false}'tir.

**Returns:**
boolean değer

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Doğrulama süreci sırasında ağ ile ilgili işlemler için milisaniye cinsinden zaman aşımı süresini alır veya ayarlar. RequestTimeout özelliği, iptal durumu veya OCSP sunucuları gibi çevrimiçi kaynaklara erişilirken sistemin bir ağ yanıtı için bekleyeceği azami süreyi tanımlar.

**Returns:**
int değer

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Bir sertifikanın doğrulanması için kullanılan yöntemi alır veya ayarlar.

**Returns:**
ValidationMethod öğesi

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

PDF belgesindeki dijital imzalar için doğrulama modunu alır veya ayarlar. ValidationMode özelliği, doğrulama sürecinin katılığı belirler.

**Returns:**
ValidationMode öğesi

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Doğrulama süreci sırasında sertifika zincirinin kontrol edilip edilmeyeceğini belirten bir değeri alır veya ayarlar. Özellik ayarlandığında, sertifika zincirinin varlığı kontrol edilir; eğer yoksa, doğrulama sonucu {@link ValidationStatus#Undefined} olur ve bu, Adobe Acrobat davranışına karşılık gelir. Yalnızca çevrimiçi iptal durumunu kontrol etmek istiyorsanız, alanı {@code false} olarak ayarlayın. Varsayılan değer {@code false}'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Doğrulama süreci sırasında ağ ile ilgili işlemler için milisaniye cinsinden zaman aşımı süresini alır veya ayarlar. RequestTimeout özelliği, iptal durumu veya OCSP sunucuları gibi çevrimiçi kaynaklara erişilirken sistemin bir ağ yanıtı için bekleyeceği azami süreyi tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Bir sertifikanın doğrulanması için kullanılan yöntemi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ValidationMethod öğesi |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

PDF belgesindeki dijital imzalar için doğrulama modunu alır veya ayarlar. ValidationMode özelliği, doğrulama sürecinin katılığı belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ValidationMode öğesi |
