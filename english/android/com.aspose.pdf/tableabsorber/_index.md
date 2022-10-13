---
title: TableAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of table elements.
type: docs
weight: 284
url: /java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object
```
public class TableAbsorber
```

Represents an absorber object of table elements. Performs search and provides access to search results via  TableAbsorber.TableList  collection.

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
## Constructors

| Constructor | Description |
| --- | --- |
| [TableAbsorber(TextSearchOptions textSearchOptions)](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | Initializes a new instance of the  TableAbsorber  with text search options. |
| [TableAbsorber()](#TableAbsorber--) | Initializes a new instance of the  TableAbsorber . |
## Methods

| Method | Description |
| --- | --- |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets text search options. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Gets or sets text search options. |
| [getTableList()](#getTableList--) | Returns readonly IList containing tables that were found |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Extracts tables on the specified page |
### TableAbsorber(TextSearchOptions textSearchOptions) {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
```
public TableAbsorber(TextSearchOptions textSearchOptions)
```


Initializes a new instance of the  TableAbsorber  with text search options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Text search options

--------------------

Performs searching for tables and provides access to the tables via  TableList  object. |

### TableAbsorber() {#TableAbsorber--}
```
public TableAbsorber()
```


Initializes a new instance of the  TableAbsorber .

--------------------

Performs searching for tables and provides access to the tables via  TableList  object.

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets text search options.

--------------------

Allows to define several options that will be used during search text containing in tables.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions object
### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Gets or sets text search options.

--------------------

Allows to define several options that will be used during search text containing in tables.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions object |

### getTableList() {#getTableList--}
```
public System.Collections.Generic.IGenericList<AbsorbedTable> getTableList()
```


Returns readonly IList containing tables that were found

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.pdf.AbsorbedTable> -  IGenericList object 
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Extracts tables on the specified page

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
 TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0).getTextFragments.get_item(1);
 // Change text of the first text fragment in the cell
 fragment.setText ("hi world");
 // Save document
 doc.save(@"D:\Tests\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf pocument page object. |

