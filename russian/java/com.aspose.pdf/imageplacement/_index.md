---
title: ImagePlacement
second_title: Aspose.PDF для справки по Java API
description: Представляет характеристики изображения, размещенного на странице документа Pdf.
type: docs
weight: 171
url: /ru/java/com.aspose.pdf/imageplacement/
---
**Наследование:**
java.lang.Object
```
public final class ImagePlacement
```

Представляет характеристики изображения, размещенного на странице документа Pdf.

--------------------

```
The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions.
 
  
 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create ImagePlacementAbsorber object to perform image placement search
 ImagePlacementAbsorber abs = new ImagePlacementAbsorber();
 // Accept the absorber for first page
 doc.getPages().get_Item(1).accept(abs);
 // Retrieve images with visible dimensions
 for (ImagePlacement imagePlacement : ```
(Iterable)
```abs.getImagePlacements())
 {
     BufferedImage scaledImage;
     ByteArrayOutputStream imageStream = new ByteArrayOutputStream())
     
         // Retrieve image from resources
         imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png);
         BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream);
         // Create new bitmap with actual dimensions
         scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight());
     
 }
```

--------------------

Когда изображение помещается на страницу, оно может иметь размеры, отличные от физических размеров, определенных в Ресурсах. Объект ImagePlacement предназначен для предоставления такой информации, как размеры, разрешение и так далее.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingParameters()](#getCompositingParameters--) | Получает параметры компоновки графического состояния, активного для изображения, размещенного на странице. |
| [getImage()](#getImage--) | Получает связанный объект ресурса XImage. |
| [getMatrix()](#getMatrix--) | Текущая матрица преобразования для этого изображения. |
| [getOperator()](#getOperator--) | Оператор, используемый для отображения изображения. |
| [getPage()](#getPage--) | Получает страницу, содержащую изображение. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник изображения. |
| [getResolution()](#getResolution--) | Получает разрешение изображения. |
| [getRotation()](#getRotation--) | Получает угол поворота изображения. |
| [hashCode()](#hashCode--) |  |
| [hide()](#hide--) | Удалить изображение со страницы. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [replace(InputStream image)](#replace-java.io.InputStream-) | Заменить изображение в коллекции другим изображением. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Сохраняет изображение с соответствующими преобразованиями: масштабированием, поворотом и разрешением. |
| [save(OutputStream outputStream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Сохраняет изображение с соответствующими преобразованиями: масштабированием, поворотом и разрешением. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCompositingParameters() {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```


Получает параметры компоновки графического состояния, активного для изображения, размещенного на странице.

**Возвращает:**
[CompositingParameters](../../com.aspose.pdf/compositingparameters) - Объект CompositingParameters
### getImage() {#getImage--}
```
public XImage getImage()
```


Получает связанный объект ресурса XImage.

**Возвращает:**
[XImage](../../com.aspose.pdf/ximage) - XImage объект
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


Текущая матрица преобразования для этого изображения.

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Матрица объекта
### getOperator() {#getOperator--}
```
public final Operator getOperator()
```


Оператор, используемый для отображения изображения.

**Возвращает:**
[Operator](../../com.aspose.pdf/operator) - Экземпляр оператора
### getPage() {#getPage--}
```
public Page getPage()
```


Получает страницу, содержащую изображение.

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Объект страницы
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник изображения.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Получает разрешение изображения.

**Возвращает:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Объект разрешения
### getRotation() {#getRotation--}
```
public float getRotation()
```


Получает угол поворота изображения.

**Возвращает:**
число с плавающей запятой
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### hide() {#hide--}
```
public final void hide()
```


Удалить изображение со страницы.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### replace(InputStream image) {#replace-java.io.InputStream-}
```
public void replace(InputStream image)
```


Заменить изображение в коллекции другим изображением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Поток, содержащий данные изображения. |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Сохраняет изображение с соответствующими преобразованиями: масштабированием, поворотом и разрешением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток, где изображение будет сохранено |

### save(OutputStream outputStream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream outputStream, ImageType format)
```


Сохраняет изображение с соответствующими преобразованиями: масштабированием, поворотом и разрешением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток, где изображение будет сохранено |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат, который будет использоваться для кодирования изображения. Формат изображения  |

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
