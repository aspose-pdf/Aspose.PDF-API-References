---
title: "OutputIntent"
linktitle: "OutputIntent"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет намерение вывода, которое соответствует цветовым характеристикам PDF‑документа и характеристикам целевого устройства вывода или производственной среды, в которой документ будет."
type: docs
weight: 3290
url: /ru/java/com.aspose.pdf/outputintent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OutputIntent

```
public final class OutputIntent extends Object
```

Представляет намерение вывода, которое соответствует цветовым характеристикам PDF‑документа и характеристикам целевого устройства вывода или производственной среды, в которой документ будет печататься.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OutputIntent](#OutputIntent-java.lang.String-) | Инициализирует новый экземпляр класса {@link OutputIntent} с указанным идентификатором условия вывода. |

## Методы

| Метод | Описание |
| --- | --- |
| [getInfo](#getInfo--) | Возвращает человекочитаемый текст, содержащий дополнительную информацию или комментарии о предполагаемом целевом устройстве или производственном условии. |
| [getOutputCondition](#getOutputCondition--) | Возвращает текст, кратко идентифицирующий предполагаемое устройство вывода или производственное условие в человекочитаемом виде. |
| [getOutputConditionIdentifier](#getOutputConditionIdentifier--) | Возвращает текст, идентифицирующий предполагаемое устройство вывода или производственное условие в человеко- или машиночитаемом виде. |
| [getRegistryName](#getRegistryName--) | Возвращает текст, указывающий реестр, в котором определено условие, обозначенное {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}). |
| [getSubtype](#getSubtype--) | Возвращает подтип намерения вывода. |
| [setInfo](#setInfo-java.lang.String-) | Устанавливает человекочитаемый текст, содержащий дополнительную информацию или комментарии о предполагаемом целевом устройстве или производственном условии. |
| [setOutputCondition](#setOutputCondition-java.lang.String-) | Получает или задает текст, кратко идентифицирующий предполагаемое устройство вывода или производственное условие в человекочитаемом виде. |
| [setOutputConditionIdentifier](#setOutputConditionIdentifier-java.lang.String-) | Устанавливает текст, идентифицирующий предполагаемое устройство вывода или производственное условие в человеко- или машиночитаемом виде. |
| [setRegistryName](#setRegistryName-java.lang.String-) | Устанавливает текст, указывающий реестр, в котором определено условие, обозначенное {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}). |

### OutputIntent {#OutputIntent-java.lang.String-}
Инициализирует новый экземпляр класса {@link OutputIntent} с указанным идентификатором условия вывода.

### getInfo {#getInfo--}
```
public final String getInfo()
```

Возвращает человекочитаемый текст, содержащий дополнительную информацию или комментарии о предполагаемом целевом устройстве или производственном условии.

**Returns:**
строковое значение

### getOutputCondition {#getOutputCondition--}
```
public final String getOutputCondition()
```

Возвращает текст, кратко идентифицирующий предполагаемое устройство вывода или производственное условие в человекочитаемом виде.

**Returns:**
строковое значение

### getOutputConditionIdentifier {#getOutputConditionIdentifier--}
```
public final String getOutputConditionIdentifier()
```

Возвращает текст, идентифицирующий предполагаемое устройство вывода или производственное условие в человеко- или машиночитаемом виде.

**Returns:**
строковое значение

### getRegistryName {#getRegistryName--}
```
public final String getRegistryName()
```

Возвращает текст, указывающий реестр, в котором определено условие, обозначенное {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}).

**Returns:**
строковое значение

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Возвращает подтип намерения вывода.

**Returns:**
строковое значение

### setInfo {#setInfo-java.lang.String-}
Устанавливает человекочитаемый текст, содержащий дополнительную информацию или комментарии о предполагаемом целевом устройстве или производственном условии.

### setOutputCondition {#setOutputCondition-java.lang.String-}
Получает или задает текст, кратко идентифицирующий предполагаемое устройство вывода или производственное условие в человекочитаемом виде.

### setOutputConditionIdentifier {#setOutputConditionIdentifier-java.lang.String-}
Устанавливает текст, идентифицирующий предполагаемое устройство вывода или производственное условие в человеко- или машиночитаемом виде.

### setRegistryName {#setRegistryName-java.lang.String-}
Устанавливает текст, указывающий реестр, в котором определено условие, обозначенное {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}).
