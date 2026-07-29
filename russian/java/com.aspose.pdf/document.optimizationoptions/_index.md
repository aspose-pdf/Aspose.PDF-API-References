---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс, описывающий алгоритм оптимизации документа. Экземпляр этого класса может использоваться в качестве параметра метода OptimizeResources(). @deprecated Этот класс устарел. Пожалуйста."
type: docs
weight: 1110
url: /ru/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Класс, описывающий алгоритм оптимизации документа. Экземпляр этого класса может использоваться в качестве параметра метода OptimizeResources(). @deprecated Этот класс устарел. Пожалуйста, используйте com.aspose.pdf.optimization.OptimizationOptions вместо него.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Устарело. |

## Методы

| Метод | Описание |
| --- | --- |
| [all](#all--) | Создаёт стратегию оптимизации со всеми активированными опциями. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Указывает максимальное измерение изображения. Если ширина или высота существующего изображения превышает это значение, размер изображения будет пропорционально уменьшен. |
| [getResolution](#getResolution--) | Указывает новое DPI изображения, когда используется флаг CompressIamges. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Указывает максимальное измерение изображения. Если ширина или высота существующего изображения превышает это значение, размер изображения будет пропорционально уменьшен. |
| [setResolution](#setResolution-int-) | Указывает новое DPI изображения, когда используется флаг CompressIamges. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Устарело.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Создаёт стратегию оптимизации со всеми активированными опциями.

**Returns:**
Объект OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Указывает максимальное измерение изображения. Если ширина или высота существующего изображения превышает это значение, размер изображения будет пропорционально уменьшен.

**Returns:**
максимальное измерение изображения

### getResolution {#getResolution--}
```
public int getResolution()
```

Указывает новое DPI изображения, когда используется флаг CompressIamges.

**Returns:**
разрешение изображения

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Указывает максимальное измерение изображения. Если ширина или высота существующего изображения превышает это значение, размер изображения будет пропорционально уменьшен.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| измерение |  | максимальное измерение изображения |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Указывает новое DPI изображения, когда используется флаг CompressIamges.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpi |  | разрешение изображения |
