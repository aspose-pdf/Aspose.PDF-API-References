---
title: ExcelSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Excel format
type: docs
weight: 1260
url: /java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Save options for export to Excel format

## Constructors

| Constructor | Description |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Gets or sets factor that will be applied to (virtual) scaling font size during conversion to Excel table in / * legacy engine. Setting of less value facilitates the search for columns and prevents merging of them for some / * documents. Default value is 0.9; Setting value to zero allows algorithm choose scaling automatically. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted. |
| [isUniformWorksheets](#isUniformWorksheets--) | Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Output format |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Defines conversion engine that will be used for conversion |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Constructor

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Gets or sets factor that will be applied to (virtual) scaling font size during conversion to Excel table in / * legacy engine. Setting of less value facilitates the search for columns and prevents merging of them for some / * documents. Default value is 0.9; Setting value to zero allows algorithm choose scaling automatically. / * / * / *

**Returns:**
double value /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet.

**Returns:**
boolean value

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted.

**Returns:**
boolean value

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page.

**Returns:**
boolean value

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Output format

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Set false if you need suppress inserting of blank column as the first column of worksheet. Default value is true; it means that blank column will be inserted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Defines conversion engine that will be used for conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |
