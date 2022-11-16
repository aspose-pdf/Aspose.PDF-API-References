---
title: JpegDevice
second_title: Aspose.PDF для справки по Java API
description: Представляет устройство изображения, которое помогает сохранять страницы PDF-документа в формате jpeg.
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.devices/jpegdevice/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class JpegDevice extends ImageDevice
```

Представляет устройство изображения, которое помогает сохранять страницы PDF-документа в формате jpeg.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegDevice()](#JpegDevice--) | Инициализирует новый экземпляр класса JpegDevice с разрешением по умолчанию и максимальным качеством. |
| [JpegDevice(Resolution resolution)](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса JpegDevice. |
| [JpegDevice(int quality)](#JpegDevice-int-) | Инициализирует новый экземпляр класса JpegDevice. |
| [JpegDevice(Resolution resolution, int quality)](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Инициализирует новый экземпляр класса JpegDevice. |
| [JpegDevice(int width, int height)](#JpegDevice-int-int-) | Инициализирует новый экземпляр класса JpegDevice с заданными размерами изображения, разрешением по умолчанию (=150) и максимальным качеством. |
| [JpegDevice(PageSize pageSize)](#JpegDevice-com.aspose.pdf.PageSize-) | Инициализирует новый экземпляр класса JpegDevice с заданным размером страницы, разрешением по умолчанию (=150) и максимальным качеством. |
| [JpegDevice(int width, int height, Resolution resolution)](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса JpegDevice с заданными размерами изображения, разрешением и максимальным качеством. |
| [JpegDevice(PageSize pageSize, Resolution resolution)](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса JpegDevice с заданным размером страницы, разрешением и максимальным качеством. |
| [JpegDevice(int width, int height, Resolution resolution, int quality)](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Инициализирует новый экземпляр класса JpegDevice с заданными размерами, разрешением и качеством изображения. |
| [JpegDevice(PageSize pageSize, Resolution resolution, int quality)](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Инициализирует новый экземпляр класса JpegDevice с указанным размером страницы, разрешением и качеством. |
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
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Преобразует страницу в jpeg и сохраняет ее в выходном потоке. |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | Выполняет некоторую операцию на данной странице и сохраняет результаты в файл. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Преобразует страницу в jpeg и сохраняет ее в выходном потоке. |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Устанавливает тип координат страницы (поля Media/Crop). |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Установите прямоугольник, определяющий область, которая будет преобразована в изображение. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Устанавливает режим представления формы. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Устанавливает параметры рендеринга. |
| [setShadingPerformanceHigh(boolean value)](#setShadingPerformanceHigh-boolean-) | Устанавливает высокую производительность процессов затенения или нет. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegDevice() {#JpegDevice--}
```
public JpegDevice()
```


Инициализирует новый экземпляр класса JpegDevice с разрешением по умолчанию и максимальным качеством.

### JpegDevice(Resolution resolution) {#JpegDevice-com.aspose.pdf.devices.Resolution-}
```
public JpegDevice(Resolution resolution)
```


Инициализирует новый экземпляр класса JpegDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |

### JpegDevice(int quality) {#JpegDevice-int-}
```
public JpegDevice(int quality)
```


Инициализирует новый экземпляр класса JpegDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| quality | int | Задает уровень сжатия изображения. Диапазон полезных значений качества — от 0 до 100. Чем меньше указанное число, тем выше степень сжатия и, следовательно, ниже качество изображения. Ноль даст вам изображение самого низкого качества, а 100 — самое высокое. |

### JpegDevice(Resolution resolution, int quality) {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
```
public JpegDevice(Resolution resolution, int quality)
```


Инициализирует новый экземпляр класса JpegDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |
| quality | int | Задает уровень сжатия изображения. Диапазон полезных значений качества — от 0 до 100. Чем меньше указанное число, тем выше степень сжатия и, следовательно, ниже качество изображения. Ноль даст вам изображение самого низкого качества, а 100 — самое высокое. |

### JpegDevice(int width, int height) {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```


Инициализирует новый экземпляр класса JpegDevice с заданными размерами изображения, разрешением по умолчанию (=150) и максимальным качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |

### JpegDevice(PageSize pageSize) {#JpegDevice-com.aspose.pdf.PageSize-}
```
public JpegDevice(PageSize pageSize)
```


Инициализирует новый экземпляр класса JpegDevice с заданным размером страницы, разрешением по умолчанию (=150) и максимальным качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |

### JpegDevice(int width, int height, Resolution resolution) {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public JpegDevice(int width, int height, Resolution resolution)
```


Инициализирует новый экземпляр класса JpegDevice с заданными размерами изображения, разрешением и максимальным качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |

### JpegDevice(PageSize pageSize, Resolution resolution) {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public JpegDevice(PageSize pageSize, Resolution resolution)
```


Инициализирует новый экземпляр класса JpegDevice с заданным размером страницы, разрешением и максимальным качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |

### JpegDevice(int width, int height, Resolution resolution, int quality) {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
```
public JpegDevice(int width, int height, Resolution resolution, int quality)
```


Инициализирует новый экземпляр класса JpegDevice с заданными размерами, разрешением и качеством изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |
| quality | int | Задает уровень сжатия изображения. Диапазон полезных значений качества — от 0 до 100. Чем меньше указанное число, тем выше степень сжатия и, следовательно, ниже качество изображения. Ноль даст вам изображение самого низкого качества, а 100 — самое высокое. |

### JpegDevice(PageSize pageSize, Resolution resolution, int quality) {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
```
public JpegDevice(PageSize pageSize, Resolution resolution, int quality)
```


Инициализирует новый экземпляр класса JpegDevice с указанным размером страницы, разрешением и качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения см. в разделе Класс разрешения. |
| quality | int | Задает уровень сжатия изображения. Диапазон полезных значений качества — от 0 до 100. Чем меньше указанное число, тем выше степень сжатия и, следовательно, ниже качество изображения. Ноль даст вам изображение самого низкого качества, а 100 — самое высокое. |

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


Преобразует страницу в jpeg и сохраняет ее в выходном потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для конвертации. |
| output | java.io.OutputStream | Выходной поток с изображением в формате jpeg. |

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


Преобразует страницу в jpeg и сохраняет ее в выходном потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для конвертации. |
| output | com.aspose.ms.System.IO.Stream | Выходной поток с изображением в формате jpeg. |

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
