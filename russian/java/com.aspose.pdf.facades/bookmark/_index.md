---
title: Bookmark
second_title: Aspose.PDF для справки по Java API
description: Представляет закладку.
type: docs
weight: 14
url: /ru/java/com.aspose.pdf.facades/bookmark/
---
**Наследование:**
java.lang.Object
```
public final class Bookmark
```

Представляет закладку.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Bookmark()](#Bookmark--) | Инициализирует новый экземпляр класса Bookmark. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Получает действие, связанное с закладкой. |
| [getBoldFlag()](#getBoldFlag--) | Получает полужирный флаг заголовка закладки. |
| [getChildItem()](#getChildItem--) | Получает дочерние элементы закладки. |
| [getChildItems()](#getChildItems--) | Получает дочерние элементы закладки. |
| [getClass()](#getClass--) |  |
| [getCustomAcorbatViewerMenuActionName()](#getCustomAcorbatViewerMenuActionName--) | Пока не поддерживается. |
| [getDestination()](#getDestination--) | Получает целевую страницу закладки. |
| [getItalicFlag()](#getItalicFlag--) | Получает курсивный флаг заголовка закладки. |
| [getLevel()](#getLevel--) | Получает уровень иерархии закладки. |
| [getPageDisplay()](#getPageDisplay--) | Получает тип целевой страницы отображаемой закладки. |
| [getPageDisplay_Bottom()](#getPageDisplay-Bottom--) | Получает нижнюю координату отображения страницы. |
| [getPageDisplay_Left()](#getPageDisplay-Left--) | Получает левую координату отображения страницы. |
| [getPageDisplay_Right()](#getPageDisplay-Right--) | Получает правильную координату отображения страницы. |
| [getPageDisplay_Top()](#getPageDisplay-Top--) | Получает верхнюю координату отображения страницы. |
| [getPageDisplay_Zoom()](#getPageDisplay-Zoom--) | Получает коэффициент масштабирования отображения страницы. |
| [getPageNumber()](#getPageNumber--) | Получает номер целевой страницы закладки. |
| [getRemoteFile()](#getRemoteFile--) | Получает файл (путь), необходимый для действия "GoToR" закладки. |
| [getTitle()](#getTitle--) | Получает название закладки. |
| [getTitleColor()](#getTitleColor--) | Получает цвет заголовка закладки. |
| [hashCode()](#hashCode--) |  |
| [isOpen()](#isOpen--) | Получает состояние закладки (открыто, закрыто). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Устанавливает действие, связанное с закладкой. |
| [setBoldFlag(boolean value)](#setBoldFlag-boolean-) | Устанавливает жирный флаг заголовка закладки. |
| [setChildItem(Bookmarks value)](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Устанавливает дочерние закладки. |
| [setChildItems(Bookmarks value)](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Устанавливает дочерние закладки. |
| [setCustomAcorbatViewerMenuActionName(int[] value)](#setCustomAcorbatViewerMenuActionName-int---) | Пока не поддерживается. |
| [setDestination(String value)](#setDestination-java.lang.String-) | Устанавливает целевую страницу закладки. |
| [setItalicFlag(boolean value)](#setItalicFlag-boolean-) | Устанавливает курсивный флаг заголовка закладки. |
| [setLevel(int value)](#setLevel-int-) | Устанавливает уровень иерархии закладок. |
| [setOpen(boolean value)](#setOpen-boolean-) | Устанавливает состояние закладки (открыто, закрыто). |
| [setPageDisplay(String value)](#setPageDisplay-java.lang.String-) | Устанавливает тип целевой страницы отображаемой закладки. |
| [setPageDisplay_Bottom(int value)](#setPageDisplay-Bottom-int-) | Устанавливает нижнюю координату отображения страницы. |
| [setPageDisplay_Left(int value)](#setPageDisplay-Left-int-) | Устанавливает левую координату отображения страницы. |
| [setPageDisplay_Right(int value)](#setPageDisplay-Right-int-) | Устанавливает правую координату отображения страницы. |
| [setPageDisplay_Top(int value)](#setPageDisplay-Top-int-) | Устанавливает верхнюю координату отображения страницы. |
| [setPageDisplay_Zoom(int value)](#setPageDisplay-Zoom-int-) | Устанавливает коэффициент масштабирования отображения страницы. |
| [setPageNumber(int value)](#setPageNumber-int-) | Устанавливает номер целевой страницы закладки. |
| [setRemoteFile(String value)](#setRemoteFile-java.lang.String-) | Устанавливает файл (путь), необходимый для действия "GoToR" закладки. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Устанавливает заголовок закладки. |
| [setTitleColor(Color value)](#setTitleColor-java.awt.Color-) | Устанавливает цвет заголовка закладки. |
| [toOutlineItemCollection(IDocument doc)](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | преобразовать в OutlineItemCollection |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bookmark() {#Bookmark--}
```
public Bookmark()
```


Инициализирует новый экземпляр класса Bookmark.

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
### getAction() {#getAction--}
```
public String getAction()
```


Получает действие, связанное с закладкой. Если PageNumber представлен, действие не может быть указано. Тип действия включает в себя: «Перейти», «Перейти», «Запустить», «Именованное».

**Возвращает:**
java.lang.String — строковое значение
### getBoldFlag() {#getBoldFlag--}
```
public boolean getBoldFlag()
```


Получает полужирный флаг заголовка закладки.

**Возвращает:**
boolean - логическое значение
### getChildItem() {#getChildItem--}
```
public Bookmarks getChildItem()
```


Получает дочерние элементы закладки.

Устарело("Используйте свойство getChildItems() вместо этого".")

**Возвращает:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - Элемент закладок
### getChildItems() {#getChildItems--}
```
public Bookmarks getChildItems()
```


Получает дочерние элементы закладки.

**Возвращает:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) закладка дочерних элементов.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCustomAcorbatViewerMenuActionName() {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```


Пока не поддерживается.

Имя действия, соответствующее выполнению пункта меню в средстве просмотра Acrobat.

**Возвращает:**
инт[] - массив значений int
### getDestination() {#getDestination--}
```
public String getDestination()
```


Получает целевую страницу закладки. Требуется, если действие установлено как "".

**Возвращает:**
java.lang.String — строковое значение
### getItalicFlag() {#getItalicFlag--}
```
public boolean getItalicFlag()
```


Получает курсивный флаг заголовка закладки.

**Возвращает:**
boolean - логическое значение
### getLevel() {#getLevel--}
```
public int getLevel()
```


Получает уровень иерархии закладки.

**Возвращает:**
интервал - целочисленное значение
### getPageDisplay() {#getPageDisplay--}
```
public String getPageDisplay()
```


Получает тип целевой страницы отображаемой закладки.

**Возвращает:**
java.lang.String — строковое значение
### getPageDisplay_Bottom() {#getPageDisplay-Bottom--}
```
public int getPageDisplay_Bottom()
```


Получает нижнюю координату отображения страницы.

**Возвращает:**
интервал - целочисленное значение
### getPageDisplay_Left() {#getPageDisplay-Left--}
```
public int getPageDisplay_Left()
```


Получает левую координату отображения страницы.

**Возвращает:**
интервал - целочисленное значение
### getPageDisplay_Right() {#getPageDisplay-Right--}
```
public int getPageDisplay_Right()
```


Получает правильную координату отображения страницы.

**Возвращает:**
интервал - целочисленное значение
### getPageDisplay_Top() {#getPageDisplay-Top--}
```
public int getPageDisplay_Top()
```


Получает верхнюю координату отображения страницы.

**Возвращает:**
интервал - целочисленное значение
### getPageDisplay_Zoom() {#getPageDisplay-Zoom--}
```
public int getPageDisplay_Zoom()
```


Получает коэффициент масштабирования отображения страницы.

**Возвращает:**
интервал - целочисленное значение
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Получает номер целевой страницы закладки.

**Возвращает:**
интервал - целочисленное значение
### getRemoteFile() {#getRemoteFile--}
```
public String getRemoteFile()
```


Получает файл (путь), необходимый для действия "GoToR" закладки.

**Возвращает:**
java.lang.String — строковое значение
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает название закладки.

**Возвращает:**
java.lang.String — строковое значение
### getTitleColor() {#getTitleColor--}
```
public Color getTitleColor()
```


Получает цвет заголовка закладки.

**Возвращает:**
[Color](../../java.awt/color) - Цветовой элемент
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isOpen() {#isOpen--}
```
public boolean isOpen()
```


Получает состояние закладки (открыто, закрыто).

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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Устанавливает действие, связанное с закладкой. Если PageNumber представлен, действие не может быть указано. Тип действия включает в себя: «Перейти», «Перейти», «Запустить», «Именованное».

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setBoldFlag(boolean value) {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```


Устанавливает жирный флаг заголовка закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setChildItem(Bookmarks value) {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
```
public void setChildItem(Bookmarks value)
```


Устанавливает дочерние закладки.

Устарело ("Используйте свойство setChildItems() вместо этого".")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Bookmarks](../../com.aspose.pdf.facades/bookmarks) | Элемент закладок |

### setChildItems(Bookmarks value) {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
```
public void setChildItems(Bookmarks value)
```


Устанавливает дочерние закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Bookmarks](../../com.aspose.pdf.facades/bookmarks) | дочерние элементы закладок. |

### setCustomAcorbatViewerMenuActionName(int[] value) {#setCustomAcorbatViewerMenuActionName-int---}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```


Пока не поддерживается.

Задает имя действия, соответствующее выполнению пункта меню в средстве просмотра Acrobat.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | массив значений int |

### setDestination(String value) {#setDestination-java.lang.String-}
```
public void setDestination(String value)
```


Устанавливает целевую страницу закладки. Требуется, если действие установлено как "".

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setItalicFlag(boolean value) {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```


Устанавливает курсивный флаг заголовка закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLevel(int value) {#setLevel-int-}
```
public void setLevel(int value)
```


Устанавливает уровень иерархии закладок.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Устанавливает состояние закладки (открыто, закрыто).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPageDisplay(String value) {#setPageDisplay-java.lang.String-}
```
public void setPageDisplay(String value)
```


Устанавливает тип целевой страницы отображаемой закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setPageDisplay_Bottom(int value) {#setPageDisplay-Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```


Устанавливает нижнюю координату отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPageDisplay_Left(int value) {#setPageDisplay-Left-int-}
```
public void setPageDisplay_Left(int value)
```


Устанавливает левую координату отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPageDisplay_Right(int value) {#setPageDisplay-Right-int-}
```
public void setPageDisplay_Right(int value)
```


Устанавливает правую координату отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPageDisplay_Top(int value) {#setPageDisplay-Top-int-}
```
public void setPageDisplay_Top(int value)
```


Устанавливает верхнюю координату отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPageDisplay_Zoom(int value) {#setPageDisplay-Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```


Устанавливает коэффициент масштабирования отображения страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Устанавливает номер целевой страницы закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRemoteFile(String value) {#setRemoteFile-java.lang.String-}
```
public void setRemoteFile(String value)
```


Устанавливает файл (путь), необходимый для действия "GoToR" закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Устанавливает заголовок закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTitleColor(Color value) {#setTitleColor-java.awt.Color-}
```
public void setTitleColor(Color value)
```


Устанавливает цвет заголовка закладки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color | Цветовой элемент |

### toOutlineItemCollection(IDocument doc) {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
```
public OutlineItemCollection toOutlineItemCollection(IDocument doc)
```


преобразовать в OutlineItemCollection

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Объект документа |

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Объект OutlineItemCollection
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
