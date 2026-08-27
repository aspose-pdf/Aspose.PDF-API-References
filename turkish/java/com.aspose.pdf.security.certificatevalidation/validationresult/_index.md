---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir sertifikanın doğrulama sürecinin sonucunu temsil eder. ValidationResult sınıfı, bir sertifikanın doğrulanması sonucuyla ilgili bilgileri, bunların dahil olduğu, sağlar."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Bir sertifikanın doğrulama sürecinin sonucunu temsil eder. ValidationResult sınıfı, bir sertifikanın doğrulanması sonucuyla ilgili bilgi sağlar; durumunu ve doğrulama sırasında karşılaşılan sorunları açıklayan bir mesajı içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Bir {@link ValidationResult} sınıfının örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMessage](#getMessage--) | Doğrulama sonucu ile ilişkili mesajı temsil eder. Message özelliği, doğrulama sonucunun durumu hakkında ek bağlam veya bilgi sağlar. |
| [getStatus](#getStatus--) | Bir sertifikanın doğrulama sürecinin durumunu alır. Status özelliği, sertifika doğrulamasının sonucunu gösterir. Olası değerler {@link ValidationStatus} enumunda tanımlanmıştır; örneğin Valid, Invalid veya Undefined. Bu, sertifikanın doğrulama kontrollerini geçip geçmediği konusunda bir içgörü sağlar. |
| [setMessage](#setMessage-java.lang.String-) | Doğrulama sonucu ile ilişkili mesajı temsil eder. Message özelliği, doğrulama sonucunun durumu hakkında ek bağlam veya bilgi sağlar. |
| [setStatus](#setStatus-int-) | Bir sertifikanın doğrulama sürecinin durumunu alır. Status özelliği, sertifika doğrulamasının sonucunu gösterir. Olası değerler {@link ValidationStatus} enumunda tanımlanmıştır; örneğin Valid, Invalid veya Undefined. Bu, sertifikanın doğrulama kontrollerini geçip geçmediği konusunda bir içgörü sağlar. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Bir {@link ValidationResult} sınıfının örneğini oluşturur.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Doğrulama sonucu ile ilişkili mesajı temsil eder. Message özelliği, doğrulama sonucunun durumu hakkında ek bağlam veya bilgi sağlar.

**Returns:**
String değeri

### getStatus {#getStatus--}
```
public final int getStatus()
```

Bir sertifikanın doğrulama sürecinin durumunu alır. Status özelliği, sertifika doğrulamasının sonucunu gösterir. Olası değerler {@link ValidationStatus} enumunda tanımlanmıştır; örneğin Valid, Invalid veya Undefined. Bu, sertifikanın doğrulama kontrollerini geçip geçmediği konusunda bir içgörü sağlar.

**Returns:**
ValidationStatus öğesi

### setMessage {#setMessage-java.lang.String-}
Doğrulama sonucu ile ilişkili mesajı temsil eder. Message özelliği, doğrulama sonucunun durumu hakkında ek bağlam veya bilgi sağlar.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Bir sertifikanın doğrulama sürecinin durumunu alır. Status özelliği, sertifika doğrulamasının sonucunu gösterir. Olası değerler {@link ValidationStatus} enumunda tanımlanmıştır; örneğin Valid, Invalid veya Undefined. Bu, sertifikanın doğrulama kontrollerini geçip geçmediği konusunda bir içgörü sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ValidationStatus öğesi |
