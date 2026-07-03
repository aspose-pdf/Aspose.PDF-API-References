---
title: TableAbsorber
second_title: Aspose.PDF for Java API Reference
description: <p> Represents an absorber object of table elements. Performs search and provides access to search results via {@code TableAbsorber.TableList} collection. </p> <hr> <pre> The.
type: docs
weight: 4800
url: /java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Represents an absorber object of table elements. Performs search and provides access to search results via {@code TableAbsorber.TableList} collection. </p> <hr> <pre> The example demonstrates how to find table on the first PDF document page and replace the text in a table cell. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

## Constructors

| Constructor | Description |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Initializes a new instance of the {@code TableAbsorber}. </p> <hr> Performs searching for tables and provides access to the tables via {@code TableList} object. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initializes a new instance of the {@code TableAbsorber}. </p> <hr> Performs searching for tables and provides access to the tables via {@code TableList} object. |

## Methods

| Method | Description |
| --- | --- |
| [getTableList](#getTableList--) | <p> Returns readonly IList containing tables that were found </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Gets text search options. </p> <hr> Allows to define several options that will be used during search text containing in tables. |
| [isUseFlowEngine](#isUseFlowEngine--) | Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of recognizing tables without borders. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Removes an {@code AbsorbedTable} from the page. </p> <hr> <p> Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Replaces an {@code AbsorbedTable} with {@code Table} on the page. </p> <hr> <p> Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Gets or sets text search options. </p> <hr> Allows to define several options that will be used during search text containing in tables. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of recognizing tables without borders. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extracts tables on the specified document. </p> <hr> <pre> The example demonstrates how to extract table on the first PDF document page. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extracts tables on the specified page </p> <hr> <pre> The example demonstrates how to extract table on the first PDF document page. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Initializes a new instance of the {@code TableAbsorber}. </p> <hr> Performs searching for tables and provides access to the tables via {@code TableList} object.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initializes a new instance of the {@code TableAbsorber}. </p> <hr> Performs searching for tables and provides access to the tables via {@code TableList} object.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Returns readonly IList containing tables that were found </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Gets text search options. </p> <hr> Allows to define several options that will be used during search text containing in tables.

**Returns:**
TextSearchOptions object

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of recognizing tables without borders.

**Returns:**
boolean value

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Removes an {@code AbsorbedTable} from the page. </p> <hr> <p> Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Replaces an {@code AbsorbedTable} with {@code Table} on the page. </p> <hr> <p> Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Gets or sets text search options. </p> <hr> Allows to define several options that will be used during search text containing in tables.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Enable an alternative table recognition engine that is superior in numerous scenarios and is capable of recognizing tables without borders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useFlowEngine |  | boolean value |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extracts tables on the specified document. </p> <hr> <pre> The example demonstrates how to extract table on the first PDF document page. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\Tests\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extracts tables on the specified page </p> <hr> <pre> The example demonstrates how to extract table on the first PDF document page. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\Tests\output.pdf"); </pre>
