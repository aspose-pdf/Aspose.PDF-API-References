---
title: Class ExcelSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ExcelSaveOptions class. Save options for export to Excel format
type: docs
weight: 4200
url: /net/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class

Save options for export to Excel format

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | Output format |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | Set true if you need inserting of blank column as the first column of worksheet. Default value is false; it means that blank column will not be inserted. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | Set true if you need to minimize the number of worksheets in resultant workbook. Default value is false; it means save of each PDF page as separated worksheet. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | Set true for using uniform columns division through the document. Default value is false; it means that columns division will independent for each page. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |

## Examples

The following example shows how to convert PDF file to XLS or XLSX file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// The path to output xls or xlsx File.
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ExcelSaveOptions	
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// Save xls or xlsx file
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


