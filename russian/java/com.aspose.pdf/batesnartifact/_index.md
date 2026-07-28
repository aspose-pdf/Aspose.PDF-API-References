---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс описывает артефакт нумерации Бейтса."
type: docs
weight: 290
url: /ru/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Класс описывает артефакт нумерации Бейтса.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Инициализирует новый экземпляр класса {@link BatesNArtifact}. Этот конструктор внутренний и создаёт экземпляр артефакта заголовка со значениями по умолчанию. |

## Методы

| Метод | Описание |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Получает или задаёт количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установить значение меньше 3, оно будет скорректировано до 3. Если установить значение больше 15, оно будет скорректировано до 15. Значение по умолчанию — 6. |
| [getPrefix](#getPrefix--) | Получает или задаёт префикс, добавляемый к номеру Бейтса. |
| [getStartNumber](#getStartNumber--) | Получает или задаёт начальный номер для нумерации Бейтса. Значение должно быть больше или равно 1. Если установить значение меньше 1, оно будет скорректировано до 1. |
| [getSuffix](#getSuffix--) | Получает или задаёт суффикс, добавляемый к номеру Бейтса. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Получает или задаёт количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установить значение меньше 3, оно будет скорректировано до 3. Если установить значение больше 15, оно будет скорректировано до 15. Значение по умолчанию — 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Получает или задаёт префикс, добавляемый к номеру Бейтса. |
| [setStartNumber](#setStartNumber-int-) | Получает или задаёт начальный номер для нумерации Бейтса. Значение должно быть больше или равно 1. Если установить значение меньше 1, оно будет скорректировано до 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Получает или задаёт суффикс, добавляемый к номеру Бейтса. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Инициализирует новый экземпляр класса {@link BatesNArtifact}. Этот конструктор внутренний и создаёт экземпляр артефакта заголовка со значениями по умолчанию.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Получает или задаёт количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установить значение меньше 3, оно будет скорректировано до 3. Если установить значение больше 15, оно будет скорректировано до 15. Значение по умолчанию — 6.

**Returns:**
int значение

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Получает или задаёт префикс, добавляемый к номеру Бейтса.

**Returns:**
строковое значение

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Получает или задаёт начальный номер для нумерации Бейтса. Значение должно быть больше или равно 1. Если установить значение меньше 1, оно будет скорректировано до 1.

**Returns:**
int значение

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Получает или задаёт суффикс, добавляемый к номеру Бейтса.

**Returns:**
строковое значение

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Получает или задаёт количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установить значение меньше 3, оно будет скорректировано до 3. Если установить значение больше 15, оно будет скорректировано до 15. Значение по умолчанию — 6.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setPrefix {#setPrefix-java.lang.String-}
Получает или задаёт префикс, добавляемый к номеру Бейтса.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Получает или задаёт начальный номер для нумерации Бейтса. Значение должно быть больше или равно 1. Если установить значение меньше 1, оно будет скорректировано до 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setSuffix {#setSuffix-java.lang.String-}
Получает или задаёт суффикс, добавляемый к номеру Бейтса.
