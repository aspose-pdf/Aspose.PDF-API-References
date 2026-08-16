---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс результата сравнения двух страниц PDF."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Представляет класс результата сравнения двух страниц PDF.

## Методы

| Метод | Описание |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Преобразует массив различий в растровое изображение, используя указанные цвета. |
| [dispose](#dispose--) | Выполняет необходимые операции очистки перед уничтожением объекта. |
| [getDestinationImage](#getDestinationImage--) | Возвращает новое растровое изображение, представляющее целевое изображение, применяя массив различий к исходному изображению. |
| [getDifference](#getDifference--) | Получает массив различий. Этот массив похож на массив данных оригинального изображения, полученный в результате метода LockBits. |
| [getHeight](#getHeight--) | Высота различия. |
| [getSourceImage](#getSourceImage--) | Получает изображение первой сравниваемой страницы. Формат пикселей изображения — 24 bpp. |
| [getStride](#getStride--) | Шаг (stride) данных изображения различий. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Преобразует массив различий в растровое изображение, используя указанные цвета.

### dispose {#dispose--}
```
public final void dispose()
```

Выполняет необходимые операции очистки перед уничтожением объекта.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Возвращает новое растровое изображение, представляющее целевое изображение, применяя массив различий к исходному изображению.

**Returns:**
Целевое изображение.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Получает массив различий. Этот массив похож на массив данных оригинального изображения, полученный в результате метода LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

Высота различия.

**Returns:**
int значение

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Получает изображение первой сравниваемой страницы. Формат пикселей изображения — 24 bpp.

**Returns:**
Экземпляр BufferedImage

### getStride {#getStride--}
```
public final int getStride()
```

Шаг (stride) данных изображения различий.

**Returns:**
int значение
