---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет результат процесса проверки сертификата. Класс ValidationResult предоставляет информацию о результате проверки сертификата, включая его."
type: docs
weight: 40
url: /ru/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Представляет результат процесса проверки сертификата. Класс ValidationResult предоставляет информацию о результате проверки сертификата, включая его статус и сообщение, описывающее любые проблемы, возникшие во время проверки.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Создаёт экземпляр класса {@link ValidationResult}. |

## Методы

| Метод | Описание |
| --- | --- |
| [getMessage](#getMessage--) | Представляет сообщение, связанное с результатом проверки. Свойство Message предоставляет дополнительный контекст или информацию о состоянии результата проверки. |
| [getStatus](#getStatus--) | Получает статус процесса проверки сертификата. Свойство Status указывает результат проверки сертификата. Возможные значения определены в перечислении {@link ValidationStatus}, например Valid, Invalid или Undefined. Это даёт представление о том, прошёл ли сертификат проверку или нет. |
| [setMessage](#setMessage-java.lang.String-) | Представляет сообщение, связанное с результатом проверки. Свойство Message предоставляет дополнительный контекст или информацию о состоянии результата проверки. |
| [setStatus](#setStatus-int-) | Получает статус процесса проверки сертификата. Свойство Status указывает результат проверки сертификата. Возможные значения определены в перечислении {@link ValidationStatus}, например Valid, Invalid или Undefined. Это даёт представление о том, прошёл ли сертификат проверку или нет. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Создаёт экземпляр класса {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Представляет сообщение, связанное с результатом проверки. Свойство Message предоставляет дополнительный контекст или информацию о состоянии результата проверки.

**Returns:**
строковое значение

### getStatus {#getStatus--}
```
public final int getStatus()
```

Получает статус процесса проверки сертификата. Свойство Status указывает результат проверки сертификата. Возможные значения определены в перечислении {@link ValidationStatus}, например Valid, Invalid или Undefined. Это даёт представление о том, прошёл ли сертификат проверку или нет.

**Returns:**
Элемент ValidationStatus

### setMessage {#setMessage-java.lang.String-}
Представляет сообщение, связанное с результатом проверки. Свойство Message предоставляет дополнительный контекст или информацию о состоянии результата проверки.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Получает статус процесса проверки сертификата. Свойство Status указывает результат проверки сертификата. Возможные значения определены в перечислении {@link ValidationStatus}, например Valid, Invalid или Undefined. Это даёт представление о том, прошёл ли сертификат проверку или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Элемент ValidationStatus |
