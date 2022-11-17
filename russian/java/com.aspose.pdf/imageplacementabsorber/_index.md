---
title: ImagePlacementAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель объектов размещения изображения.
type: docs
weight: 172
url: /ru/java/com.aspose.pdf/imageplacementabsorber/
---
**Наследование:**
java.lang.Object
```
public final class ImagePlacementAbsorber
```

Представляет объект-поглотитель объектов размещения изображения. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска через коллекцию ImagePlacementAbsorber.ImagePlacements.

--------------------

```
The example demonstrates how to find images on the first PDF document page and get the image placement properties.


 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Создайте объект ImagePlacementAbsorber для выполнения поиска размещения изображения
 ImagePlacementAbsorber abs = new ImagePlacementAbsorber();
 // Принять поглотитель для первой страницы
 doc.getPages().get_Item(1).accept(abs);
 // Показать свойства размещения изображений для всех мест размещения
 for (ImagePlacement imagePlacement : ```
(Iterable)
```abs.getImagePlacements())
 {
     System.out.println("image width:" + imagePlacement.getRectangle().getWidth());
     System.out.println("image height:" + imagePlacement.getRectangle().getHeight());
     System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX());
     System.out.println("image LLY:" + imagePlacement.getRectangle.getY());
     System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX());
     System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY());
 }
```

--------------------

Объект ImagePlacementAbsorber в основном используется в сценарии поиска изображений. По завершении поиска вхождения представляются объектами ImagePlacement, которые содержит коллекция ImagePlacementAbsorber.ImagePlacements. Объект ImagePlacement предоставляет доступ к свойствам размещения изображения: размерам, разрешению и т. д.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImagePlacementAbsorber()](#ImagePlacementAbsorber--) | Инициализирует новый экземпляр объекта ImagePlacementAbsorber. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImagePlacements()](#getImagePlacements--) | Получает коллекцию вхождений размещения изображений, представленных объектами ImagePlacement. |
| [hashCode()](#hashCode--) |  |
| [isReadOnlyMode()](#isReadOnlyMode--) | Получает/устанавливает режим только для чтения для коллекции операций синтаксического анализа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Получает/устанавливает режим только для чтения для коллекции операций синтаксического анализа. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Выполняет поиск по указанному документу. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Выполняет поиск на указанной странице. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImagePlacementAbsorber() {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```


Инициализирует новый экземпляр объекта ImagePlacementAbsorber.

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
### getImagePlacements() {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```


Получает коллекцию вхождений размещения изображений, представленных объектами ImagePlacement.

**Возвращает:**
[ImagePlacementCollection](../../com.aspose.pdf/imageplacementcollection) - Объект ImagePlacementCollection
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReadOnlyMode() {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```


Получает/устанавливает режим только для чтения для коллекции операций синтаксического анализа. Это может помочь против исключений из памяти.

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




### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Получает/устанавливает режим только для чтения для коллекции операций синтаксического анализа. Это может помочь против исключений из памяти.

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
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Выполняет поиск по указанному документу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | Pdf объект документа. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Выполняет поиск на указанной странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа Pdf. |

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
