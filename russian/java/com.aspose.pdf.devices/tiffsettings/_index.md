---
title: TiffSettings
second_title: Aspose.PDF для справки по Java API
description: Этот класс представляет настройки для импорта PDF в Tiff.
type: docs
weight: 29
url: /ru/java/com.aspose.pdf.devices/tiffsettings/
---
**Наследование:**
java.lang.Object
```
public final class TiffSettings
```

Этот класс представляет настройки для импорта PDF в Tiff.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffSettings()](#TiffSettings--) | Инициализирует новый экземпляр класса TiffSettings. |
| [TiffSettings(int compressionType)](#TiffSettings-int-) | Инициализирует новый экземпляр класса TiffSettings. |
| [TiffSettings(Margins margins)](#TiffSettings-com.aspose.pdf.devices.Margins-) | Инициализирует новый экземпляр класса TiffSettings. |
| [TiffSettings(int compressionType, int colorDepth, Margins margins)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-) | Инициализирует новый экземпляр класса TiffSettings. |
| [TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-) | Инициализирует новый экземпляр класса TiffSettings. |
| [TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-int-) | Инициализирует новый экземпляр класса TiffSettings. |
| [TiffSettings(boolean skipBlankPages)](#TiffSettings-boolean-) | Инициализирует новый экземпляр класса TiffSettings. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Получение значения границы преобразования цветов в белый и черный. |
| [getClass()](#getClass--) |  |
| [getCompression()](#getCompression--) | Получает тип сжатия. |
| [getCoordinateType()](#getCoordinateType--) | Получает тип координат страницы (поля мультимедиа/обрезки). |
| [getDepth()](#getDepth--) | Получает глубину цвета. |
| [getIndexedConversionType()](#getIndexedConversionType--) | Получает IndexedConversionType. |
| [getMargins()](#getMargins--) | Получает поля. |
| [getShape()](#getShape--) | Получает тип фигуры. |
| [getSkipBlankPages()](#getSkipBlankPages--) | Получает значение, указывающее, следует ли пропускать пустые страницы. |
| [hashCode()](#hashCode--) |  |
| [isUseAlternativeImageEngine()](#isUseAlternativeImageEngine--) | Получает флаг, определяющий, используется ли альтернативный механизм обработки изображений. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(float value)](#setBrightness-float-) | Задайте границу значения преобразования цветов в белый и черный. |
| [setCompression(int value)](#setCompression-int-) | Устанавливает тип сжатия. |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Устанавливает тип координат страницы (поля Media/Crop). |
| [setDepth(int value)](#setDepth-int-) | Получает глубину цвета. |
| [setIndexedConversionType(int value)](#setIndexedConversionType-int-) | Задает IndexedConversionType. |
| [setShape(int value)](#setShape-int-) | Устанавливает тип фигуры. |
| [setSkipBlankPages(boolean value)](#setSkipBlankPages-boolean-) | Задает значение, указывающее, следует ли пропускать пустые страницы. |
| [setUseAlternativeImageEngine(boolean useAlternativeImageEngine)](#setUseAlternativeImageEngine-boolean-) | Устанавливает флаг, определяющий, используется ли альтернативный механизм обработки изображений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSettings() {#TiffSettings--}
```
public TiffSettings()
```


Инициализирует новый экземпляр класса TiffSettings.

### TiffSettings(int compressionType) {#TiffSettings-int-}
```
public TiffSettings(int compressionType)
```


Инициализирует новый экземпляр класса TiffSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| compressionType | int | Тип сжатия. |

### TiffSettings(Margins margins) {#TiffSettings-com.aspose.pdf.devices.Margins-}
```
public TiffSettings(Margins margins)
```


Инициализирует новый экземпляр класса TiffSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | Поля. |

### TiffSettings(int compressionType, int colorDepth, Margins margins) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins)
```


Инициализирует новый экземпляр класса TiffSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| compressionType | int | Тип сжатия. |
| colorDepth | int | Глубина цвета. |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | Поля. |

### TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages)
```


Инициализирует новый экземпляр класса TiffSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| compressionType | int | Тип сжатия. |
| colorDepth | int | Глубина цвета. |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | Поля. |
| skipBlankPages | boolean | если установлено значение true, нужно пропускать пустые страницы |

### TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-int-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType)
```


Инициализирует новый экземпляр класса TiffSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| compressionType | int | Тип сжатия. |
| colorDepth | int | Глубина цвета. |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | Поля. |
| skipBlankPages | boolean | если установлено значение true, нужно пропускать пустые страницы. |
| shapeType | int | Тип фигуры. |

### TiffSettings(boolean skipBlankPages) {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```


Инициализирует новый экземпляр класса TiffSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| skipBlankPages | boolean |  если установлено значение true[пропускать пустые страницы]. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Получение значения границы преобразования цветов в белый и черный. Этот параметр можно применять с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или ColorDepth.Format1bpp == 1

**Возвращает:**
float - плавающее значение яркости должно быть в диапазоне от 0 до 1. По умолчанию значение равно 0.33f
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCompression() {#getCompression--}
```
public int getCompression()
```


Получает тип сжатия.

Значение: тип сжатия.

--------------------

Значение по умолчанию — CompressionType.LZW.

**Возвращает:**
int - элемент CompressionType
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Получает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию.

**Возвращает:**
int - значение PageCoordinateType
### getDepth() {#getDepth--}
```
public int getDepth()
```


Получает глубину цвета.

Значение: глубина цвета.

--------------------

Значение по умолчанию — ColorDepth.Default.

**Возвращает:**
int - элемент ColorDepth
### getIndexedConversionType() {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```


Получает IndexedConversionType. Значение по умолчанию — Простой.

**Возвращает:**
int — элемент IndexedConversionType
### getMargins() {#getMargins--}
```
public Margins getMargins()
```


Получает поля.

**Возвращает:**
[Margins](../../com.aspose.pdf.devices/margins) - Объект поля
### getShape() {#getShape--}
```
public int getShape()
```


Получает тип фигуры.

Значение: тип фигуры.

--------------------

Значение по умолчанию — ShapeType.None.

**Возвращает:**
int - элемент ShapeType
### getSkipBlankPages() {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```


Получает значение, указывающее, следует ли пропускать пустые страницы.

Значение: true, если нужно пропускать пустые страницы; в противном случае ложь.

--------------------

Значение по умолчанию — ложь

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isUseAlternativeImageEngine() {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```


Получает флаг, определяющий, используется ли альтернативный механизм обработки изображений. Значение True используется по умолчанию для ОС Linux. Для ОС Windows значение по умолчанию — false.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBrightness(float value) {#setBrightness-float-}
```
public void setBrightness(float value)
```


Задайте границу значения преобразования цветов в белый и черный. Этот параметр можно применять с EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle или ColorDepth.Format1bpp == 1

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | : Значение яркости должно быть в диапазоне от 0 до 1. По умолчанию значение равно 0.33f |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Устанавливает тип сжатия.

Значение: тип сжатия.

--------------------

Значение по умолчанию — CompressionType.LZW.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент CompressionType |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Устанавливает тип координат страницы (поля Media/Crop). Значение CropBox используется по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | PageCoordinateType |

### setDepth(int value) {#setDepth-int-}
```
public void setDepth(int value)
```


Получает глубину цвета.

Значение: глубина цвета.

--------------------

Значение по умолчанию — ColorDepth.Default.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ColorDepth |

### setIndexedConversionType(int value) {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```


Задает IndexedConversionType.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент IndexedConversionType |

### setShape(int value) {#setShape-int-}
```
public void setShape(int value)
```


Устанавливает тип фигуры.

Значение: тип фигуры.

--------------------

Значение по умолчанию — ShapeType.None.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ShapeType |

### setSkipBlankPages(boolean value) {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```


Задает значение, указывающее, следует ли пропускать пустые страницы.

Значение: true, если нужно пропускать пустые страницы; в противном случае ложь.

--------------------

Значение по умолчанию — ложь

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUseAlternativeImageEngine(boolean useAlternativeImageEngine) {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```


Устанавливает флаг, определяющий, используется ли альтернативный механизм обработки изображений.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| useAlternativeImageEngine | boolean | логическое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
