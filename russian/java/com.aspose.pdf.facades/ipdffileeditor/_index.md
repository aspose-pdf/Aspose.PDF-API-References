---
название: IPdfFileEditor
second_title: Aspose.PDF для справки по Java API
описание: Реализует операции с конкатенацией файлов PDF, разделением, извлечением страниц, созданием буклетов и т.д.
тип: документы
вес: 70
URL-адрес: /java/com.aspose.pdf.facades/ipdffileeditor/
---```
общедоступный интерфейс IPdfFileEditor
```

Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.
## Methods

| Method | Description |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Resizes page contents and add specified margins. |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | Resizes page contents and add specified margins. |
| [append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-) | Appends pages, which are chosen from array of documents in portStreams. |
| [append(String inputFile, String portFile, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String---int-int-java.lang.String-) | Appends pages, which are chosen from portFiles documents. |
| [concatenate(IDocument[] src, IDocument dest)](#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-) | Concatenates documents. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatenates two files. |
| [concatenate(InputStream[] inputStream, OutputStream outputStream)](#concatenate-java.io.InputStream---java.io.OutputStream-) | Concatenates files |
| [concatenate(String firstInputFile, String secInputFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatentates two files. |
| [concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. |
| [concatenate(String[] inputFiles, String outputFile)](#concatenate-java.lang.String---java.lang.String-) | Concatenates files into one file. |
| [delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#delete-java.io.InputStream-int---java.io.OutputStream-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [delete(String inputFile, int[] pageNumber, String outputFile)](#delete-java.lang.String-int---java.lang.String-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extracts pages from input file,saves as a new Pdf file. |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | Extracts pages specified by number array, saves as a new Pdf file. |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | Extracts pages from input file,saves as a new Pdf file. |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | Extracts pages specified by number array, saves as a new PDF file. |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | is Allow Concatenate Exceptions |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | If set to true, streams are closed after operation. |
| [getContentDisposition()](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [getConversionLog()](#getConversionLog--) | Gets log of conversion process. |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | This property defines behavior when concatenating process met corrupted file. |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | If true, incremental updates are made during concatenation. |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | If true then field names will be made unique when forms are concatenated. |
| [getLastException()](#getLastException--) | Gets last occured exception. |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | If true, duplicate outlines are merged. |
| [getOwnerPassword()](#getOwnerPassword--) | Gets owner's password if the source input Pdf file is encrypted. |
| [getPreserveUserRights()](#getPreserveUserRights--) | If true, user rights of first document are applied to concatenated document. |
| [getRemoveSignatures()](#getRemoveSignatures--) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [getSaveOptions()](#getSaveOptions--) | Gets or sets save options when result is stored as HttpServletResponse. |
| [getUniqueSuffix()](#getUniqueSuffix--) | Get format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserts pages from an other file into the Pdf file at a position. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | Inserts pages from an other file into the input Pdf file. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream)](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Makes booklet from the InputStream to outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Makes booklet from the input stream and save result into output stream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---) | Makes booklet from the firstInputStream to outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---) | Makes customized booklet from the firstInputStream to outputStream. |
| [makeBooklet(String inputFile, String outputFile)](#makeBooklet-java.lang.String-java.lang.String-) | Makes booklet from the input file to output file. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Makes booklet from the inputFile to outputFile. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-int---int---) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Makes N-Up document from the two input PDF streams to outputStream. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Makes N-Up document from the input stream and saves result into output stream. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the first input stream to output stream. |
| [makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)](#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-) | Makes N-Up document from the multi input PDF streams to outputStream. |
| [makeNUp(String inputFile, String outputFile, int x, int y)](#makeNUp-java.lang.String-java.lang.String-int-int-) | Makes N-Up document from the firstInputFile to outputFile. |
| [makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the input file to outputFile. |
| [makeNUp(String firstInputFile, String secondInputFile, String outputFile)](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Makes N-Up document from the two input PDF files to outputFile. |
| [makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)](#makeNUp-java.lang.String---java.lang.String-boolean-) | Makes N-Up document from the multi input PDF files to outputFile. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | Resizes contents of document pages. |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | Resizes contents of document pages. |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | Resizes contents of document pages. |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | Resizes contents of document pages. |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | If set to true, exceptions are thrown if error occured. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | If set to true, streams are closed after operation. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | This property defines behavior when concatenating process met corrupted file. |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | If true, incremental updates are made during concatenation. |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | If true then field names will be made unique when forms are concatenated. |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | If true, duplicate outlines are merged. |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Sets owner's password if the source input Pdf file is encrypted. |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | If true, user rights of first document are applied to concatenated document. |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpServletResponse. |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | Set format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Splits from start to specified location,and saves the front part in output Stream. |
| [splitFromFirst(String inputFile, int location, String outputFile)](#splitFromFirst-java.lang.String-int-java.lang.String-) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [splitToBulks(InputStream inputStream, int[][] numberOfPage)](#splitToBulks-java.io.InputStream-int-----) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToBulks(String inputFile, int[][] numberOfPage)](#splitToBulks-java.lang.String-int-----) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToEnd(InputStream inputStream, int location, OutputStream outputStream)](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Splits from specified location, and saves the rear part as a new file Stream. |
| [splitToEnd(String inputFile, int location, String outputFile)](#splitToEnd-java.lang.String-int-java.lang.String-) | Splits from location, and saves the rear part as a new file. |
| [splitToPages(InputStream inputStream)](#splitToPages-java.io.InputStream-) | Splits the Pdf file into single-page documents. |
| [splitToPages(InputStream inputStream, String fileNameTemplate)](#splitToPages-java.io.InputStream-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |
| [splitToPages(String inputFile)](#splitToPages-java.lang.String-) | Splits the PDF file into single-page documents. |
| [splitToPages(String inputFile, String fileNameTemplate)](#splitToPages-java.lang.String-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |
### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
общедоступный абстрактный логический addMargins (источник InputStream, назначение OutputStream, int[] страницы, двойное левое поле, двойное правое поле, двойное верхнее поле, двойное нижнее поле)
```


Resizes page contents and add specifed margins. Margins are specified in default space units.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream src = новый FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.addMargins (источник, пункт назначения,
 // обрабатываем страницы 1, 2, 3
 	новый инт[]
 	{1, 2, 3},
 	// левое поле 10 единиц
 	10,
 	// правое поле 5 единиц
 	5,
 	// верхнее поле 5 единиц
 	5,
 	// нижнее поле 5 единиц
 	5);
 назначения.Закрыть();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin. |
| rightMargin | double | Right margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

**Returns:**
boolean - boolean value
### addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-}
```
общедоступный абстрактный логический addMargins (источник строки, пункт назначения строки, int[] страницы, двойное левое поле, двойное правое поле, двойное верхнее поле, двойное нижнее поле)
```


Resizes page contents and add specifed margins. Margins are specified in default space units.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.addMargins("input.pdf", "output.pdf",
 // обрабатываем страницы 1, 2, 3
 	новый инт[]
 	{1, 2, 3},
 	// левое поле 10 единиц
 	10,
 	// правое поле 5 единиц
 	5,
 	// верхнее поле 5 единиц
 	5,
 	// нижнее поле 5 единиц
 	5);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin. |
| rightMargin | double | Right margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

**Returns:**
boolean - true if resize was successful.
### addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
общедоступное абстрактное логическое значение addMarginsPct (источник InputStream, место назначения OutputStream, int[] страницы, двойное левое поле, двойное правое поле, двойное верхнее поле, двойное нижнее поле)
```


Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream src = новый FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.addMarginsPct (источник, пункт назначения,
 // обрабатываем страницы 1, 2, 3
 	новый инт[]
 	{1, 2, 3},
 	// левое поле составляет 15% от ширины страницы
 	15,
 	// правое поле составляет 10% от ширины страницы
 	10,
 	// верхнее поле составляет 20% от ширины страницы
 	20,
 	// нижнее поле составляет 5% от ширины страницы
 	5);
 назначение.закрыть();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin in percents of initial page size. |
| rightMargin | double | Right margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

**Returns:**
boolean - true if resize was successful
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
общедоступный абстрактный логический addMarginsPct (источник строки, пункт назначения строки, int[] страницы, двойное левое поле, двойное правое поле, двойное верхнее поле, двойное нижнее поле)
```


Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.addMarginsPct("input.pdf", "output.pdf",
 // обрабатываем страницы 1, 2, 3
 	новый инт[]
 	{1, 2, 3},
 	// левое поле составляет 15% от ширины страницы
 	15,
 	// правое поле составляет 10% от ширины страницы
 	10,
 	// верхнее поле составляет 20% от ширины страницы
 	20,
 	// нижнее поле составляет 5% от ширины страницы
 	5);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin in percents of initial page size. |
| rightMargin | double | Right margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

**Returns:**
boolean - true if resize was successful
### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
общедоступное абстрактное логическое добавление (InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream instream = новый FileInputStream("input.pdf");
 InputStream stream1 = новый FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1, 3, 5, outstream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| portStream | java.io.InputStream | Pages from Pdf file Stream. |
| startPage | int | Page starts in portFile Stream. |
| endPage | int | Page ends in portFile Stream. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True for success, or false.
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-}
```
общедоступное абстрактное логическое добавление (InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream instream = новый FileInputStream("input.pdf");
 InputStream stream1 = новый FileInputStream("file1.pdf");
 InputStream stream2 = новый FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, новый поток[]
 {поток1, поток2}, 3, 5, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf stream. |
| portStreams | java.io.InputStream[] | Documents to copy pages from. |
| startPage | int | Page starts in portStreams documents. |
| endPage | int | Page ends in portStreams documents . |
| outputStream | java.io.OutputStream | Output Pdf stream. |

**Returns:**
boolean - True for success, or false.
### append(String inputFile, String portFile, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
```
общедоступное абстрактное логическое добавление (String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| portFile | java.lang.String | Pages from Pdf file. |
| startPage | int | Page starts in portFile. |
| endPage | int | Page ends in portFile. |
| outputFile | java.lang.String | Output Pdf document. |

**Returns:**
boolean - True if operation was succeeded.
### append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String---int-int-java.lang.String-}
```
публичное абстрактное логическое добавление (String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.append("input.pdf", новая строка[]
 { "file1.pdf", "file2.pdf" }, 3, 5, "outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| portFiles | java.lang.String[] | Documents to copy pages from. |
| startPage | int | Page starts in portFiles documents. |
| endPage | int | Page ends in portFiles documents . |
| outputFile | java.lang.String | Output Pdf document. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(IDocument[] src, IDocument dest) {#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-}
```
общедоступная абстрактная логическая конкатенация (IDocument[] источник, пункт назначения IDocument)
```


Concatenates documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IDocument\[\]](../../com.aspose.pdf/idocument) | Array of source documents. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Destination document. |

**Returns:**
boolean - True if concatenation is successful.
### concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
общедоступная абстрактная логическая конкатенация (InputStream firstInputStream, InputStream secInputStream, InputStream BlankPageStream, OutputStream outputStream)
```


Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream stream1 = новый FileInputStream("file1.pdf");
 InputStream stream2 = новый FileInputStream("file2.pdf");
 Пустой InputStream = новый FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate (новый поток[]
 {поток1, поток2, пустой}, исходящий);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | The first Pdf Stream. |
| secInputStream | java.io.InputStream | The second Pdf Stream. |
| blankPageStream | java.io.InputStream | The Pdf Stream with blank page |
| outputStream | java.io.OutputStream | Output Pdf Stream. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
общедоступная абстрактная логическая конкатенация (InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
```


Concatenates two files.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream stream1 = новый FileInputStream("file1.pdf");
 InputStream stream2 = новый FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate (поток1, поток2, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | Stream of first file. |
| secInputStream | java.io.InputStream | Stream of second file. |
| outputStream | java.io.OutputStream | Stream where result file will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(InputStream[] inputStream, OutputStream outputStream) {#concatenate-java.io.InputStream---java.io.OutputStream-}
```
публичная абстрактная логическая конкатенация (InputStream[] inputStream, OutputStream outputStream)
```


Concatenates files

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream stream1 = новый FileInputStream("file1.pdf");
 InputStream stream2 = новый FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate (новый поток[]
 {поток1, поток2}, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | Array of streams to be concatenated. |
| outputStream | java.io.OutputStream | Stream where result file will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(String firstInputFile, String secInputFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
```
общедоступная абстрактная логическая конкатенация (String firstInputFile, String secInputFile, String outputFile)
```


Concatentates two files.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | First file to concatenate. |
| secInputFile | java.lang.String | Second file to concatenate. |
| outputFile | java.lang.String | Output file. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
общедоступная абстрактная логическая конкатенация (String firstInputFile, String secInputFile, String BlankPageFile, String outputFile)
```


Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | First file. |
| secInputFile | java.lang.String | Second file. |
| blankPageFile | java.lang.String | PDF file with blank page. |
| outputFile | java.lang.String | Result file. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(String[] inputFiles, String outputFile) {#concatenate-java.lang.String---java.lang.String-}
```
публичная абстрактная логическая конкатенация (строка[] inputFiles, String outputFile)
```


Concatenates files into one file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.concatenate (новая строка[]
 "src1.pdf", "src2.pdf" }, "dest.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Array of files to concatenate. |
| outputFile | java.lang.String | Name of output file. |

**Returns:**
boolean - True if operation was succeeded.
### delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#delete-java.io.InputStream-int---java.io.OutputStream-}
```
публичное абстрактное логическое удаление (InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Deletes pages specified by number array from input file, saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.Delete (входной поток, новый интервал[]
 { 2, 3 }, выходной поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| pageNumber | int[] | Index of page out of the input file. |
| outputStream | java.io.OutputStream | Output file stream. |

**Returns:**
boolean - True for success, or false.
### delete(String inputFile, int[] pageNumber, String outputFile) {#delete-java.lang.String-int---java.lang.String-}
```
публичное абстрактное логическое удаление (String inputFile, int[] pageNumber, String outputFile)
```


Deletes pages specified by number array from input file, saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.delete("input.pdf", новый интервал[]
 { 2, 3 }, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file path. |
| pageNumber | int[] | Index of page out of the input file. |
| outputFile | java.lang.String | Output file path. |

**Returns:**
boolean - True if operation was succeeded.
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
открытый абстрактный логический экстракт (InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
```


Extracts pages from input file,saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.extract (исходный поток, 1, 3, 6, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| startPage | int | Start page number. |
| endPage | int | End page number. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True for success, or false.
### extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#extract-java.io.InputStream-int---java.io.OutputStream-}
```
открытый абстрактный логический экстракт (InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Extracts pages specified by number array, saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.extract (исходный поток, новый интервал[]
 {3, 5, 8}, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| pageNumber | int[] | Index of page out of the input file. |
| outputStream | java.io.OutputStream | Output file stream. |

**Returns:**
boolean - True for success, or false.
### extract(String inputFile, int startPage, int endPage, String outputFile) {#extract-java.lang.String-int-int-java.lang.String-}
```
открытый абстрактный логический экстракт (String inputFile, int startPage, int endPage, String outputFile)
```


Extracts pages from input file,saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.extract("input.pdf", 3, 7, "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file path. |
| startPage | int | Start page number. |
| endPage | int | End page number. |
| outputFile | java.lang.String | Output Pdf file path. |

**Returns:**
boolean - True for success, or false.
### extract(String inputFile, int[] pageNumber, String outputFile) {#extract-java.lang.String-int---java.lang.String-}
```
публичный абстрактный логический экстракт (String inputFile, int[] pageNumber, String outputFile)
```


Extracts pages specified by number array, saves as a new PDF file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.extract("input.pdf", новый интервал[]
 { 3, 5, 7 }, "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file path. |
| pageNumber | int[] | Index of page out of the input file. |
| outputFile | java.lang.String | Output file path. |

**Returns:**
boolean - True if operation was succeeded.
### getAllowConcatenateExceptions() {#getAllowConcatenateExceptions--}
```
публичное абстрактное логическое значение getAllowConcatenateExceptions()
```


is Allow Concatenate Exceptions

**Returns:**
boolean - boolean value
### getAttachmentName() {#getAttachmentName--}
```
общедоступная абстрактная строка getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Returns:**
java.lang.String - string value
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
публичное абстрактное логическое значение getCloseConcatenatedStreams()
```


If set to true, streams are closed after operation.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.setCloseConcatenatedStreams (истина);
```

**Returns:**
boolean - boolean value
### getContentDisposition() {#getContentDisposition--}
```
общедоступная абстракция int getContentDisposition()
```


Gets how content will be stored when result of operation is stored into HttpServletResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int - ContentDisposition element
### getConversionLog() {#getConversionLog--}
```
общедоступная абстрактная строка getConversionLog()
```


Gets log of conversion process.

**Returns:**
java.lang.String - string value
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
общедоступная абстракция int getCorruptedFileAction()
```


This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted.

**Returns:**
int - ConcatenateCorruptedFileAction element
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
публичное абстрактное логическое значение getIncrementalUpdates()
```


If true, incremental updates are made during concatenation.

**Returns:**
boolean - boolean value
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
публичное абстрактное логическое значение getKeepFieldsUnique()
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Returns:**
boolean - boolean value
### getLastException() {#getLastException--}
```
публичное абстрактное исключение getLastException()
```


Gets last occured exception. May be used to check the reason of failure when AllowconcatenateExceptions = false.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.setAllowConcatenateExceptions (ложь);
 если (!pfe.concatenate("", "", ""))
 {
     Система.out.println("");
     если (pfe.getLastException() != ноль)
     {
 	System.out.println(pfe.getLastException().getMessage());
 	если (pfe.getLastException().getCause() != ноль)
 	    System.out.println(pfe.getLastException().getCause().getMessage());
     }
 }
```

**Returns:**
java.lang.Exception - java.lang.Exception object
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
публичное абстрактное логическое значение getMergeDuplicateLayers()
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Returns:**
boolean - boolean value
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
публичное абстрактное логическое значение getMergeDuplicateOutlines()
```


If true, duplicate outlines are merged.

**Returns:**
boolean - boolean value
### getOwnerPassword() {#getOwnerPassword--}
```
общедоступная абстрактная строка getOwnerPassword()
```


Gets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Returns:**
java.lang.String - string value
### getPreserveUserRights() {#getPreserveUserRights--}
```
публичное абстрактное логическое значение getPreserveUserRights()
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Returns:**
boolean - boolean value
### getRemoveSignatures() {#getRemoveSignatures--}
```
публичное абстрактное логическое значение getRemoveSignatures()
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Returns:**
boolean - boolean value
### getSaveOptions() {#getSaveOptions--}
```
открытый абстрактный SaveOptions getSaveOptions()
```


Gets or sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getUniqueSuffix() {#getUniqueSuffix--}
```
общедоступная абстрактная строка getUniqueSuffix()
```


Get format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

**Returns:**
java.lang.String - string value
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
общедоступная абстрактная логическая вставка (InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 InputStream insertStream = новый FileInputStream ("file2.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.insert (исходный поток, 1, вставленный поток, 2, 6, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| startPage | int | From which page to start. |
| endPage | int | To which page to end. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True for success, or false.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
общедоступная абстрактная логическая вставка (InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 InputStream insertStream = новый FileInputStream ("file2.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.insert (исходный поток, 1, вставленный поток, новый интервал[]
 {3, 4, 5}, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True if operation was succeeded.
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
общедоступная абстрактная логическая вставка (String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


Inserts pages from an other file into the Pdf file at a position.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Position in input file. |
| portFile | java.lang.String | The porting Pdf file. |
| startPage | int | Start position in portFile. |
| endPage | int | End position in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
общедоступная абстрактная логическая вставка (String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.insert("file1.pdf", 1, "out.pdf", 2, 6, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Insert position in input file. |
| portFile | java.lang.String | Pages from the Pdf file. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
открытый абстрактный логический makeBooklet (InputStream inputStream, OutputStream outputStream)
```


Makes booklet from the InputStream to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeBooklet (входной поток, выходной поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | output pdf stream. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
открытый абстрактный логический makeBooklet (InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


Makes booklet from the input stream and save result into output stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
открытый абстрактный логический makeBooklet (InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] левые страницы, интервал[] правые страницы)
```


Makes booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeBooklet (inputStream, outputStream, PageSize.A4, новый int[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
открытый абстрактный логический makeBooklet (InputStream inputStream, OutputStream outputStream, int[] левые страницы, интервал[] правые страницы)
```


Makes customized booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeBooklet (входной поток, выходной поток, новый интервал[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
открытый абстрактный логический makeBooklet (String inputFile, String outputFile)
```


Makes booklet from the input file to output file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
открытый абстрактный логический makeBooklet (String inputFile, String outputFile, PageSize pageSize)
```


Makes booklet from the inputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation is succeeded.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
открытый абстрактный логический makeBooklet (String inputFile, String outputFile, PageSize pageSize, int[] левые страницы, интервал[] правые страницы)
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, новый int[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
открытый абстрактный логический makeBooklet (String inputFile, String outputFile, int[] левые страницы, интервал[] правые страницы)
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", новый интервал[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| leftPages | int[] | The left pages of the booklet. |
| rightPages | int[] | The right pages of the booklet. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
открытый абстрактный логический makeNUp (InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
```


Makes N-Up document from the two input PDF streams to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream input1 = новый FileInputStream("input1.pdf");
 InputStream input2 = новый FileInputStream("input2.pdf");
 OutputStream output = новый FileOutputStream("output.pdf");
 pfe.makeNUp (вход1, ввод2, вывод);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | first input stream. |
| secondInputStream | java.io.InputStream | second input stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
открытый абстрактный логический makeNUp (InputStream inputStream, OutputStream outputStream, int x, int y)
```


Makes N-Up document from the input stream and saves result into output stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeNUp (входной поток, выходной поток, 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
открытый абстрактный логический makeNUp (InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


Makes N-Up document from the first input stream to output stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
открытый абстрактный логический makeNUp (InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream stream1 = новый FileInputStream("input1.pdf");
 InputStream stream2 = новый FileInputStream("input2.pdf");
 InputStream stream3 = новый FileInputStream("input3.pdf");
 OutputStream output = новый FileOutputStream("output.pdf");
 pfe.makeNUp (новый поток[]
 {поток1, поток2, поток3}, вывод, ложь);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | Input Pdf streams. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
открытый абстрактный логический makeNUp (String inputFile, String outputFile, int x, int y)
```


Makes N-Up document from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
открытый абстрактный логический makeNUp (String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


Makes N-Up document from the input file to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
открытый абстрактный логический makeNUp (строка firstInputFile, String secondInputFile, String outputFile)
```


Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | first input file. |
| secondInputFile | java.lang.String | second input file. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
общественное абстрактное логическое значение makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)
```


Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp (новая строка[]
 { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Input Pdf files. |
| outputFile | java.lang.String | Output pdf file path and name. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically. |

**Returns:**
boolean - boolean - True for success, or false.
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
открытый абстрактный логический resizeContents (источник InputStream, назначение OutputStream, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream src = новый FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents (источник, пункт назначения,
 // изменить размер всех страниц документа
 	нулевой,
 	// ширина нового содержимого = 200
 	200,
 	// высота нового содержимого = 300
 	300);
 // остальная часть страницы будет пустой
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
общедоступный абстрактный логический resizeContents (источник строки, пункт назначения строки, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf",
 // изменить размер всех страниц документа
 	нулевой,
 	// ширина нового содержимого = 200
 	200,
 	// высота нового содержимого = 300
 	300);
 // остальная часть страницы будет пустой
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
открытый абстрактный логический resizeContentsPct (источник InputStream, назначение OutputStream, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream src = новый FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct (источник, пункт назначения,
 // изменить размер всех страниц документа
 	нулевой,
 	// ширина нового содержимого = 60% от исходного размера
 	60,
 	// высота нового содержимого = 60% от исходного размера
 	60);
 // Остальная часть страницы будет пустой (поля страницы). Размер слева и справа
 // поля (100% - 60%) / 2 = 20%
 // То же самое для верхнего и нижнего полей.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - True if resize was successful.
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
общедоступный абстрактный логический resizeContentsPct (источник строки, пункт назначения строки, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.resizeContentsPct("input.pdf", "output.pdf",
 // изменить размер всех страниц документа
 	нулевой,
 	// ширина нового содержимого = 60% от исходного размера
 	60,
 	// высота нового содержимого = 60% от исходного размера
 	60);
 // Остальная часть страницы будет пустой (поля страницы). Размер слева и справа
 // поля (100% - 60%) / 2 = 20%
 // То же самое для верхнего и нижнего полей.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - true if resize was successful.
### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public abstract void setAllowConcatenateExceptions (логическое значение)
```


If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.setAllowConcatenateException (истина);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName (строковое значение)
```


Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string value |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public abstract void setCloseConcatenatedStreams (логическое значение)
```


If set to true, streams are closed after operation.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.setCloseConcatenatedStreams (истина);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition (значение int)
```


Sets how content will be stored when result of operation is stored into HttpServletResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ContentDisposition element |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public abstract void setConvertTo (значение PdfFormat)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat element |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public abstract void setCorruptedFileAction (значение int)
```


This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ConcatenateCorruptedFileAction element |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public abstract void setIncrementalUpdates (логическое значение)
```


If true, incremental updates are made during concatenation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public abstract void setKeepFieldsUnique (логическое значение)
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public abstract void setMergeDuplicateLayers (логическое значение)
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public abstract void setMergeDuplicateOutlines (логическое значение)
```


If true, duplicate outlines are merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public abstract void setOwnerPassword (строковое значение)
```


Sets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string value |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public abstract void setPreserveUserRights (логическое значение)
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public abstract void setRemoveSignatures (логическое значение)
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions (значение SaveOptions)
```


Sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions object |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public abstract void setUniqueSuffix (строковое значение)
```


Set format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

--------------------

```
PdfFileEditor ed = новый PdfFileEditor();
 ed.setUniqueSuffix("_%ЧИСЛО%");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string value |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
открытый абстрактный логический splitFromFirst (InputStream inputStream, int location, OutputStream outputStream)
```


Splits from start to specified location,and saves the front part in output Stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.splitFromFirst (исходный поток, 5, исходящий поток);
```

--------------------

The streams are NOT closed after this operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting point. |
| outputStream | java.io.OutputStream | Output file Stream. |

**Returns:**
boolean - True for success, or false.
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
открытый абстрактный логический splitFromFirst (String inputFile, int location, String outputFile)
```


Splits Pdf file from first page to specified location,and saves the front part as a new file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.splitFromFirst("input.pdf", 5, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting point. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
открытый абстрактный ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] количество страниц)
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| numberOfPage | int[][] | The start page and the end page of each document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
открытый абстрактный ByteArrayInputStream[] splitToBulks(String inputFile, int[][] количество страниц)
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file. |
| numberOfPage | int[][] | Array which contains array of double elements, which is start and end pages of document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
открытый абстрактный логический splitToEnd (InputStream inputStream, int location, OutputStream outputStream)
```


Splits from specified location, and saves the rear part as a new file Stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.splitToEnd (исходный поток, 5, исходящий поток);
```

--------------------

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting position. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True for success, or false.
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
открытый абстрактный логический splitToEnd (String inputFile, int location, String outputFile)
```


Splits from location, and saves the rear part as a new file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.splitToEnd("input.pdf", 5, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting position. |
| outputFile | java.lang.String | Output Pdf file path. |

**Returns:**
boolean - True for success, or false.
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
открытый абстрактный ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


Splits the Pdf file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf stream. |

**Returns:**
java.io.ByteArrayInputStream[] - ByteArrayInputStream[] array
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public abstract void splitToPages (InputStream inputStream, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of the soruce document. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number. For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
открытый абстрактный ByteArrayInputStream[] splitToPages (строка inputFile)
```


Splits the PDF file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file name. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a single-page PDF document.
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public abstract void splitToPages (String inputFile, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file name. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number. For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |
