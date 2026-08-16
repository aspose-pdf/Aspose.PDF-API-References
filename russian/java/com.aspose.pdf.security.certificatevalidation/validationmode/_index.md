---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Справочник API Aspose.PDF для Java"
description: "Указывает режим проверки для процессов валидации подписи PDF."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Указывает режим проверки для процессов валидации подписи PDF.

## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Представляет режим, при котором проверка не выполняется. |
| [OnlyCheck](#OnlyCheck) | Представляет режим, в котором проводится проверка, но её результат не влияет на проверку цифровой подписи. Вы можете проверить результат проверки самостоятельно. |
| [Strict](#Strict) | Представляет режим, в котором проводится проверка, и её результат влияет на проверку цифровой подписи. Если сертификат не может быть проверен, цифровая подпись считается недействительной. Вы можете проверить результат проверки самостоятельно. |

### None {#None}
```
public static final int None
```

Представляет режим, при котором проверка не выполняется.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Представляет режим, в котором проводится проверка, но её результат не влияет на проверку цифровой подписи. Вы можете проверить результат проверки самостоятельно.

### Strict {#Strict}
```
public static final int Strict
```

Представляет режим, в котором проводится проверка, и её результат влияет на проверку цифровой подписи. Если сертификат не может быть проверен, цифровая подпись считается недействительной. Вы можете проверить результат проверки самостоятельно.
