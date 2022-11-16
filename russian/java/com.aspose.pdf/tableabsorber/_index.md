---
title: TableAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель элементов таблицы.
type: docs
weight: 353
url: /ru/java/com.aspose.pdf/tableabsorber/
---
**Наследование:**
java.lang.Object
```
public class TableAbsorber
```

Представляет объект-поглотитель элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию TableAbsorber.TableList.

--------------------

```
The example demonstrates how to find table on the first PDF document page and replace the text in a table cell.

 	// Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TableAbsorber object to find tables
 TableAbsorber absorber = new TableAbsorber();
 // Visit first page with absorber
 absorber.visit(doc.getPages().get_Item(1));
 // Get access to first table on page, their first cell and text fragments in it
 TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0)
 .getTextFragments().get_Item(1);
 // Change text of the first text fragment in the cell
 fragment.setText("hi world");
 // Save document
 doc.save("D:\\Tests\\output.pdf");
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TableAbsorber(TextSearchOptions textSearchOptions)](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | Инициализирует новый экземпляр TableAbsorber с параметрами текстового поиска. |
| [TableAbsorber()](#TableAbsorber--) | Инициализирует новый экземпляр TableAbsorber . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getTableList()](#getTableList--) | Возвращает IList только для чтения, содержащий найденные таблицы. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Получает параметры поиска текста. |
| [hashCode()](#hashCode--) |  |
| [isUseFlowEngine()](#isUseFlowEngine--) | Активируйте раннюю альфа-версию альтернативного механизма распознавания таблиц, который можно использовать для преобразования таблиц без границ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(AbsorbedTable table)](#remove-com.aspose.pdf.AbsorbedTable-) | Удаляет AbsorbedTable со страницы. |
| [replace(Page page, AbsorbedTable oldTable, Table newTable)](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | Заменяет AbsorbedTable на Table на странице. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Получает или задает параметры текстового поиска. |
| [setUseFlowEngine(boolean useFlowEngine)](#setUseFlowEngine-boolean-) | Активируйте раннюю альфа-версию альтернативного механизма распознавания таблиц, который можно использовать для преобразования таблиц без границ. |
| [toString()](#toString--) |  |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Извлекает таблицы на указанной странице |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableAbsorber(TextSearchOptions textSearchOptions) {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
```
public TableAbsorber(TextSearchOptions textSearchOptions)
```


Инициализирует новый экземпляр TableAbsorber с параметрами текстового поиска.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Параметры текстового поиска

--------------------

 Выполняет поиск таблиц и предоставляет доступ к таблицам через объект TableList.|

### TableAbsorber() {#TableAbsorber--}
```
public TableAbsorber()
```


Инициализирует новый экземпляр TableAbsorber .

--------------------

Выполняет поиск таблиц и предоставляет доступ к таблицам через объект TableList.

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
### getTableList() {#getTableList--}
```
public List<AbsorbedTable> getTableList()
```


Возвращает IList только для чтения, содержащий найденные таблицы.

**Возвращает:**
java.util.List<com.aspose.pdf.AbsorbedTable> — объект IGenericList 
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Получает параметры поиска текста.

--------------------

Позволяет определить несколько опций, которые будут использоваться при поиске текста, содержащегося в таблицах.

**Возвращает:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - Объект TextSearchOptions
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isUseFlowEngine() {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```


Активируйте раннюю альфа-версию альтернативного механизма распознавания таблиц, который можно использовать для преобразования таблиц без границ. Пока не поддерживает редактирование таблиц и получение стилей текста. По умолчанию ложно.

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




### remove(AbsorbedTable table) {#remove-com.aspose.pdf.AbsorbedTable-}
```
public void remove(AbsorbedTable table)
```


Удаляет AbsorbedTable со страницы.

--------------------

Пожалуйста, примите во внимание, что это изменяет коллекцию TableList. В случае удаления/замены таблиц в цикле используйте копию коллекции TableList.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| table | [AbsorbedTable](../../com.aspose.pdf/absorbedtable) |  AbsorbedTable удалить. |

### replace(Page page, AbsorbedTable oldTable, Table newTable) {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
```
public void replace(Page page, AbsorbedTable oldTable, Table newTable)
```


Заменяет AbsorbedTable на Table на странице.

--------------------

Пожалуйста, примите во внимание, что это изменяет коллекцию TableList. В случае удаления/замены таблиц в цикле используйте копию коллекции TableList.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа Pdf. |
| oldTable | [AbsorbedTable](../../com.aspose.pdf/absorbedtable) |  AbsorbedTable подлежит замене. |
| newTable | [Table](../../com.aspose.pdf/table) |  Стол на замену старому столу. |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Получает или задает параметры текстового поиска.

--------------------

Позволяет определить несколько опций, которые будут использоваться при поиске текста, содержащегося в таблицах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Объект TextSearchOptions |

### setUseFlowEngine(boolean useFlowEngine) {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```


Активируйте раннюю альфа-версию альтернативного механизма распознавания таблиц, который можно использовать для преобразования таблиц без границ. Пока не поддерживает редактирование таблиц и получение стилей текста. По умолчанию ложно.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| useFlowEngine | boolean | логическое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Извлекает таблицы на указанной странице

--------------------

```
The example demonstrates how to extract table on the first PDF document page.

 // Open document
 Document doc = new Document(@"D:\Tests\input.pdf");
 // Create TableAbsorber object to find tables
 TableAbsorber absorber = new TableAbsorber();
 // Visit first page with absorber
 absorber.visit(pdfDocument.getPages.get_item(1));
 // Get access to first table on page, their first cell and text fragments in it
 TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0)
 .getTextFragments.get_item(1);
 // Change text of the first text fragment in the cell
 fragment.setText ("hi world");
 // Save document
 doc.save(@"D:\Tests\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа PDF. |

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
