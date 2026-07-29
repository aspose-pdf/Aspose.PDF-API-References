---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Справочник API Aspose.PDF для Java"
description: "Предоставляет настройки для функции автотегирования в PDF‑документах. Класс {@link AutoTaggingSettings} позволяет настраивать параметры автоматического тегирования PDF‑контента. Он."
type: docs
weight: 230
url: /ru/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Предоставляет настройки для функции автотегирования в PDF‑документах. Класс {@link AutoTaggingSettings} позволяет настраивать параметры автоматического тегирования PDF‑контента. Он включает свойства для включения или отключения автотегирования, указания стратегии распознавания заголовков и определения уровней заголовков на основе размеров шрифтов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [getDefault](#getDefault--) | Получает настройки по умолчанию для функции автотегирования в PDF‑документах. Настройки по умолчанию включают автотегирование и используют автоматическую стратегию распознавания заголовков. Эти настройки могут использоваться в качестве базовой конфигурации для конвертации PDF‑формата или других операций, требующих автоматического тегирования PDF‑контента. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Получает или задаёт значение, указывающее, включена ли функция автотегирования. Когда она включена, функция автотегирования автоматически генерирует тегированный контент для PDF‑документа, что может улучшить доступность и структуру. |
| [getHeadingLevels](#getHeadingLevels--) | Получает или задаёт уровни заголовков, используемые для определения структуры заголовков в PDF‑документе. Свойство {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) позволяет настраивать сопоставление размеров шрифтов уровням заголовков. Это используется в процессе автотегирования для идентификации и назначения соответствующих уровней заголовков на основе размера шрифта текстовых элементов в документе. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Получает или задает стратегию, используемую для распознавания заголовков в документе во время автоматической разметки. Свойство {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) определяет, как заголовки идентифицируются в документе. Доступные стратегии включают распознавание заголовков на основе структуры, эвристического анализа или автоматического обнаружения. Установка этого свойства в {@link HeadingRecognitionStrategy#None} отключает распознавание заголовков. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Получает или задаёт значение, указывающее, включена ли функция автотегирования. Когда она включена, функция автотегирования автоматически генерирует тегированный контент для PDF‑документа, что может улучшить доступность и структуру. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Получает или задаёт уровни заголовков, используемые для определения структуры заголовков в PDF‑документе. Свойство {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) позволяет настраивать сопоставление размеров шрифтов уровням заголовков. Это используется в процессе автотегирования для идентификации и назначения соответствующих уровней заголовков на основе размера шрифта текстовых элементов в документе. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Получает или задает стратегию, используемую для распознавания заголовков в документе во время автоматической разметки. Свойство {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) определяет, как заголовки идентифицируются в документе. Доступные стратегии включают распознавание заголовков на основе структуры, эвристического анализа или автоматического обнаружения. Установка этого свойства в {@link HeadingRecognitionStrategy#None} отключает распознавание заголовков. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Получает настройки по умолчанию для функции автотегирования в PDF‑документах. Настройки по умолчанию включают автотегирование и используют автоматическую стратегию распознавания заголовков. Эти настройки могут использоваться в качестве базовой конфигурации для конвертации PDF‑формата или других операций, требующих автоматического тегирования PDF‑контента.

**Returns:**
Экземпляр AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Получает или задаёт значение, указывающее, включена ли функция автотегирования. Когда она включена, функция автотегирования автоматически генерирует тегированный контент для PDF‑документа, что может улучшить доступность и структуру.

**Returns:**
логическое значение

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Получает или задаёт уровни заголовков, используемые для определения структуры заголовков в PDF‑документе. Свойство {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) позволяет настраивать сопоставление размеров шрифтов уровням заголовков. Это используется в процессе автотегирования для идентификации и назначения соответствующих уровней заголовков на основе размера шрифта текстовых элементов в документе.

**Returns:**
экземпляр HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Получает или задает стратегию, используемую для распознавания заголовков в документе во время автоматической разметки. Свойство {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) определяет, как заголовки идентифицируются в документе. Доступные стратегии включают распознавание заголовков на основе структуры, эвристического анализа или автоматического обнаружения. Установка этого свойства в {@link HeadingRecognitionStrategy#None} отключает распознавание заголовков.

**Returns:**
элемент HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Получает или задаёт значение, указывающее, включена ли функция автотегирования. Когда она включена, функция автотегирования автоматически генерирует тегированный контент для PDF‑документа, что может улучшить доступность и структуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Получает или задаёт уровни заголовков, используемые для определения структуры заголовков в PDF‑документе. Свойство {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) позволяет настраивать сопоставление размеров шрифтов уровням заголовков. Это используется в процессе автотегирования для идентификации и назначения соответствующих уровней заголовков на основе размера шрифта текстовых элементов в документе.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Получает или задает стратегию, используемую для распознавания заголовков в документе во время автоматической разметки. Свойство {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) определяет, как заголовки идентифицируются в документе. Доступные стратегии включают распознавание заголовков на основе структуры, эвристического анализа или автоматического обнаружения. Установка этого свойства в {@link HeadingRecognitionStrategy#None} отключает распознавание заголовков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | элемент HeadingRecognitionStrategy |
