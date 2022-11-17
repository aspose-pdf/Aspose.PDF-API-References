---
title: TiffDevice
second_title: Aspose.PDF для справки по Java API
description: Этот класс помогает сохранять PDF-документ страницу за страницей в одно изображение в формате TIFF.
type: docs
weight: 28
url: /ru/java/com.aspose.pdf.devices/tiffdevice/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.DocumentDevice](../../com.aspose.pdf.devices/documentdevice)
```
public final class TiffDevice extends DocumentDevice
```

Этот класс помогает сохранять PDF-документ страницу за страницей в одно изображение в формате TIFF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffDevice(Resolution resolution)](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(TiffSettings settings)](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice()](#TiffDevice--) | Инициализирует новый экземпляр класса TiffDevice с настройками по умолчанию. |
| [TiffDevice(int width, int height, Resolution resolution, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(int width, int height, Resolution resolution)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(PageSize pageSize, Resolution resolution)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(int width, int height, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(PageSize pageSize, TiffSettings settings)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(int width, int height)](#TiffDevice-int-int-) | Инициализирует новый экземпляр класса TiffDevice. |
| [TiffDevice(PageSize pageSize)](#TiffDevice-com.aspose.pdf.PageSize-) | Инициализирует новый экземпляр класса TiffDevice. |
## Методы

| Метод | Описание |
| --- | --- |
| [binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Выполните бинаризацию Брэдли для входного потока. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCropRectangle()](#getCropRectangle--) | Получите прямоугольник, определяющий область, которая будет преобразована в изображение. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Получает режим представления формы. |
| [getHeight()](#getHeight--) | Получает высоту вывода изображения. |
| [getRenderingOptions()](#getRenderingOptions--) | Получает параметры рендеринга. |
| [getResolution()](#getResolution--) | Получает разрешение изображения. |
| [getSettings()](#getSettings--) | Получает настройки для преобразования pdf в изображение tiff. |
| [getWidth()](#getWidth--) | Получает ширину вывода изображения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Преобразует определенные страницы документа в формат tiff и сохраняет его в выходном потоке. |
| [process(IDocument document, int fromPage, int toPage, String outputFileName)](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Обрабатывает определенные страницы документа и сохраняет результаты в файл. |
| [process(IDocument document, OutputStream output)](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [process(IDocument document, String outputFileName)](#process-com.aspose.pdf.IDocument-java.lang.String-) | Обрабатывает весь документ и сохраняет результаты в файл. |
| [processInternal(IDocument document, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Преобразует определенные страницы документа в формат tiff и сохраняет его в выходном потоке. |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Установите прямоугольник, определяющий область, которая будет преобразована в изображение. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Получает режим представления формы. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Устанавливает параметры рендеринга. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffDevice(Resolution resolution) {#TiffDevice-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(Resolution resolution)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение результирующего файла изображения. |

### TiffDevice(Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(Resolution resolution, TiffSettings settings)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |

### TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### TiffDevice(TiffSettings settings) {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(TiffSettings settings)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |

### TiffDevice(TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(TiffSettings settings, IIndexBitmapConverter converter)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### TiffDevice() {#TiffDevice--}
```
public TiffDevice()
```


Инициализирует новый экземпляр класса TiffDevice с настройками по умолчанию.

### TiffDevice(int width, int height, Resolution resolution, TiffSettings settings) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(int width, int height, Resolution resolution, TiffSettings settings)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |

### TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### TiffDevice(int width, int height, Resolution resolution) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(int width, int height, Resolution resolution)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |

### TiffDevice(PageSize pageSize, Resolution resolution) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(PageSize pageSize, Resolution resolution)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение выходного изображения. |

### TiffDevice(int width, int height, TiffSettings settings) {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(int width, int height, TiffSettings settings)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |

### TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### TiffDevice(PageSize pageSize, TiffSettings settings) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки Tiff см. в классе TiffSettings. |

### TiffDevice(int width, int height) {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина вывода изображения. |
| height | int | Высота вывода изображения. |

### TiffDevice(PageSize pageSize) {#TiffDevice-com.aspose.pdf.PageSize-}
```
public TiffDevice(PageSize pageSize)
```


Инициализирует новый экземпляр класса TiffDevice.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного изображения. |

### binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold) {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
```
public void binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)
```


Выполните бинаризацию Брэдли для входного потока.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImageStream | java.io.InputStream | Входной поток изображений. |
| outputImageStream | java.io.OutputStream | Выходной поток изображения. |
| threshold | double | Пороговое значение от 0,0 до 1,0. |

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
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


Получите прямоугольник, определяющий область, которая будет преобразована в изображение. Значение по умолчанию — null, и в этом случае все изображение преобразуется в страницу.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Получает режим представления формы.

**Возвращает:**
int - значение FormPresentationMode
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
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - варианты рендеринга.
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Получает разрешение изображения.

**Возвращает:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Элемент разрешения
### getSettings() {#getSettings--}
```
public TiffSettings getSettings()
```


Получает настройки для преобразования pdf в изображение tiff.

**Возвращает:**
[TiffSettings](../../com.aspose.pdf.devices/tiffsettings) - Элемент TiffSettings
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```


Преобразует определенные страницы документа в формат tiff и сохраняет его в выходном потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для преобразования. |
| fromPage | int | Определяет номер страницы, с которой начнется конвертация. |
| toPage | int | Определяет номер страницы, на которой завершится конвертация. |
| output | java.io.OutputStream | Выходной поток с изображением в формате tiff. |

### process(IDocument document, int fromPage, int toPage, String outputFileName) {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
```
public void process(IDocument document, int fromPage, int toPage, String outputFileName)
```


Обрабатывает определенные страницы документа и сохраняет результаты в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| fromPage | int | Первая страница для начала обработки. |
| toPage | int | Последняя страница обработки. |
| outputFileName | java.lang.String | Определяет файл, в котором хранятся результаты обработки. |

### process(IDocument document, OutputStream output) {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public void process(IDocument document, OutputStream output)
```


Обрабатывает весь документ и сохраняет результаты в поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| output | java.io.OutputStream | Определяет поток, в котором хранятся результаты обработки. |

### process(IDocument document, String outputFileName) {#process-com.aspose.pdf.IDocument-java.lang.String-}
```
public void process(IDocument document, String outputFileName)
```


Обрабатывает весь документ и сохраняет результаты в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| outputFileName | java.lang.String | Определяет файл, в котором хранятся результаты обработки. |

### processInternal(IDocument document, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, System.IO.Stream output)
```


Обрабатывает весь документ и сохраняет результаты в поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для обработки. |
| output | com.aspose.ms.System.IO.Stream | Определяет поток, в котором хранятся результаты обработки. |

### processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```


Преобразует определенные страницы документа в формат tiff и сохраняет его в выходном потоке.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ для преобразования. |
| fromPage | int | Определяет номер страницы, с которой начнется конвертация. |
| toPage | int | Определяет номер страницы, на которой завершится конвертация. |
| output | com.aspose.ms.System.IO.Stream | Выходной поток с изображением в формате tiff. |

### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


Установите прямоугольник, определяющий область, которая будет преобразована в изображение. Значение по умолчанию — null, и в этом случае все изображение преобразуется в страницу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Получает режим представления формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Устанавливает параметры рендеринга.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | варианты рендеринга. |

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
