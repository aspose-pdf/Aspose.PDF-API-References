---
title: TableAbsorber
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示表格元素的吸收器对象。
type: docs
weight: 353
url: /zh/java/com.aspose.pdf/tableabsorber/
---
**遗产：**
java.lang.Object
```
public class TableAbsorber
```

表示表格元素的吸收器对象。通过 TableAbsorber.TableList 集合执行搜索并提供对搜索结果的访问。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TableAbsorber(TextSearchOptions textSearchOptions)](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | 使用文本搜索选项初始化 TableAbsorber 的新实例。 |
| [TableAbsorber()](#TableAbsorber--) | 初始化 TableAbsorber 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getTableList()](#getTableList--) | 返回包含找到的表的只读 IList |
| [getTextSearchOptions()](#getTextSearchOptions--) | 获取文本搜索选项。 |
| [hashCode()](#hashCode--) |  |
| [isUseFlowEngine()](#isUseFlowEngine--) | 激活可用于无边框转换表的替代表识别引擎的早期 alfa 版本。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(AbsorbedTable table)](#remove-com.aspose.pdf.AbsorbedTable-) | 从页面中删除 AbsorbedTable。 |
| [replace(Page page, AbsorbedTable oldTable, Table newTable)](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | 用页面上的表替换 AbsorbedTable。 |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 获取或设置文本搜索选项。 |
| [setUseFlowEngine(boolean useFlowEngine)](#setUseFlowEngine-boolean-) | 激活可用于无边框转换表的替代表识别引擎的早期 alfa 版本。 |
| [toString()](#toString--) |  |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | 提取指定页面上的表格 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableAbsorber(TextSearchOptions textSearchOptions) {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
```
public TableAbsorber(TextSearchOptions textSearchOptions)
```


使用文本搜索选项初始化 TableAbsorber 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项

--------------------

执行表搜索并通过 TableList 对象提供对表的访问。|

### TableAbsorber() {#TableAbsorber--}
```
public TableAbsorber()
```


初始化 TableAbsorber 的新实例。

--------------------

执行表搜索并通过 TableList 对象提供对表的访问。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getTableList() {#getTableList--}
```
public List<AbsorbedTable> getTableList()
```


返回包含找到的表的只读 IList

**退货：**
java.util.List<com.aspose.pdf.AbsorbedTable> - IGenericList 对象 
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


获取文本搜索选项。

--------------------

允许定义几个选项，这些选项将在搜索包含在表格中的文本时使用。

**退货：**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isUseFlowEngine() {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```


激活可用于无边框转换表的替代表识别引擎的早期 alfa 版本。尚不支持编辑表格和获取文本样式。默认情况下是假的。

**退货：**
boolean - 布尔值
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


从页面中删除 AbsorbedTable。

--------------------

请考虑它更改 TableList 集合。如果在循环中删除/替换表，请使用 TableList 集合的副本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| table | [AbsorbedTable](../../com.aspose.pdf/absorbedtable) |  要删除的 AbsorbedTable。 |

### replace(Page page, AbsorbedTable oldTable, Table newTable) {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
```
public void replace(Page page, AbsorbedTable oldTable, Table newTable)
```


用页面上的表替换 AbsorbedTable。

--------------------

请考虑它更改 TableList 集合。如果在循环中删除/替换表，请使用 TableList 集合的副本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf 文档页面对象。 |
| oldTable | [AbsorbedTable](../../com.aspose.pdf/absorbedtable) |  要替换的 AbsorbedTable。 |
| newTable | [Table](../../com.aspose.pdf/table) |  替换旧表的表。 |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


获取或设置文本搜索选项。

--------------------

允许定义几个选项，这些选项将在搜索包含在表格中的文本时使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions 对象 |

### setUseFlowEngine(boolean useFlowEngine) {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```


激活可用于无边框转换表的替代表识别引擎的早期 alfa 版本。尚不支持编辑表格和获取文本样式。默认情况下是假的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| useFlowEngine | boolean | 布尔值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


提取指定页面上的表格

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

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf 文档页面对象。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
