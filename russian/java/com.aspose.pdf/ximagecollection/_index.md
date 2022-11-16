---
title: XImageCollection
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий коллекцию XImage.
type: docs
weight: 410
url: /ru/java/com.aspose.pdf/ximagecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class XImageCollection implements Iterable<XImage>
```

Класс, представляющий коллекцию XImage.
## Методы

| Метод | Описание |
| --- | --- |
| [add(XImage image)](#add-com.aspose.pdf.XImage-) | Добавляет новое изображение в список изображений. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage-) | Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу. |
| [add(InputStream image)](#add-java.io.InputStream-) | Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу. |
| [add(InputStream image, int quality)](#add-java.io.InputStream-int-) | Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу. |
| [addWithImageFilterType(InputStream image, int filterType)](#addWithImageFilterType-java.io.InputStream-int-) | Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(XImage item)](#contains-com.aspose.pdf.XImage-) | Определяет, содержит ли коллекция определенное значение. |
| [copyTo(XImage[] array, int index)](#copyTo-com.aspose.pdf.XImage---int-) | Копирует массив изображений в коллекцию. |
| [delete()](#delete--) | Удаляет изображения из коллекции. |
| [delete(int index)](#delete-int-) | Удаляет индекс из коллекции по индексу. |
| [delete(int index, int action)](#delete-int-int-) | Удаляет индекс из коллекции по индексу, выполняющему действие, указанное параметром действия. |
| [delete(String name)](#delete-java.lang.String-) | Удаляет элемент из коллекции по имени. |
| [delete(String name, int action)](#delete-java.lang.String-int-) | Удаляет элемент из коллекции по имени. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImageName(XImage image)](#getImageName-com.aspose.pdf.XImage-) | Возвращает имя в списке изображений, которое является ключом данного изображения. |
| [getNames()](#getNames--) | Получает массив имен изображений. |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [get_Item(int index)](#get-Item-int-) | Получает изображение из коллекции по его индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает изображение из коллекции по его имени. |
| [hasImage(String imgName)](#hasImage-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает true, если объект синхронизирован. |
| [iterator()](#iterator--) | Возвращает перечислитель коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XImage item)](#remove-com.aspose.pdf.XImage-) | Пока не поддерживается, выдает исключение. |
| [replace(int index, InputStream stream)](#replace-int-java.io.InputStream-) | Заменить изображение в коллекции другим изображением. |
| [replace(int index, InputStream stream, int quality)](#replace-int-java.io.InputStream-int-) | Заменить изображение в коллекции другим изображением. |
| [replace(int index, InputStream stream, int quality, boolean isBlackAndWhite)](#replace-int-java.io.InputStream-int-boolean-) | Заменить изображение в коллекции другим изображением. |
| [size()](#size--) | Количество изображений в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(XImage image) {#add-com.aspose.pdf.XImage-}
```
public String add(XImage image)
```


Добавляет новое изображение в список изображений. Этот метод добавляет изображение как ссылку на тот же PdfObject (что позволяет уменьшить размер файла).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | XImage, который нужно добавить. |

**Возвращает:**
java.lang.String — Имя добавляемого изображения.
### add(BufferedImage image) {#add-java.awt.image.BufferedImage-}
```
public String add(BufferedImage image)
```


Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | BufferedImage, содержащий данные изображения. |

**Возвращает:**
java.lang.String — Имя добавляемого изображения.
### add(InputStream image) {#add-java.io.InputStream-}
```
public String add(InputStream image)
```


Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Поток, содержащий данные изображения (в формате JPEG). |

**Возвращает:**
java.lang.String — Имя добавляемого изображения.
### add(InputStream image, int quality) {#add-java.io.InputStream-int-}
```
public String add(InputStream image, int quality)
```


Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | int | Качество JPEG. |

**Возвращает:**
java.lang.String — Имя добавляемого изображения.
### addWithImageFilterType(InputStream image, int filterType) {#addWithImageFilterType-java.io.InputStream-int-}
```
public String addWithImageFilterType(InputStream image, int filterType)
```


Добавляет объект в конец коллекции, чтобы объект был доступен по последнему индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Поток, содержащий данные изображения. |
| filterType | int | Тип фильтра изображения. |

**Возвращает:**
java.lang.String — Имя добавляемого изображения.
### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### contains(XImage item) {#contains-com.aspose.pdf.XImage-}
```
public boolean contains(XImage item)
```


Определяет, содержит ли коллекция определенное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [XImage](../../com.aspose.pdf/ximage) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - true, если элемент найден в коллекции; в противном случае ложно.
### copyTo(XImage[] array, int index) {#copyTo-com.aspose.pdf.XImage---int-}
```
public void copyTo(XImage[] array, int index)
```


Копирует массив изображений в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [XImage\[\]](../../com.aspose.pdf/ximage) | Массив для копирования. |
| index | int | Индекс, куда изображения будут скопированы в коллекцию. |

### delete() {#delete--}
```
public void delete()
```


Удаляет изображения из коллекции.

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удаляет индекс из коллекции по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс изображения. |

### delete(int index, int action) {#delete-int-int-}
```
public final void delete(int index, int action)
```


Удаляет индекс из коллекции по индексу, выполняющему действие, указанное параметром действия.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс удаляемого изображения. |
| action | int | Элемент ImageDeleteAction. Действие, выполняемое после удаления изображения. |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Удаляет элемент из коллекции по имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя изображения, которое необходимо удалить. |

### delete(String name, int action) {#delete-java.lang.String-int-}
```
public final void delete(String name, int action)
```


Удаляет элемент из коллекции по имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя изображения, которое необходимо удалить. |
| action | int | Действие, которое необходимо выполнить с объектом изображения. |

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
### getImageName(XImage image) {#getImageName-com.aspose.pdf.XImage-}
```
public String getImageName(XImage image)
```


Возвращает имя в списке изображений, которое является ключом данного изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | Изображение для поиска. |

**Возвращает:**
java.lang.String — Имя (ключ) найденного изображения; null, если изображения не найдены.
### getNames() {#getNames--}
```
public String[] getNames()
```


Получает массив имен изображений.

**Возвращает:**
java.lang.String[] - Нить[] множество
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Возвращает объект синхронизации.

**Возвращает:**
java.lang.Object — элемент объекта
### get_Item(int index) {#get-Item-int-}
```
public XImage get_Item(int index)
```


Получает изображение из коллекции по его индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс изображения |

**Возвращает:**
[XImage](../../com.aspose.pdf/ximage) - Полученное изображение.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public XImage get_Item(String name)
```


Получает изображение из коллекции по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя изображения. |

**Возвращает:**
[XImage](../../com.aspose.pdf/ximage) - Полученное изображение.
### hasImage(String imgName) {#hasImage-java.lang.String-}
```
public boolean hasImage(String imgName)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imgName | java.lang.String |  |

**Возвращает:**
логический
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает true, если объект синхронизирован.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<XImage> iterator()
```


Возвращает перечислитель коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.XImage> — перечислитель коллекции
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XImage item) {#remove-com.aspose.pdf.XImage-}
```
public boolean remove(XImage item)
```


Пока не поддерживается, выдает исключение.

Всегда выдает NotImplementedException

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [XImage](../../com.aspose.pdf/ximage) | Экземпляр XImage Элемент для удаления. |

**Возвращает:**
boolean - логическое значение
### replace(int index, InputStream stream) {#replace-int-java.io.InputStream-}
```
public void replace(int index, InputStream stream)
```


Заменить изображение в коллекции другим изображением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента коллекции, который будет заменен. |
| stream | java.io.InputStream | Поток, содержащий данные изображения (в формате JPEG). |

### replace(int index, InputStream stream, int quality) {#replace-int-java.io.InputStream-int-}
```
public void replace(int index, InputStream stream, int quality)
```


Заменить изображение в коллекции другим изображением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента коллекции, который будет заменен. |
| stream | java.io.InputStream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | int | Качество JPEG. |

### replace(int index, InputStream stream, int quality, boolean isBlackAndWhite) {#replace-int-java.io.InputStream-int-boolean-}
```
public final void replace(int index, InputStream stream, int quality, boolean isBlackAndWhite)
```


Заменить изображение в коллекции другим изображением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента коллекции, который будет заменен. |
| stream | java.io.InputStream | Поток, содержащий данные изображения (в формате JPEG). |
| quality | int | Качество сжатия JPEG, в процентах (допустимые значения: 0..100). |
| isBlackAndWhite | boolean | Если true, изображение сжимается методом сжатия CCITT, который обеспечивает лучшее сжатие черно-белого изображения. Может использоваться только для черно-белых изображений. |

### size() {#size--}
```
public int size()
```


Количество изображений в коллекции.

**Возвращает:**
интервал - целочисленное значение
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
