---
title: GifDevice
second_title: Aspose.PDF для справки по Java API
description: Представляет устройство изображения, которое помогает сохранять страницы PDF-документа в формате gif.
type: docs
weight: 17
url: /ru/java/com.aspose.pdf.devices/gifdevice/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class GifDevice extends ImageDevice
```

Представляет устройство изображения, которое помогает сохранять страницы PDF-документа в формате gif.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifDevice()](#GifDevice--) | Инициализирует новый экземпляр класса GifDevice с разрешением по умолчанию. |
| [GifDevice(Resolution resolution)](#GifDevice-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса GifDevice. |
| [GifDevice(int width, int height, Resolution resolution)](#GifDevice-int-int-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса GifDevice с заданными размерами и разрешением изображения. |
| [GifDevice(PageSize pageSize, Resolution resolution)](#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса GifDevice с указанным размером и разрешением страницы. |
| [GifDevice(int width, int height)](#GifDevice-int-int-) | Инициализирует новый экземпляр класса GifDevice с предоставленными размерами изображения и разрешением по умолчанию (=150). |
| [GifDevice(PageSize pageSize)](#GifDevice-com.aspose.pdf.PageSize-) | Инициализирует новый экземпляр класса GifDevice с заданным размером страницы и разрешением по умолчанию (=150). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | Получает тип координат страницы (поля мультимедиа/обрезки). |
| [getCropRectangle()](#getCropRectangle--) | Получите прямоугольник, определяющий область, которая будет преобразована в изображение. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Получает режим представления формы. |
| [getHeight()](#getHeight--) | Получает высоту вывода изображения. |
| [getRenderingOptions()](#getRenderingOptions--) | Получает параметры рендеринга. |
| [getResolution()](#getResolution--) | Получает разрешение изображения. |
| [getWidth()](#getWidth--) | Получает ширину вывода изображения. |
| [hashCode()](#hashCode--) |  |
| [isShadingPerformanceHigh()](#isShadingPerformanceHigh--) | Является ли производительность процессов затенения высокой. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | Отрисовывает страницу на графике |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Преобразует страницу в gif и сохраняет ее в выходном потоке. |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | Выполняет некоторую операцию на данной странице и сохраняет результаты в файл. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Преобразует страницу в gif и сохраняет ее в выходном потоке. |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Устанавливает тип координат страницы (поля Media/Crop). |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Установите прямоугольник, определяющий область, которая будет преобразована в изображение. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Устанавливает режим представления формы. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Устанавливает параметры рендеринга. |
| [setShadingPerformanceHigh(boolean value)](#setShadingPerformanceHigh-boolean-) | Устанавливает высокую производительность процессов затенения или нет. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifDevice() {#GifDevice--}
```
public GifDevice()
```


Инициализирует новый экземпляр класса GifDevice с разрешением по умолчанию.

### GifDevice(Resolution resolution) {#GifDevice-com.aspose.pdf.devices.Resolution-}
```
public GifDevice(Resolution resolution)
```


Инициализирует новый экземпляр класса GifDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |

### GifDevice(int width, int height, Resolution resolution) {#GifDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public GifDevice(int width, int height, Resolution resolution)
```


Инициализирует новый экземпляр класса GifDevice с заданными размерами и разрешением изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |

### GifDevice(PageSize pageSize, Resolution resolution) {#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public GifDevice(PageSize pageSize, Resolution resolution)
```


Инициализирует новый экземпляр класса GifDevice с указанным размером и разрешением страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |

### GifDevice(int width, int height) {#GifDevice-int-int-}
```
public GifDevice(int width, int height)
```


Инициализирует новый экземпляр класса GifDevice с предоставленными размерами изображения и разрешением по умолчанию (=150).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |

### GifDevice(PageSize pageSize) {#GifDevice-com.aspose.pdf.PageSize-}
```
public GifDevice(PageSize pageSize)
```


Инициализирует новый экземпляр класса GifDevice с заданным размером страницы и разрешением по умолчанию (=150).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |

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
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Получает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию.

**Возвращает:**
int - элемент PageCoordinateType
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


Получите прямоугольник, определяющий область, которая будет преобразована в изображение. Значение по умолчанию равно null, и в этом случае вся страница преобразуется в изображение.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Получает режим представления формы.

**Возвращает:**
int - элемент FormPresentationMode
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту вывода изображения.

**Возвращает:**
интервал - целочисленное значение
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Получает параметры рендеринга.

**Возвращает:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - Элемент RenderingOptions
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Получает разрешение изображения.

**Возвращает:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Элемент разрешения
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину вывода изображения.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isShadingPerformanceHigh() {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```


Является ли производительность процессов затенения высокой.
По умолчанию верно.

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




### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


Отрисовывает страницу на графике

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |
| gr | com.aspose.ms.System.Drawing.Graphics | внутренний объект |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Преобразует страницу в gif и сохраняет ее в выходном потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для конвертации. |
| output | java.io.OutputStream | Выходной поток с изображением gif. |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}
```
public void process(Page page, String outputFileName)
```


Выполняет некоторую операцию на данной странице и сохраняет результаты в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для обработки. |
| outputFileName | java.lang.String | Этот файл содержит результаты обработки. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Преобразует страницу в gif и сохраняет ее в выходном потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для конвертации. |
| output | com.aspose.ms.System.IO.Stream | Выходной поток с изображением gif. |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Устанавливает тип координат страницы (поля Media/Crop). Значение CropBox используется по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PageCoordinateType |

### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


Установите прямоугольник, определяющий область, которая будет преобразована в изображение. Значение по умолчанию равно null, и в этом случае вся страница преобразуется в изображение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Устанавливает режим представления формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент FormPresentationMode |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Устанавливает параметры рендеринга.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | Элемент RenderingOptions |

### setShadingPerformanceHigh(boolean value) {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```


Устанавливает высокую производительность процессов затенения или нет.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
