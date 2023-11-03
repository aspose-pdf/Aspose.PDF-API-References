---
title: ExcelSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Excel format
type: docs
weight: 100
url: /java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Save options for export to Excel format
## Constructors

| Constructor | Description |
| --- | --- |
| [ExcelSaveOptions()](#ExcelSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getMinimizeTheNumberOfWorksheets()](#getMinimizeTheNumberOfWorksheets--) | Set true if you need to minimize the number of worksheets in resultant workbook. |
| [setMinimizeTheNumberOfWorksheets(boolean value)](#setMinimizeTheNumberOfWorksheets-boolean-) | Set true if you need to minimize the number of worksheets in resultant workbook. |
| [isInsertBlankColumnAtFirst()](#isInsertBlankColumnAtFirst--) | Set false if you need suppress inserting of blank column as the first column of worksheet. |
| [setInsertBlankColumnAtFirst(boolean value)](#setInsertBlankColumnAtFirst-boolean-) | Set false if you need suppress inserting of blank column as the first column of worksheet. |
| [isUniformWorksheets()](#isUniformWorksheets--) | Set true for using uniform columns division through the document. |
| [setUniformWorksheets(boolean value)](#setUniformWorksheets-boolean-) | Set true for using uniform columns division through the document. |
| [getFormat()](#getFormat--) | Output format. |
| [setFormat(int value)](#setFormat-int-) | Output format |
### ExcelSaveOptions() {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```


Constructor

### getMinimizeTheNumberOfWorksheets() {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```


Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet.

**Returns:**
boolean - boolean value
### setMinimizeTheNumberOfWorksheets(boolean value) {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```


Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isInsertBlankColumnAtFirst() {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```


Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted.

**Returns:**
boolean - boolean value
### setInsertBlankColumnAtFirst(boolean value) {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```


Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isUniformWorksheets() {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```


Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page.

**Returns:**
boolean - boolean value
### setUniformWorksheets(boolean value) {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```


Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getFormat() {#getFormat--}
```
public int getFormat()
```


Output format.

Return  ExcelSaveOptions.ExcelFormat.XMLSpreadSheet2003  or  ExcelSaveOptions.ExcelFormat.XLSX  or  ExcelSaveOptions.ExcelFormat.CSV 

**Returns:**
int - ExcelFormat element
### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


Output format

Use the  ExcelSaveOptions.ExcelFormat.XMLSpreadSheet2003  or  ExcelSaveOptions.ExcelFormat.XLSX 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExcelFormat element |

