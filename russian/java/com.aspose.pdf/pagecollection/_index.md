---
title: PageCollection
second_title: Aspose.PDF для справки по Java API
description: Коллекция страниц PDF-документа.
type: docs
weight: 259
url: /ru/java/com.aspose.pdf/pagecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable, com.aspose.pdf.ISupportsMemoryCleanup
```
public final class PageCollection implements Iterable<Page>, ISupportsMemoryCleanup
```

Коллекция страниц PDF-документа.
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает объект посетителя AnnotationSelector, предоставляющий функциональные возможности для работы с аннотациями. |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Принимает объект посетителя ImagePlacementAbsorber, предоставляющий функциональные возможности для работы с объектами размещения изображения. |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | Принимает объект посетителя TextAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами. |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Принимает объект посетителя TextFragmentAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами. |
| [add()](#add--) | Добавляет пустую страницу |
| [add(Page entity)](#add-com.aspose.pdf.Page-) | Добавляет страницу в коллекцию. |
| [add(Page[] pages)](#add-com.aspose.pdf.Page---) | Добавляет в коллекцию все страницы из массива. |
| [add(Iterable<Page> pages)](#add-java.lang.Iterable-com.aspose.pdf.Page--) | Добавляет в коллекцию все страницы из списка. |
| [add(List<Page> pages)](#add-java.util.List-com.aspose.pdf.Page--) | Добавляет в коллекцию все страницы из списка. |
| [add_Rename_Namesake(Page entity)](#add-Rename-Namesake-com.aspose.pdf.Page-) | Добавляет страницу в коллекцию. |
| [clear()](#clear--) | Очистить коллекцию страниц. |
| [contains(Page item)](#contains-com.aspose.pdf.Page-) | Определяет, содержит ли этот экземпляр объект. |
| [copyTo(Page[] array, int index)](#copyTo-com.aspose.pdf.Page---int-) | Копирует страницы в документ. |
| [delete()](#delete--) | Удаляет все страницы из коллекции. |
| [delete(int index)](#delete-int-) | Удалить указанную страницу. |
| [delete(Integer[] pages)](#delete-java.lang.Integer---) | Удалить указанные страницы, номера которых указаны в массиве. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByPdfObject(IPdfObject pdfObject)](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten()](#flatten--) | Удаляет все поля, расположенные на страницах, и ставит вместо них их значения. |
| [freeMemory()](#freeMemory--) | Очищает кэшированные данные |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект синхронизации коллекции. |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Возвращает страницу по ее индексу. |
| [get_Item(int index)](#get-Item-int-) | Получает страницу по индексу. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Page entity)](#indexOf-com.aspose.pdf.Page-) | Возвращает индекс указанной страницы. |
| [insert(int pageNumber)](#insert-int-) | Вставить пустой файл apge в коллекцию в указанной позиции. |
| [insert(int pageNumber, Page entity)](#insert-int-com.aspose.pdf.Page-) | Вставляет страницу в коллекцию страниц в указанном месте. |
| [insert(int pageNumber, Page[] pages)](#insert-int-com.aspose.pdf.Page---) | Вставляет страницы массива в документ. |
| [insert(int pageNumber, Iterable<Page> pages)](#insert-int-java.lang.Iterable-com.aspose.pdf.Page--) | Вставляет страницы из коллекции в документ. |
| [insert(int pageNumber, List<Page> pages)](#insert-int-java.util.List-com.aspose.pdf.Page--) | Вставляет страницы из коллекции в документ. |
| [isEmpty()](#isEmpty--) | Возвращает TRUE, если коллекция пуста. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, что коллекция доступна только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает истину о том, что объект синхронизирован. |
| [iterator()](#iterator--) | Возвращает перечислитель страниц. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Page item)](#remove-com.aspose.pdf.Page-) | Удаляет указанный элемент, выдает исключение. |
| [size()](#size--) | Получает количество страниц в документе. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Принимает объект посетителя AnnotationSelector, предоставляющий функциональные возможности для работы с аннотациями.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Посетитель селектора аннотаций |

### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


Принимает объект посетителя ImagePlacementAbsorber, предоставляющий функциональные возможности для работы с объектами размещения изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) | Объект размещения изображения. |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


Принимает объект посетителя TextAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) | Объект поглотителя текста. |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


Принимает объект посетителя TextFragmentAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) | Объект поглотителя фрагментов текста. |

### add() {#add--}
```
public Page add()
```


Добавляет пустую страницу

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Добавлена страница.
### add(Page entity) {#add-com.aspose.pdf.Page-}
```
public Page add(Page entity)
```


Добавляет страницу в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | Страница, которую необходимо добавить. |

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Добавлена страница.
### add(Page[] pages) {#add-com.aspose.pdf.Page---}
```
public void add(Page[] pages)
```


Добавляет в коллекцию все страницы из массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pages | [Page\[\]](../../com.aspose.pdf/page) | Массив страниц, которые будут добавлены. |

### add(Iterable<Page> pages) {#add-java.lang.Iterable-com.aspose.pdf.Page--}
```
public void add(Iterable<Page> pages)
```


Добавляет в коллекцию все страницы из списка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pages | java.lang.Iterable<com.aspose.pdf.Page> | Список, содержащий все страницы, которые необходимо добавить. |

### add(List<Page> pages) {#add-java.util.List-com.aspose.pdf.Page--}
```
public void add(List<Page> pages)
```


Добавляет в коллекцию все страницы из списка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pages | java.util.List<com.aspose.pdf.Page> | Список, содержащий все страницы, которые необходимо добавить. |

### add_Rename_Namesake(Page entity) {#add-Rename-Namesake-com.aspose.pdf.Page-}
```
public void add_Rename_Namesake(Page entity)
```


Добавляет страницу в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | Страница, которую необходимо добавить. |

### clear() {#clear--}
```
public void clear()
```


Очистить коллекцию страниц.

### contains(Page item) {#contains-com.aspose.pdf.Page-}
```
public boolean contains(Page item)
```


Определяет, содержит ли этот экземпляр объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Page](../../com.aspose.pdf/page) | Экземпляр страницы |

**Возвращает:**
 boolean - логическое значение истинно, если[ содержит][указанный пункт]; в противном случае ложь.
### copyTo(Page[] array, int index) {#copyTo-com.aspose.pdf.Page---int-}
```
public void copyTo(Page[] array, int index)
```


Копирует страницы в документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [Page\[\]](../../com.aspose.pdf/page) | Массив, содержащий объект Pages для вставки в документ. Это должен быть объект[] или Страница[]. |
| index | int | Начальный индекс, в который будут вставлены страницы |

### delete() {#delete--}
```
public void delete()
```


Удаляет все страницы из коллекции.

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удалить указанную страницу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Номер страницы, которая будет удалена. Номера страниц начинаются с 1. |

### delete(Integer[] pages) {#delete-java.lang.Integer---}
```
public void delete(Integer[] pages)
```


Удалить указанные страницы, номера которых указаны в массиве.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pages | java.lang.Integer[] | Массив удаляемых страниц. |

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
### findByPdfObject(IPdfObject pdfObject) {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}
```
public final Page findByPdfObject(IPdfObject pdfObject)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfObject | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

**Возвращает:**
[Page](../../com.aspose.pdf/page)
### flatten() {#flatten--}
```
public void flatten()
```


Удаляет все поля, расположенные на страницах, и ставит вместо них их значения.

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Очищает кэшированные данные

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект синхронизации коллекции.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```


Возвращает страницу по ее индексу. Страница 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс запрашиваемой страницы. Страницы нумеруются с 1. |

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Запрашиваемая страница
### get_Item(int index) {#get-Item-int-}
```
public Page get_Item(int index)
```


Получает страницу по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс страницы. |

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Восстановленная страница.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### indexOf(Page entity) {#indexOf-com.aspose.pdf.Page-}
```
public int indexOf(Page entity)
```


Возвращает индекс указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | Объект страницы. Номера страниц начинаются с 1.

--------------------

 Номера страниц начинаются с 1. Возвращает 0, если в коллекции нет страницы.|

**Возвращает:**
int — индекс страницы в коллекции.
### insert(int pageNumber) {#insert-int-}
```
public Page insert(int pageNumber)
```


Вставить пустой файл apge в коллекцию в указанной позиции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Позиция новой страницы. |

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Вставленная страница.
### insert(int pageNumber, Page entity) {#insert-int-com.aspose.pdf.Page-}
```
public Page insert(int pageNumber, Page entity)
```


Вставляет страницу в коллекцию страниц в указанном месте.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Обязательный индекс страницы в коллекции. |
| entity | [Page](../../com.aspose.pdf/page) | Страница для вставки. |

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Вставленная страница.
### insert(int pageNumber, Page[] pages) {#insert-int-com.aspose.pdf.Page---}
```
public void insert(int pageNumber, Page[] pages)
```


Вставляет страницы массива в документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Начальный номер новых страниц. |
| pages | [Page\[\]](../../com.aspose.pdf/page) | Массив страниц, которые будут вставлены. |

### insert(int pageNumber, Iterable<Page> pages) {#insert-int-java.lang.Iterable-com.aspose.pdf.Page--}
```
public void insert(int pageNumber, Iterable<Page> pages)
```


Вставляет страницы из коллекции в документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Начальная позиция новых страниц. |
| pages | java.lang.Iterable<com.aspose.pdf.Page> | Коллекция страниц. |

### insert(int pageNumber, List<Page> pages) {#insert-int-java.util.List-com.aspose.pdf.Page--}
```
public void insert(int pageNumber, List<Page> pages)
```


Вставляет страницы из коллекции в документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Начальная позиция новых страниц. |
| pages | java.util.List<com.aspose.pdf.Page> | Коллекция страниц. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает TRUE, если коллекция пуста.

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, что коллекция доступна только для чтения. Всегда возвращает ложь.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает истину о том, что объект синхронизирован.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<Page> iterator()
```


Возвращает перечислитель страниц.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.Page> — Перечислитель страниц
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Page item) {#remove-com.aspose.pdf.Page-}
```
public boolean remove(Page item)
```


Удаляет указанный элемент, выдает исключение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Page](../../com.aspose.pdf/page) | Экземпляр страницы |

**Возвращает:**
boolean - логическое значение
### size() {#size--}
```
public int size()
```


Получает количество страниц в документе.

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
