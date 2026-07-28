---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет параметры проверки цифровой подписи в PDF‑документе."
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Представляет параметры проверки цифровой подписи в PDF‑документе.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Создаёт экземпляр класса {@link ValidationOptions}. |

## Методы

| Метод | Описание |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Получает или задаёт значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки. Когда свойство установлено, наличие цепочки сертификатов будет проверяться; если её нет, результат проверки будет {@link ValidationStatus#Undefined}, что соответствует поведению Adobe Acrobat. Если требуется только онлайн‑проверка статуса отзыва, установите значение в {@code false}. Значение по умолчанию — {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Получает или задаёт длительность тайм‑аута в миллисекундах для сетевых операций во время процесса проверки. Свойство RequestTimeout определяет максимальное время, которое система должна ждать сетевого ответа при доступе к онлайн‑ресурсам, таким как статус отзыва или серверы OCSP. |
| [getValidationMethod](#getValidationMethod--) | Получает или задаёт метод, используемый для проверки сертификата. |
| [getValidationMode](#getValidationMode--) | Получает или задаёт режим проверки цифровых подписей в PDF‑документе. Свойство ValidationMode определяет степень строгости процесса проверки. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Получает или задаёт значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки. Когда свойство установлено, наличие цепочки сертификатов будет проверяться; если её нет, результат проверки будет {@link ValidationStatus#Undefined}, что соответствует поведению Adobe Acrobat. Если требуется только онлайн‑проверка статуса отзыва, установите значение в {@code false}. Значение по умолчанию — {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Получает или задаёт длительность тайм‑аута в миллисекундах для сетевых операций во время процесса проверки. Свойство RequestTimeout определяет максимальное время, которое система должна ждать сетевого ответа при доступе к онлайн‑ресурсам, таким как статус отзыва или серверы OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | Получает или задаёт метод, используемый для проверки сертификата. |
| [setValidationMode](#setValidationMode-int-) | Получает или задаёт режим проверки цифровых подписей в PDF‑документе. Свойство ValidationMode определяет степень строгости процесса проверки. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Создаёт экземпляр класса {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Получает или задаёт значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки. Когда свойство установлено, наличие цепочки сертификатов будет проверяться; если её нет, результат проверки будет {@link ValidationStatus#Undefined}, что соответствует поведению Adobe Acrobat. Если требуется только онлайн‑проверка статуса отзыва, установите значение в {@code false}. Значение по умолчанию — {@code false}.

**Returns:**
логическое значение

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Получает или задаёт длительность тайм‑аута в миллисекундах для сетевых операций во время процесса проверки. Свойство RequestTimeout определяет максимальное время, которое система должна ждать сетевого ответа при доступе к онлайн‑ресурсам, таким как статус отзыва или серверы OCSP.

**Returns:**
int значение

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Получает или задаёт метод, используемый для проверки сертификата.

**Returns:**
Элемент ValidationMethod

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Получает или задаёт режим проверки цифровых подписей в PDF‑документе. Свойство ValidationMode определяет степень строгости процесса проверки.

**Returns:**
Элемент ValidationMode

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Получает или задаёт значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки. Когда свойство установлено, наличие цепочки сертификатов будет проверяться; если её нет, результат проверки будет {@link ValidationStatus#Undefined}, что соответствует поведению Adobe Acrobat. Если требуется только онлайн‑проверка статуса отзыва, установите значение в {@code false}. Значение по умолчанию — {@code false}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Получает или задаёт длительность тайм‑аута в миллисекундах для сетевых операций во время процесса проверки. Свойство RequestTimeout определяет максимальное время, которое система должна ждать сетевого ответа при доступе к онлайн‑ресурсам, таким как статус отзыва или серверы OCSP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Получает или задаёт метод, используемый для проверки сертификата.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Элемент ValidationMethod |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Получает или задаёт режим проверки цифровых подписей в PDF‑документе. Свойство ValidationMode определяет степень строгости процесса проверки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Элемент ValidationMode |
