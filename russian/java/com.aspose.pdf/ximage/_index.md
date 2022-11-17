---
title: XImage
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий изображение X-Object.
type: docs
weight: 409
url: /ru/java/com.aspose.pdf/ximage/
---
**Наследование:**
java.lang.Object
```
public final class XImage
```

Класс, представляющий изображение X-Object.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XImage(IPdfDataStream image)](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | только для внутреннего использования |
## Методы

| Метод | Описание |
| --- | --- |
| [containsTransparency()](#containsTransparency--) | Если изображение содержит прозрачность, чем вернуть true; в противном случае ложно. |
| [delete()](#delete--) | Удаляет изображение из родительской коллекции. |
| [detectColorType(BufferedImage bmp)](#detectColorType-java.awt.image.BufferedImage-) | Возвращает цветовой тип изображения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Возвращает цветовой тип изображения. |
| [getEngineImg()](#getEngineImg--) | Объект IPdfImage, описывающий изображение. |
| [getFilterType()](#getFilterType--) | Получает тип фильтра изображения. |
| [getGrayscaled()](#getGrayscaled--) | Получает версию изображения в оттенках серого. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getImage()](#getImage--) | Только для внутреннего использования |
| [getMetadata()](#getMetadata--) | Метаданные изображения. |
| [getName()](#getName--) | Получает имя изображения. |
| [getNameInCollection()](#getNameInCollection--) | Возвращает имя изображения в своей коллекции. |
| [getRawBytes()](#getRawBytes--) | Возвращает необработанные байты для изображения без декодирования. |
| [getRawParameters()](#getRawParameters--) | Получает необработанные параметры изображения |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [hashCode()](#hashCode--) |  |
| [isImage(IPdfPrimitive primitive)](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает true, если примитив является изображением. |
| [isTheSameObject(XImage image)](#isTheSameObject-com.aspose.pdf.XImage-) | Возвращает true, если оба изображения ссылаются на один и тот же объект. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rename(String name)](#rename-java.lang.String-) | Переименовывает изображение и заменяет все ссылки на изображение новым именем |
| [replace(InputStream image)](#replace-java.io.InputStream-) | Заменяет изображение на поток, указанный в изображении. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет данные изображения в поток как изображение JPEG. |
| [save(OutputStream stream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Сохраняет изображение в поток в требуемом формате. |
| [save(OutputStream stream, ImageType format, int resolution)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Сохраняет изображение в поток в требуемом формате. |
| [save(OutputStream stream, float xDpi, float yDpi)](#save-java.io.OutputStream-float-float-) | Сохраняет изображение в поток в требуемом формате. |
| [save(OutputStream stream, int resolution)](#save-java.io.OutputStream-int-) | Сохраняет изображение в поток в требуемом формате с указанным разрешением. |
| [saveInternal(System.IO.Stream stream, ImageType format, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal(System.IO.Stream stream, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Сохраняет данные изображения в поток как изображение JPEG с указанным разрешением. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя изображения. |
| [toStream()](#toStream--) | Возвращает исходный поток изображений. |
| [toString()](#toString--) | Возвращает строковое представление свойств объекта XImage. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XImage(IPdfDataStream image) {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
```
public XImage(IPdfDataStream image)
```


только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) | внутренний экземпляр |

### containsTransparency() {#containsTransparency--}
```
public boolean containsTransparency()
```


Если изображение содержит прозрачность, чем вернуть true; в противном случае ложно.

**Возвращает:**
boolean - логическое значение
### delete() {#delete--}
```
public void delete()
```


Удаляет изображение из родительской коллекции.

### detectColorType(BufferedImage bmp) {#detectColorType-java.awt.image.BufferedImage-}
```
public static int detectColorType(BufferedImage bmp)
```


Возвращает цветовой тип изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bmp | java.awt.image.BufferedImage | Изображение. |

**Возвращает:**
int - Тип цвета.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Возвращает цветовой тип изображения.

**Возвращает:**
int - значение типа цвета.
### getEngineImg() {#getEngineImg--}
```
public IPdfDataStream getEngineImg()
```


Объект IPdfImage, описывающий изображение. Только внутренний

**Возвращает:**
[IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) - IPdfDataStream
### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Получает тип фильтра изображения.

**Возвращает:**
int - элемент ImageFilterType
### getGrayscaled() {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```


Получает версию изображения в оттенках серого.

**Возвращает:**
java.awt.image.BufferedImage — буферизованное изображение
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

**Возвращает:**
интервал - целочисленное значение
### getImage() {#getImage--}
```
public System.Drawing.Bitmap getImage()
```


Только для внутреннего использования

**Возвращает:**
com.aspose.ms.System.Drawing.Bitmap — Изображение
### getMetadata() {#getMetadata--}
```
public final Metadata getMetadata()
```


Метаданные изображения.

**Возвращает:**
[Metadata](../../com.aspose.pdf/metadata) - Экземпляр метаданных
### getName() {#getName--}
```
public String getName()
```


Получает имя изображения. Обратите внимание, что если вы измените имя изображения, на которое есть ссылки в содержании страницы, документ может стать неверным. В этом случае используйте метод XImage.Rename.

**Возвращает:**
java.lang.String — Строка
### getNameInCollection() {#getNameInCollection--}
```
public String getNameInCollection()
```


Возвращает имя изображения в своей коллекции.

**Возвращает:**
java.lang.String — ключ изображения (имя).
### getRawBytes() {#getRawBytes--}
```
public byte[] getRawBytes()
```


Возвращает необработанные байты для изображения без декодирования.

**Возвращает:**
байт[] - массив байтов
### getRawParameters() {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```


Получает необработанные параметры изображения

**Возвращает:**
[RawParameters](../../com.aspose.pdf/rawparameters) - Экземпляр RawParameters
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isImage(IPdfPrimitive primitive) {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static boolean isImage(IPdfPrimitive primitive)
```


Возвращает true, если примитив является изображением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| primitive | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive |

**Возвращает:**
логическое значение - логическое значение
### isTheSameObject(XImage image) {#isTheSameObject-com.aspose.pdf.XImage-}
```
public boolean isTheSameObject(XImage image)
```


Возвращает true, если оба изображения ссылаются на один и тот же объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | Изображение для сравнения с «этим» изображением. |

**Возвращает:**
boolean — логическое значение, которое истинно, если изображения ссылаются на один и тот же объект.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rename(String name) {#rename-java.lang.String-}
```
public final void rename(String name)
```


Переименовывает изображение и заменяет все ссылки на изображение новым именем

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Новое имя изображения. |

### replace(InputStream image) {#replace-java.io.InputStream-}
```
public void replace(InputStream image)
```


Заменяет изображение на поток, указанный в изображении.

\*

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Поток с данными изображения. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет данные изображения в поток как изображение JPEG.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, где данные изображения будут сохранены. |

### save(OutputStream stream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream stream, ImageType format)
```


Сохраняет изображение в поток в требуемом формате.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, где изображение будет сохранено |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат, который будет использоваться для кодирования изображения. |

### save(OutputStream stream, ImageType format, int resolution) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
```
public void save(OutputStream stream, ImageType format, int resolution)
```


Сохраняет изображение в поток в требуемом формате.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, где изображение будет сохранено |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат, который будет использоваться для кодирования изображения. |
| resolution | int | Разрешение изображения |

### save(OutputStream stream, float xDpi, float yDpi) {#save-java.io.OutputStream-float-float-}
```
public void save(OutputStream stream, float xDpi, float yDpi)
```


Сохраняет изображение в поток в требуемом формате.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream, где изображение будет сохранено |
| xDpi | float | Горизонтальное разрешение изображения |
| yDpi | float | Вертикальное разрешение изображения |

### save(OutputStream stream, int resolution) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int resolution)
```


Сохраняет изображение в поток в требуемом формате с указанным разрешением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, где изображение будет сохранено |
| resolution | int | Разрешение изображения |

### saveInternal(System.IO.Stream stream, ImageType format, int resolution) {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}
```
public void saveInternal(System.IO.Stream stream, ImageType format, int resolution)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| format | [ImageType](../../com.aspose.pdf/imagetype) |  |
| resolution | int |  |

### saveInternal(System.IO.Stream stream, int resolution) {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
```
public void saveInternal(System.IO.Stream stream, int resolution)
```


Сохраняет данные изображения в поток как изображение JPEG с указанным разрешением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, где данные изображения будут сохранены. |
| resolution | int | Разрешение изображения |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя изображения. Обратите внимание, что если вы измените имя изображения, на которое есть ссылки в содержании страницы, документ может стать неверным. В этом случае используйте метод XImage.Rename.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### toStream() {#toStream--}
```
public InputStream toStream()
```


Возвращает исходный поток изображений.

**Возвращает:**
java.io.InputStream — исходный поток изображений.
### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление свойств объекта XImage.

**Возвращает:**
java.lang.String — экземпляр строки
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
