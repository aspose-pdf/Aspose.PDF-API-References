---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс параметров сохранения документа в формате markdown."
type: docs
weight: 60
url: /ru/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Представляет класс параметров сохранения документа в формате markdown.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Создаёт параметр экземпляра для сохранения документа в формате markdown. |

## Методы

| Метод | Описание |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Получить или установить прямоугольную область для извлечения содержимого в markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Получает или задаёт стиль выделения для генерируемого документа. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Получает и задаёт свойство, указывающее, следует ли извлекать векторную графику. |
| [getHeadingLevels](#getHeadingLevels--) | Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия распознавания заголовков {@link HeadingRecognitionStrategy#Heuristic} будет выбрана при установке стратегий {@link HeadingRecognitionStrategy#Auto}, даже если документ содержит закладки. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Получает или задаёт стратегию распознавания заголовков. |
| [getHeadingStyle](#getHeadingStyle--) | Получает или задаёт стиль заголовков для генерируемого документа. |
| [getLineBreakStyle](#getLineBreakStyle--) | Получает или задаёт стиль разрыва строки для генерируемого документа. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Получает и задаёт разрешение на преобразование нижних и верхних индексов. Это значение по умолчанию равно true. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Получает и задаёт разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в markdown‑просмотрщике текст будет обтекать изображение. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Получить или установить прямоугольную область для извлечения содержимого в markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Получает или задаёт стиль выделения для генерируемого документа. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Получает и задаёт свойство, указывающее, следует ли извлекать векторную графику. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия распознавания заголовков {@link HeadingRecognitionStrategy#Heuristic} будет выбрана при установке стратегий {@link HeadingRecognitionStrategy#Auto}, даже если документ содержит закладки. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Получает или задаёт стратегию распознавания заголовков. |
| [setHeadingStyle](#setHeadingStyle-int-) | Получает или задаёт стиль заголовков для генерируемого документа. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Получает или задаёт стиль разрыва строки для генерируемого документа. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Получает и задаёт разрешение на преобразование нижних и верхних индексов. Это значение по умолчанию равно true. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Получает и задаёт разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в markdown‑просмотрщике текст будет обтекать изображение. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Создаёт параметр экземпляра для сохранения документа в формате markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Получить или установить прямоугольную область для извлечения содержимого в markdown.

**Returns:**
Экземпляр Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Получает или задаёт стиль выделения для генерируемого документа.

**Returns:**
Элемент EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Получает и задаёт свойство, указывающее, следует ли извлекать векторную графику.

**Returns:**
логическое значение

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия распознавания заголовков {@link HeadingRecognitionStrategy#Heuristic} будет выбрана при установке стратегий {@link HeadingRecognitionStrategy#Auto}, даже если документ содержит закладки.

**Returns:**
экземпляр HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Получает или задаёт стратегию распознавания заголовков.

**Returns:**
элемент HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Получает или задаёт стиль заголовков для генерируемого документа.

**Returns:**
элемент HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Получает или задаёт стиль разрыва строки для генерируемого документа.

**Returns:**
элемент LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown.

**Returns:**
строковое значение

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown.

**Returns:**
строковое значение

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Получает и задаёт разрешение на преобразование нижних и верхних индексов. Это значение по умолчанию равно true.

**Returns:**
логическое значение

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Получает и задаёт разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в markdown‑просмотрщике текст будет обтекать изображение.

**Returns:**
логическое значение

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Получить или установить прямоугольную область для извлечения содержимого в markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Получает или задаёт стиль выделения для генерируемого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Элемент EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Получает и задаёт свойство, указывающее, следует ли извлекать векторную графику.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Определяет ожидаемые уровни заголовков, используемые в стратегии распознавания заголовков по размеру шрифта. Если значение этого свойства установлено, то стратегия распознавания заголовков {@link HeadingRecognitionStrategy#Heuristic} будет выбрана при установке стратегий {@link HeadingRecognitionStrategy#Auto}, даже если документ содержит закладки.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Получает или задаёт стратегию распознавания заголовков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | элемент HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Получает или задаёт стиль заголовков для генерируемого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | элемент HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Получает или задаёт стиль разрыва строки для генерируемого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | элемент LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Если значение не указано, изображения будут записаны в тот же каталог, что и сам файл markdown. Это не путь, а только имя! Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Получает и задаёт имя каталога для сохранения ресурсов документа, таких как изображения. Этот каталог будет автоматически создан в каталоге с сохранённым файлом markdown.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Получает и задаёт разрешение на преобразование нижних и верхних индексов. Это значение по умолчанию равно true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Получает и задаёт разрешение на использование тега img для вставки изображений слева и справа от текста. В этом случае в markdown‑просмотрщике текст будет обтекать изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |
