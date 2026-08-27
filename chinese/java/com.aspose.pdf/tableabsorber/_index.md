---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示表元素的吸收器对象。执行搜索并通过 {@code TableAbsorber.TableList} 集合提供对搜索结果的访问。 </p> <hr> <pre> The."
type: docs
weight: 4800
url: /zh/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> 表示表元素的吸收器对象。执行搜索并通过 {@code TableAbsorber.TableList} 集合提供对搜索结果的访问。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上查找表格并替换表格单元格中的文本。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> 初始化 {@code TableAbsorber} 的新实例。 </p> <hr> 执行表格搜索并通过 {@code TableList} 对象提供对表格的访问。 |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> 初始化 {@code TableAbsorber} 的新实例。 </p> <hr> 执行表格搜索并通过 {@code TableList} 对象提供对表格的访问。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTableList](#getTableList--) | <p> 返回只读 IList，包含已找到的表格 </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> 获取文本搜索选项。 </p> <hr> 允许定义在表格中搜索文本时使用的多个选项。 |
| [isUseFlowEngine](#isUseFlowEngine--) | 启用一种在多种场景下更出色且能够识别无边框表格的替代表格识别引擎。 |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> 从页面中移除 {@code AbsorbedTable}。 </p> <hr> <p> 请注意这会更改 TableList 集合。若在循环中移除/替换表格，请使用 TableList 集合的副本。 </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> 将页面上的 {@code AbsorbedTable} 替换为 {@code Table}。 </p> <hr> <p> 请注意这会更改 TableList 集合。若在循环中移除/替换表格，请使用 TableList 集合的副本。 </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> 获取或设置文本搜索选项。 </p> <hr> 允许定义将在表格中搜索文本时使用的多个选项。 |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | 启用一种在多种场景下更出色且能够识别无边框表格的替代表格识别引擎。 |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> 提取指定文档中的表格。 </p> <hr> <pre> 此示例演示如何在 PDF 文档的第一页提取表格。 // Open document Document doc = new Document(@\"D:\\\\Tests\\\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> 提取指定页面上的表格。 </p> <hr> <pre> 此示例演示如何在 PDF 文档的第一页提取表格。 // Open document Document doc = new Document(@\"D:\\\\Tests\\\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\\\Tests\\\\output.pdf\"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> 初始化 {@code TableAbsorber} 的新实例。 </p> <hr> 执行表格搜索并通过 {@code TableList} 对象提供对表格的访问。

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> 初始化 {@code TableAbsorber} 的新实例。 </p> <hr> 执行表格搜索并通过 {@code TableList} 对象提供对表格的访问。

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> 返回只读 IList，包含已找到的表格 </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> 获取文本搜索选项。 </p> <hr> 允许定义在表格中搜索文本时使用的多个选项。

**Returns:**
TextSearchOptions 对象

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

启用一种在多种场景下更出色且能够识别无边框表格的替代表格识别引擎。

**Returns:**
布尔值

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> 从页面中移除 {@code AbsorbedTable}。 </p> <hr> <p> 请注意这会更改 TableList 集合。若在循环中移除/替换表格，请使用 TableList 集合的副本。 </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> 将页面上的 {@code AbsorbedTable} 替换为 {@code Table}。 </p> <hr> <p> 请注意这会更改 TableList 集合。若在循环中移除/替换表格，请使用 TableList 集合的副本。 </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> 获取或设置文本搜索选项。 </p> <hr> 允许定义将在表格中搜索文本时使用的多个选项。

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

启用一种在多种场景下更出色且能够识别无边框表格的替代表格识别引擎。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| useFlowEngine |  | 布尔值 |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> 提取指定文档中的表格。 </p> <hr> <pre> 此示例演示如何在 PDF 文档的第一页提取表格。 // Open document Document doc = new Document(@\"D:\Tests\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\Tests\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> 提取指定页面上的表格。 </p> <hr> <pre> 此示例演示如何在 PDF 文档的第一页提取表格。 // Open document Document doc = new Document(@\"D:\Tests\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\Tests\output.pdf\"); </pre>
