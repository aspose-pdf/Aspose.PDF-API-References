---
title: XForm
second_title: Aspose.PDF для справки по Java API
description: Класс представляет XForm
type: docs
weight: 407
url: /ru/java/com.aspose.pdf/xform/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.pdf.ISupportsMemoryCleanup
```
public final class XForm implements ISupportsMemoryCleanup
```

Класс представляет XForm
## Методы

| Метод | Описание |
| --- | --- |
| [containsOwnResources()](#containsOwnResources--) | Возвращает True, если содержит собственные ресурсы |
| [createNewForm(Page source, IDocument document)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Создает XForm, который дублирует содержимое страницы. |
| [createNewForm(Page source, ITrailerable trailerable, Copier copier)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [createNewForm(ITrailerable trailerable)](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Создает новую XForm в документе. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [freeMemory()](#freeMemory--) | Очищает кэшированные данные |
| [getBBox()](#getBBox--) | Получает ограничивающую рамку формы. |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | Получает операторы формы. |
| [getEngineObj()](#getEngineObj--) | Только внутренний |
| [getMatrix()](#getMatrix--) | Получает матрицу формы. |
| [getName()](#getName--) | Получает имя формы. |
| [getOpi()](#getOpi--) | Получает открытый интерфейс допечатной подготовки (OPI). |
| [getRectangle()](#getRectangle--) | Получается прямоугольник формы. |
| [getResources()](#getResources--) | Возвращает ресурсы формы X-Object. |
| [getResources(boolean allowCreate)](#getResources-boolean-) | Возвращает ресурсы формы X-Object |
| [getResources2()](#getResources2--) | Получает ресурсы Form XObject. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBBox(Rectangle value)](#setBBox-com.aspose.pdf.Rectangle-) | Устанавливает ограничивающую рамку формы. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Задает матрицу формы. |
| [setName(String value)](#setName-java.lang.String-) | Задает имя формы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsOwnResources() {#containsOwnResources--}
```
public boolean containsOwnResources()
```


Возвращает True, если содержит собственные ресурсы

**Возвращает:**
boolean - логическое значение
### createNewForm(Page source, IDocument document) {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
```
public static XForm createNewForm(Page source, IDocument document)
```


Создает XForm, который дублирует содержимое страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Page](../../com.aspose.pdf/page) | Исходная страница |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ, в который будет добавлен новый XForm. |

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - Недавно созданная XForm.
### createNewForm(Page source, ITrailerable trailerable, Copier copier) {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}
```
public static XForm createNewForm(Page source, ITrailerable trailerable, Copier copier)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Page](../../com.aspose.pdf/page) |  |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |
| copier | [Copier](../../com.aspose.pdf/copier) |  |

**Возвращает:**
[XForm](../../com.aspose.pdf/xform)
### createNewForm(ITrailerable trailerable) {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
```
public static XForm createNewForm(ITrailerable trailerable)
```


Создает новую XForm в документе.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | Описывает объект ITrailerable |

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - Недавно созданная XForm
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
### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Очищает кэшированные данные

### getBBox() {#getBBox--}
```
public Rectangle getBBox()
```


Получает ограничивающую рамку формы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольник
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


Получает операторы формы.

**Возвращает:**
[OperatorCollection](../../com.aspose.pdf/operatorcollection) - Объект OperatorCollection
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Только внутренний

**Возвращает:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - Объект IPdfObject
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


Получает матрицу формы.

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Матрица
### getName() {#getName--}
```
public String getName()
```


Получает имя формы. Имя формы — это имя, которое используется для ссылки на форму в XObejct ductary в ресурсах страницы.

**Возвращает:**
java.lang.String — Строка
### getOpi() {#getOpi--}
```
public Opi getOpi()
```


Получает открытый интерфейс допечатной подготовки (OPI).

**Возвращает:**
[Opi](../../com.aspose.pdf/opi) - Опи экземпляр
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получается прямоугольник формы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольник
### getResources() {#getResources--}
```
public Resources getResources()
```


Возвращает ресурсы формы X-Object. Если для For нет ресурсов и для параметра allowCreate установлено значение true, для формы будут автоматически созданы ресурсы.

**Возвращает:**
[Resources](../../com.aspose.pdf/resources) - Экземпляр ресурсов
### getResources(boolean allowCreate) {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```


Возвращает ресурсы формы X-Object

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| allowCreate | boolean | Если для For нет ресурсов и для параметра allowCreate установлено значение true, для формы будут автоматически созданы ресурсы. |

**Возвращает:**
[Resources](../../com.aspose.pdf/resources) - Экземпляр ресурсов
### getResources2() {#getResources2--}
```
public final Resources getResources2()
```


Получает ресурсы Form XObject.

**Возвращает:**
[Resources](../../com.aspose.pdf/resources) - Экземпляр ресурсов. Если для формы нет ресурсов, для формы будут автоматически созданы ресурсы.
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




### setBBox(Rectangle value) {#setBBox-com.aspose.pdf.Rectangle-}
```
public void setBBox(Rectangle value)
```


Устанавливает ограничивающую рамку формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Прямоугольник](../../com.aspose.pdf/rectangle) | Rectangle |

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


Задает матрицу формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | Матрица объекта |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Задает имя формы. Имя формы — это имя, которое используется для ссылки на форму в словаре XObejct в ресурсах страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

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
