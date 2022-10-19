---
title: PdfFileInfo
second_title: Aspose.PDF for Java API Reference
description: Represents a class for accessing meta information of PDF document.
type: docs
weight: 41
url: /java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileInfo extends SaveableFacade
```

Represents a class for accessing meta information of PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileInfo()](#PdfFileInfo--) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo(InputStream inputStream)](#PdfFileInfo-java.io.InputStream-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class. |
| [PdfFileInfo(InputStream inputStream, String password)](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class. |
| [PdfFileInfo(String inputFile)](#PdfFileInfo-java.lang.String-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class. |
| [PdfFileInfo(String inputFile, String password)](#PdfFileInfo-java.lang.String-java.lang.String-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class. |
| [PdfFileInfo(IDocument document)](#PdfFileInfo-com.aspose.pdf.IDocument-) | Initializes new  PdfFileInfo  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [getAuthor()](#getAuthor--) | Gets the Author information of PDF document. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the Author information of PDF document. |
| [isEncrypted()](#isEncrypted--) | Checks whether the PDF document is encrypted. |
| [isPdfFile()](#isPdfFile--) | Checks whether the source input is a valid PDF file. |
| [getUseStrictValidation()](#getUseStrictValidation--) | Uses strict validation rules via using  IsPdfFile (\#isPdfFile\#isPdfFile) property. |
| [setUseStrictValidation(boolean value)](#setUseStrictValidation-boolean-) | Uses strict validation rules via using  IsPdfFile (\#isPdfFile\#isPdfFile) property. |
| [getCreationDate()](#getCreationDate--) | Gets the CreationDate information of PDF document. |
| [setCreationDate(String value)](#setCreationDate-java.lang.String-) | Sets the CreationDate information of PDF document. |
| [getCreator()](#getCreator--) | Gets the Creator information of PDF document. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Sets the Creator information of PDF document. |
| [hasCollection()](#hasCollection--) | Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it. |
| [getHeader()](#getHeader--) | Gets the customized information of PDF document. |
| [setHeader(Map<String,String> value)](#setHeader-java.util.Map-java.lang.String-java.lang.String--) | Sets the customized information of PDF document. |
| [getInputFile()](#getInputFile--) | Gets the input file. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Sets the input file. |
| [getInputStream()](#getInputStream--) | Gets the input stream. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Sets the input stream. |
| [getKeywords()](#getKeywords--) | Gets the Keywords information of PDF document. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the Keywords information of PDF document. |
| [getModDate()](#getModDate--) | Gets the ModDate date information of PDF document. |
| [setModDate(String value)](#setModDate-java.lang.String-) | Sets the ModDate date information of PDF document. |
| [getNumberOfPages()](#getNumberOfPages--) | Gets the number of document pages. |
| [getProducer()](#getProducer--) | Gets the Producer information of PDF document. |
| [getSubject()](#getSubject--) | Gets the Subject information of PDF document. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the Subject information of PDF document. |
| [getTitle()](#getTitle--) | Gets the Title information of PDF document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the Title information of PDF document. |
| [clearInfo()](#clearInfo--) | Clears all meta information of PDF document. |
| [getDocumentPrivilege()](#getDocumentPrivilege--) | Gets the PDF document privilege settings. |
| [getMetaInfo(String name)](#getMetaInfo-java.lang.String-) | Gets customized information of PDF document with property name. |
| [getPageHeight(int pageNum)](#getPageHeight-int-) | Gets the height of the specified page. |
| [getPageRotation(int pageNum)](#getPageRotation-int-) | Gets the rotation of the specified page. |
| [getPageWidth(int pageNum)](#getPageWidth-int-) | Gets the width of the specified page. |
| [getPageXOffset(int pageNum)](#getPageXOffset-int-) | Gets the horizontal offset of the specified page display area. |
| [getPageYOffset(int pageNum)](#getPageYOffset-int-) | Gets the vertical offset of the specified page display area. |
| [getPdfVersion()](#getPdfVersion--) | Gets the version info of PDF document. |
| [saveNewInfo(OutputStream outputStream)](#saveNewInfo-java.io.OutputStream-) | Save updated PDF document into specified stream. |
| [saveNewInfo(String outputFile)](#saveNewInfo-java.lang.String-) | Save updated PDF document into specified file. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves the PDF document to the specified file. |
| [setMetaInfo(String name, String value)](#setMetaInfo-java.lang.String-java.lang.String-) | Sets customized information of PDF document. |
| [saveNewInfoWithXmp(String outputFileName)](#saveNewInfoWithXmp-java.lang.String-) | Changes the properties specified explicitly by setting file information, other properties remain. |
| [getPasswordType()](#getPasswordType--) | Returns the type of password which was passed for creating PdfFileInfo instance. |
| [hasOpenPassword()](#hasOpenPassword--) | Returns true if password is needed to open password protected pdf document. |
| [hasEditPassword()](#hasEditPassword--) | Returns true if password is needed to modify permissions or document security property. |
| [close()](#close--) | Closes all resources used by this document. |
| [dispose()](#dispose--) | Closes all resources used by this instance. |
### PdfFileInfo() {#PdfFileInfo--}
```
public PdfFileInfo()
```


Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo(InputStream inputStream) {#PdfFileInfo-java.io.InputStream-}
```
public PdfFileInfo(InputStream inputStream)
```


Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream where input file is placed. |

### PdfFileInfo(InputStream inputStream, String password) {#PdfFileInfo-java.io.InputStream-java.lang.String-}
```
public PdfFileInfo(InputStream inputStream, String password)
```


Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream where input file is placed. |
| password | java.lang.String | Password for access to file. |

### PdfFileInfo(String inputFile) {#PdfFileInfo-java.lang.String-}
```
public PdfFileInfo(String inputFile)
```


Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Name of file containing input file. |

### PdfFileInfo(String inputFile, String password) {#PdfFileInfo-java.lang.String-java.lang.String-}
```
public PdfFileInfo(String inputFile, String password)
```


Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Name of file containing input file. |
| password | java.lang.String | Password for access to file. |

### PdfFileInfo(IDocument document) {#PdfFileInfo-com.aspose.pdf.IDocument-}
```
public PdfFileInfo(IDocument document)
```


Initializes new  PdfFileInfo  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets the Author information of PDF document.

**Returns:**
java.lang.String - String value
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Sets the Author information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Checks whether the PDF document is encrypted.

**Returns:**
boolean - boolean value
### isPdfFile() {#isPdfFile--}
```
public boolean isPdfFile()
```


Checks whether the source input is a valid PDF file.

**Returns:**
boolean - boolean value
### getUseStrictValidation() {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```


Uses strict validation rules via using  IsPdfFile (\#isPdfFile\#isPdfFile) property.

**Returns:**
boolean - boolean value
### setUseStrictValidation(boolean value) {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```


Uses strict validation rules via using  IsPdfFile (\#isPdfFile\#isPdfFile) property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getCreationDate() {#getCreationDate--}
```
public String getCreationDate()
```


Gets the CreationDate information of PDF document.

**Returns:**
java.lang.String - String value
### setCreationDate(String value) {#setCreationDate-java.lang.String-}
```
public void setCreationDate(String value)
```


Sets the CreationDate information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getCreator() {#getCreator--}
```
public String getCreator()
```


Gets the Creator information of PDF document.

**Returns:**
java.lang.String - String value
### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


Sets the Creator information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### hasCollection() {#hasCollection--}
```
public boolean hasCollection()
```


Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it.

**Returns:**
boolean - boolean value
### getHeader() {#getHeader--}
```
public Map<String,String> getHeader()
```


Gets the customized information of PDF document.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> -  Map  object
### setHeader(Map<String,String> value) {#setHeader-java.util.Map-java.lang.String-java.lang.String--}
```
public void setHeader(Map<String,String> value)
```


Sets the customized information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Map<java.lang.String,java.lang.String> |  Map  object |

### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


Gets the input file.

**Returns:**
java.lang.String - String value
### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


Sets the input file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


Gets the input stream.

**Returns:**
java.io.InputStream - InputStream object
### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Sets the input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Gets the Keywords information of PDF document.

**Returns:**
java.lang.String - String value
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Sets the Keywords information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getModDate() {#getModDate--}
```
public String getModDate()
```


Gets the ModDate date information of PDF document.

**Returns:**
java.lang.String - String value
### setModDate(String value) {#setModDate-java.lang.String-}
```
public void setModDate(String value)
```


Sets the ModDate date information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getNumberOfPages() {#getNumberOfPages--}
```
public int getNumberOfPages()
```


Gets the number of document pages.

**Returns:**
int - int value
### getProducer() {#getProducer--}
```
public String getProducer()
```


Gets the Producer information of PDF document.

**Returns:**
java.lang.String - String value
### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets the Subject information of PDF document.

**Returns:**
java.lang.String - String value
### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets the Subject information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the Title information of PDF document.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the Title information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### clearInfo() {#clearInfo--}
```
public void clearInfo()
```


Clears all meta information of PDF document.

### getDocumentPrivilege() {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```


Gets the PDF document privilege settings.

**Returns:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - The PDF document privilege settings.
### getMetaInfo(String name) {#getMetaInfo-java.lang.String-}
```
public String getMetaInfo(String name)
```


Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Custom meta property key. |

**Returns:**
java.lang.String - Custom meta property value.
### getPageHeight(int pageNum) {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```


Gets the height of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum | int | Page number. |

**Returns:**
float - The height of the page.
### getPageRotation(int pageNum) {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```


Gets the rotation of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum | int | Page number. |

**Returns:**
int - The rotation of the page. The value may be 0,90,180,270.
### getPageWidth(int pageNum) {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```


Gets the width of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum | int | Page number. |

**Returns:**
float - The width of the page.
### getPageXOffset(int pageNum) {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```


Gets the horizontal offset of the specified page display area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum | int | Page number. |

**Returns:**
float - The horizontal offset from the left side of the page.
### getPageYOffset(int pageNum) {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```


Gets the vertical offset of the specified page display area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum | int | Page number. |

**Returns:**
float - The vertical offset of the page display area.
### getPdfVersion() {#getPdfVersion--}
```
public String getPdfVersion()
```


Gets the version info of PDF document.

**Returns:**
java.lang.String - The version string.
### saveNewInfo(OutputStream outputStream) {#saveNewInfo-java.io.OutputStream-}
```
public boolean saveNewInfo(OutputStream outputStream)
```


Save updated PDF document into specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Output stream. |

**Returns:**
boolean - True if success otherwise is false.
### saveNewInfo(String outputFile) {#saveNewInfo-java.lang.String-}
```
public boolean saveNewInfo(String outputFile)
```


Save updated PDF document into specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | Output file. |

**Returns:**
boolean - True if success otherwise is false.
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Saves the PDF document to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | The destination stream. |

### setMetaInfo(String name, String value) {#setMetaInfo-java.lang.String-java.lang.String-}
```
public void setMetaInfo(String name, String value)
```


Sets customized information of PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Custom meta property key. |
| value | java.lang.String | Custom meta property value. |

### saveNewInfoWithXmp(String outputFileName) {#saveNewInfoWithXmp-java.lang.String-}
```
public boolean saveNewInfoWithXmp(String outputFileName)
```


Changes the properties specified explicitly by setting file information, other properties remain.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Output file. |

**Returns:**
boolean - True for success, or false.
### getPasswordType() {#getPasswordType--}
```
public int getPasswordType()
```


Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in  PasswordType . Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password.

**Returns:**
int - PasswordType element
### hasOpenPassword() {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```


Returns true if password is needed to open password protected pdf document.

**Returns:**
boolean - boolean value
### hasEditPassword() {#hasEditPassword--}
```
public boolean hasEditPassword()
```


Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read only if valid password was provided in  PdfFileInfo  constructor. In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with  InvalidPasswordException .

**Returns:**
boolean - boolean value
### close() {#close--}
```
public void close()
```


Closes all resources used by this document.

### dispose() {#dispose--}
```
public void dispose()
```


Closes all resources used by this instance.

This method is obsolete, use close() instead.

