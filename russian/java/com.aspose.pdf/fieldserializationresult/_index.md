---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет результат процесса сериализации поля формы."
type: docs
weight: 1390
url: /ru/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Представляет результат процесса сериализации поля формы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Инициализирует новый экземпляр класса {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Инициализирует новый экземпляр класса {@link FieldSerializationResult}. |

## Методы

| Метод | Описание |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Получает сообщения об ошибках, связанные с процессом сериализации. Значение: Набор сообщений об ошибках. |
| [getFieldFullName](#getFieldFullName--) | Получает полное имя поля. Значение: Полное имя поля. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Получает статус сериализации поля формы. Значение: Статус сериализации поля формы. |
| [getWarningMessages](#getWarningMessages--) | Получает сообщения предупреждений, связанные с процессом сериализации. Значение: Набор сообщений предупреждений. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Обновляет статус сериализации и добавляет сообщение в соответствующий набор. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Инициализирует новый экземпляр класса {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Инициализирует новый экземпляр класса {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Получает сообщения об ошибках, связанные с процессом сериализации. Значение: Набор сообщений об ошибках.

**Returns:**
Экземпляр HashSet из String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Получает полное имя поля. Значение: Полное имя поля.

**Returns:**
строковое значение

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Получает статус сериализации поля формы. Значение: Статус сериализации поля формы.

**Returns:**
Элемент FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Получает сообщения предупреждений, связанные с процессом сериализации. Значение: Набор сообщений предупреждений.

**Returns:**
Экземпляр HashSet из String

### updateStatus {#updateStatus-int-java.lang.String-}
Обновляет статус сериализации и добавляет сообщение в соответствующий набор.
