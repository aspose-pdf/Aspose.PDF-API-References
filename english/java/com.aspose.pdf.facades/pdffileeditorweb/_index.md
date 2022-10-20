---
title: PdfFileEditorWeb
second_title: Aspose.PDF for Java API Reference
description: Represents PdfFileEditorWeb class
type: docs
weight: 40
url: /java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, com.aspose.pdf.facades.APdfFileEditor

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IPdfFileEditor](../../com.aspose.pdf.facades/ipdffileeditor)
```
public final class PdfFileEditorWeb extends APdfFileEditor implements IPdfFileEditor
```

Represents PdfFileEditorWeb class

Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileEditorWeb()](#PdfFileEditorWeb--) | PdfFileEditorWeb constructor. |
## Methods

| Method | Description |
| --- | --- |
| [concatenate(String[] inputFiles, HttpServletResponse response)](#concatenate-java.lang.String---javax.servlet.http.HttpServletResponse-) | Concatenates files and saves reslt into HttpResposnse object. |
| [concatenate(InputStream[] inputStream, HttpServletResponse response)](#concatenate-java.io.InputStream---javax.servlet.http.HttpServletResponse-) | Concatenates files and stores result into HttpServletResponse object. |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response)](#append-java.io.InputStream-java.io.InputStream---int-int-javax.servlet.http.HttpServletResponse-) | Appends documents to source document and saves result into response object. |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response)](#append-java.lang.String-java.lang.String---int-int-javax.servlet.http.HttpServletResponse-) | Appends documents to source document and saves result into HttpServletResponse object. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response)](#insert-java.lang.String-int-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | Inserts contents of file into source file and stores result into HttpServletResponse object. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response)](#insert-java.io.InputStream-int-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | Inserts document into other document and stores result into response object. |
| [delete(String inputFile, int[] pageNumber, HttpServletResponse response)](#delete-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | Deletes specified pages from document and stores result into HttpServletResponse object. |
| [delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response)](#delete-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | Deletes specified pages from document and saves result into HttpServletResponse object. |
| [extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response)](#extract-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | Extracts specified pages form source file and stores result into HttpServletResponse object. |
| [extract(String inputFile, int[] pageNumber, HttpServletResponse response)](#extract-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | Extracts specified pages from source file and stores result into HttpServletResponse object. |
| [splitFromFirst(String inputFile, int location, HttpServletResponse response)](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Splits document from first page to location and saves result into HttpServletResponse objects. |
| [splitFromFirst(InputStream inputStream, int location, HttpServletResponse response)](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Splits document from start to specified location and stores result into HttpServletResponse object. |
| [splitToEnd(InputStream inputStream, int location, HttpServletResponse response)](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Splits from specified location, and saves the rear part into HttpServletResponse object. |
| [splitToEnd(String inputFile, int location, HttpServletResponse response)](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Splits from specified location, and saves the rear part into HttpServletResponse object. |
| [makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-) | Makes booklet from source file and stores result into HttpServletResponse objects. |
| [makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-) | Make booklet from PDF file and stores it into HttpServletResponse. |
| [makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response)](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes booklet from source file and stores result into HttpServletResponse objects. |
| [makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response)](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes booklet from source file and stores result into HttpServletResponse. |
| [makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response)](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse object. |
| [makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response)](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse object. |
| [makeNUp(String inputFile, int x, int y, HttpServletResponse response)](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse. |
| [makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response)](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse. |
| [resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)](#resizeContents-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Resizes contents of pages in document. |
| [resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)](#resizeContents-com.aspose.ms.System.IO.Stream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Resizes contents of pages in document. |
### PdfFileEditorWeb() {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```


PdfFileEditorWeb constructor.

### concatenate(String[] inputFiles, HttpServletResponse response) {#concatenate-java.lang.String---javax.servlet.http.HttpServletResponse-}
```
public boolean concatenate(String[] inputFiles, HttpServletResponse response)
```


Concatenates files and saves reslt into HttpResposnse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Array of files to concatenate. |
| response | javax.servlet.http.HttpServletResponse | Response object. |

**Returns:**
boolean - true if concatenation was successful.
### concatenate(InputStream[] inputStream, HttpServletResponse response) {#concatenate-java.io.InputStream---javax.servlet.http.HttpServletResponse-}
```
public boolean concatenate(InputStream[] inputStream, HttpServletResponse response)
```


Concatenates files and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | Streams array which contain files to concatenate. |
| response | javax.servlet.http.HttpServletResponse | Response object/ |

**Returns:**
boolean - true if operation was succeeded.
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response) {#append-java.io.InputStream-java.io.InputStream---int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response)
```


Appends documents to source document and saves result into response object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream which contains source document. |
| portStreams | java.io.InputStream[] | Array of streams with documents to be appended. |
| startPage | int | Start page of appended page. |
| endPage | int | End page of appended pages. |
| response | javax.servlet.http.HttpServletResponse | Response object where document will be saved. |

**Returns:**
boolean - true if operation was successful.
### append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response) {#append-java.lang.String-java.lang.String---int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response)
```


Appends documents to source document and saves result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Name of file containing source document. |
| portFiles | java.lang.String[] | Array of file names containing appended documents |
| startPage | int | Start page of appended pages. |
| endPage | int | End page of appended pages. |
| response | javax.servlet.http.HttpServletResponse | Response object where document will be saved. |

**Returns:**
boolean - true if operation was succeeded.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response) {#insert-java.lang.String-int-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response)
```


Inserts contents of file into source file and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file name. |
| insertLocation | int | Page number where second file will be inserted. |
| portFile | java.lang.String | Path to file which will be inserted. |
| pageNumber | int[] | Array of page numbers in source file wihich will be inserted. |
| response | javax.servlet.http.HttpServletResponse | Response object where result will be stored. |

**Returns:**
boolean - true of inserting was successful.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response) {#insert-java.io.InputStream-int-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response)
```


Inserts document into other document and stores result into response object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream with source document |
| insertLocation | int | Location where other document will be inserted. |
| portStream | java.io.InputStream | Document to be inserted. |
| pageNumber | int[] | Array of page numbers in second document which will be inserted. |
| response | javax.servlet.http.HttpServletResponse | Response object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### delete(String inputFile, int[] pageNumber, HttpServletResponse response) {#delete-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean delete(String inputFile, int[] pageNumber, HttpServletResponse response)
```


Deletes specified pages from document and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Path of source file. |
| pageNumber | int[] | Array of page numbers which must be deleted. |
| response | javax.servlet.http.HttpServletResponse | Response object where result document will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response) {#delete-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response)
```


Deletes specified pages from document and saves result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source document stream. |
| pageNumber | int[] | Array of page numbers which will be deleted. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object |

**Returns:**
boolean - True if operation succeded.
### extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response) {#extract-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response)
```


Extracts specified pages form source file and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of source document. |
| pageNumber | int[] | Array of page numbers which will be extracted. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### extract(String inputFile, int[] pageNumber, HttpServletResponse response) {#extract-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean extract(String inputFile, int[] pageNumber, HttpServletResponse response)
```


Extracts specified pages from source file and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file path. |
| pageNumber | int[] | Array of page numbers which will be extracted. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - true if pages were extracted successfully.
### splitFromFirst(String inputFile, int location, HttpServletResponse response) {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitFromFirst(String inputFile, int location, HttpServletResponse response)
```


Splits document from first page to location and saves result into HttpServletResponse objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file name. |
| location | int | Split point. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse objects. |

**Returns:**
boolean - True if operation was succeeded.
### splitFromFirst(InputStream inputStream, int location, HttpServletResponse response) {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitFromFirst(InputStream inputStream, int location, HttpServletResponse response)
```


Splits document from start to specified location and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of source document. |
| location | int | The splitting point. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### splitToEnd(InputStream inputStream, int location, HttpServletResponse response) {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitToEnd(InputStream inputStream, int location, HttpServletResponse response)
```


Splits from specified location, and saves the rear part into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source document stream. |
| location | int | Split point. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object. |

**Returns:**
boolean - true if splitting was successful.
### splitToEnd(String inputFile, int location, HttpServletResponse response) {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitToEnd(String inputFile, int location, HttpServletResponse response)
```


Splits from specified location, and saves the rear part into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | source file name. |
| location | int | Split point. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse objects. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response) {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)
```


Makes booklet from source file and stores result into HttpServletResponse objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file path. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Desired page size. |
| leftPages | int[] | Aray of page numbers to be placed in left. |
| rightPages | int[] | Array of page numbers to be placed in right. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response) {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)
```


Make booklet from PDF file and stores it into HttpServletResponse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input document stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Desired page size. |
| leftPages | int[] | Array of page numbers which will be placed in left. |
| rightPages | int[] | Array of page numbers which will b eplaced in right. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response) {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response)
```


Makes booklet from source file and stores result into HttpServletResponse objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file path. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Desired page size in output file. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation is succeeded.
### makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response) {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response)
```


Makes booklet from source file and stores result into HttpServletResponse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input document stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Desired page size in output file. |
| response | javax.servlet.http.HttpServletResponse | Respose object where resut will be saved. |

**Returns:**
boolean - true if booklet was built successfully.
### makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response) {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response)
```


Makes N-up document and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of source document. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size in result file. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response) {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response)
```


Makes N-up document and stores result into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Path to source file. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size in result file. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(String inputFile, int x, int y, HttpServletResponse response) {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(String inputFile, int x, int y, HttpServletResponse response)
```


Makes N-up document and stores result into HttpServletResponse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file name. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response) {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response)
```


Makes N-up document and stores result into HttpServletResponse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of input document. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse where result will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response) {#resizeContents-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
```
public boolean resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)
```


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.Result is stored into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source file. |
| pages | int[] | Array of pages to be resized. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result is saved. |

**Returns:**
boolean - True if operation was succeeded.
### resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response) {#resizeContents-com.aspose.ms.System.IO.Stream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
```
public boolean resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)
```


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.Result is stored into HttpServletResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | com.aspose.ms.System.IO.Stream | Stream of source file. |
| pages | int[] | Array of pages to be resized. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse object where result is saved. |

**Returns:**
boolean - True if operation was succeeded.
