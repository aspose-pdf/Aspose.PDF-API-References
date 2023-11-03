---
title: FlowConverter
second_title: Aspose.PDF for Java API Reference
description: Convert PDF Document to Flow formats XLSX ODS XMLSpreedSheet2003 CSV DOCX in EnchanedFlow mode TableAbsorber in FlowEngine mode.
type: docs
weight: 128
url: /java/com.aspose.pdf/flowconverter/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ApsUsingConverter](../../com.aspose.pdf/apsusingconverter)
```
public class FlowConverter extends ApsUsingConverter
```

Convert PDF Document to Flow formats (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX in EnchanedFlow mode, TableAbsorber in FlowEngine mode. !!! Don't port from C\# as could be ahead of .Net version !!!!
## Constructors

| Constructor | Description |
| --- | --- |
| [FlowConverter()](#FlowConverter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [convert(ADocument doc, OutputStream outputStream, ExcelSaveOptions options)](#convert-com.aspose.pdf.ADocument-java.io.OutputStream-com.aspose.pdf.ExcelSaveOptions-) |  |
| [convertInternal(ADocument doc, System.IO.Stream outputStream, ExcelSaveOptions options)](#convertInternal-com.aspose.pdf.ADocument-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ExcelSaveOptions-) |  |
| [convertWithNewEngine(ADocument doc, System.IO.Stream ouputStream, ExcelSaveOptions excelSaveOptions, DocSaveOptions docSaveOptions)](#convertWithNewEngine-com.aspose.pdf.ADocument-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ExcelSaveOptions-com.aspose.pdf.DocSaveOptions-) |  |
| [convertPDFToTableAbsorber(Page page, IDocument document)](#convertPDFToTableAbsorber-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) |  |
### FlowConverter() {#FlowConverter--}
```
public FlowConverter()
```


### convert(ADocument doc, OutputStream outputStream, ExcelSaveOptions options) {#convert-com.aspose.pdf.ADocument-java.io.OutputStream-com.aspose.pdf.ExcelSaveOptions-}
```
public static void convert(ADocument doc, OutputStream outputStream, ExcelSaveOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | com.aspose.pdf.ADocument |  |
| outputStream | java.io.OutputStream |  |
| options | [ExcelSaveOptions](../../com.aspose.pdf/excelsaveoptions) |  |

### convertInternal(ADocument doc, System.IO.Stream outputStream, ExcelSaveOptions options) {#convertInternal-com.aspose.pdf.ADocument-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ExcelSaveOptions-}
```
public static void convertInternal(ADocument doc, System.IO.Stream outputStream, ExcelSaveOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | com.aspose.pdf.ADocument |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |
| options | [ExcelSaveOptions](../../com.aspose.pdf/excelsaveoptions) |  |

### convertWithNewEngine(ADocument doc, System.IO.Stream ouputStream, ExcelSaveOptions excelSaveOptions, DocSaveOptions docSaveOptions) {#convertWithNewEngine-com.aspose.pdf.ADocument-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ExcelSaveOptions-com.aspose.pdf.DocSaveOptions-}
```
public static void convertWithNewEngine(ADocument doc, System.IO.Stream ouputStream, ExcelSaveOptions excelSaveOptions, DocSaveOptions docSaveOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | com.aspose.pdf.ADocument |  |
| ouputStream | com.aspose.ms.System.IO.Stream |  |
| excelSaveOptions | [ExcelSaveOptions](../../com.aspose.pdf/excelsaveoptions) |  |
| docSaveOptions | [DocSaveOptions](../../com.aspose.pdf/docsaveoptions) |  |

### convertPDFToTableAbsorber(Page page, IDocument document) {#convertPDFToTableAbsorber-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
```
public static System.Collections.Generic.List<AbsorbedTable> convertPDFToTableAbsorber(Page page, IDocument document)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.AbsorbedTable>
