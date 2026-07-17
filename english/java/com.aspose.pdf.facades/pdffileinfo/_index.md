---
title: PdfFileInfo
linktitle: PdfFileInfo
second_title: Aspose.PDF for Java API Reference
description: Represents a class for accessing meta information of PDF document.
type: docs
weight: 490
url: /java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Represents a class for accessing meta information of PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values. |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [clearInfo](#clearInfo--) | Clears all meta information of PDF document. |
| [close](#close--) | Closes all resources used by this document. |
| [dispose](#dispose--) | Closes all resources used by this instance. This method is obsolete, use close() instead. |
| [getAuthor](#getAuthor--) | Gets the Author information of PDF document. |
| [getCreationDate](#getCreationDate--) | Gets the CreationDate information of PDF document. |
| [getCreator](#getCreator--) | Gets the Creator information of PDF document. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Gets the PDF document privilege settings. |
| [getHeader](#getHeader--) | <p> Gets the customized information of PDF document. </p> |
| [getInputFile](#getInputFile--) | Gets the input file. |
| [getInputStream](#getInputStream--) | Gets the input stream. |
| [getKeywords](#getKeywords--) | Gets the Keywords information of PDF document. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string. |
| [getModDate](#getModDate--) | Gets the ModDate date information of PDF document. |
| [getNumberOfPages](#getNumberOfPages--) | Gets the number of document pages. |
| [getPageHeight](#getPageHeight-int-) | Gets the height of the specified page. |
| [getPageRotation](#getPageRotation-int-) | Gets the rotation of the specified page. |
| [getPageWidth](#getPageWidth-int-) | Gets the width of the specified page. |
| [getPageXOffset](#getPageXOffset-int-) | Gets the horizontal offset of the specified page display area. |
| [getPageYOffset](#getPageYOffset-int-) | Gets the vertical offset of the specified page display area. |
| [getPasswordType](#getPasswordType--) | Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in {@code PasswordType}. Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password. |
| [getPdfVersion](#getPdfVersion--) | Gets the version info of PDF document. |
| [getProducer](#getProducer--) | Gets the Producer information of PDF document. |
| [getSubject](#getSubject--) | Gets the Subject information of PDF document. |
| [getTitle](#getTitle--) | Gets the Title information of PDF document. |
| [getUseStrictValidation](#getUseStrictValidation--) | Uses strict validation rules via using {@code IsPdfFile}({@link #isPdfFile}) property. |
| [hasCollection](#hasCollection--) | Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it. |
| [hasEditPassword](#hasEditPassword--) | Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read only if valid password was provided in {@code PdfFileInfo} constructor. In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Returns true if password is needed to open password protected pdf document. |
| [isEncrypted](#isEncrypted--) | Checks whether the PDF document is encrypted. |
| [isPdfFile](#isPdfFile--) | Checks whether the source input is a valid PDF file. |
| [save](#save-java.io.OutputStream-) | Saves the PDF document to the specified file. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Save updated PDF document into specified stream. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Save updated PDF document into specified file. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Changes the properties specified explicitly by setting file information, other properties remain. |
| [setAuthor](#setAuthor-java.lang.String-) | Sets the Author information of PDF document. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Sets the CreationDate information of PDF document. |
| [setCreator](#setCreator-java.lang.String-) | Sets the Creator information of PDF document. |
| [setHeader](#setHeader-java.util.Map-) | Sets the customized information of PDF document. |
| [setInputFile](#setInputFile-java.lang.String-) | Sets the input file. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Sets the input stream. |
| [setKeywords](#setKeywords-java.lang.String-) | Sets the Keywords information of PDF document. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Sets customized information of PDF document. |
| [setModDate](#setModDate-java.lang.String-) | Sets the ModDate date information of PDF document. |
| [setSubject](#setSubject-java.lang.String-) | Sets the Subject information of PDF document. |
| [setTitle](#setTitle-java.lang.String-) | Sets the Title information of PDF document. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Uses strict validation rules via using {@code IsPdfFile}({@link #isPdfFile}) property. |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes a new instance of the com.aspose.pdf.facades.PdfFileInfo class with default values.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initializes the facade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initializes the facade.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Clears all meta information of PDF document.

### close {#close--}
```
public void close()
```

Closes all resources used by this document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Closes all resources used by this instance. This method is obsolete, use close() instead.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Gets the Author information of PDF document.

**Returns:**
String value

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Gets the CreationDate information of PDF document.

**Returns:**
String value

### getCreator {#getCreator--}
```
public String getCreator()
```

Gets the Creator information of PDF document.

**Returns:**
String value

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Gets the PDF document privilege settings.

**Returns:**
The PDF document privilege settings.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Gets the customized information of PDF document. </p>

**Returns:**
{@code Map<String, String>} object

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Gets the input file.

**Returns:**
String value

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Gets the input stream.

**Returns:**
InputStream object

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Gets the Keywords information of PDF document.

**Returns:**
String value

### getMetaInfo {#getMetaInfo-java.lang.String-}
Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string.

### getModDate {#getModDate--}
```
public String getModDate()
```

Gets the ModDate date information of PDF document.

**Returns:**
String value

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Gets the number of document pages.

**Returns:**
int value

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Gets the height of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum |  | Page number. |

**Returns:**
The height of the page.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Gets the rotation of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum |  | Page number. |

**Returns:**
The rotation of the page. The value may be 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Gets the width of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum |  | Page number. |

**Returns:**
The width of the page.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Gets the horizontal offset of the specified page display area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum |  | Page number. |

**Returns:**
The horizontal offset from the left side of the page.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Gets the vertical offset of the specified page display area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNum |  | Page number. |

**Returns:**
The vertical offset of the page display area.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in {@code PasswordType}. Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password.

**Returns:**
PasswordType element @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Gets the version info of PDF document.

**Returns:**
The version string.

### getProducer {#getProducer--}
```
public String getProducer()
```

Gets the Producer information of PDF document.

**Returns:**
String value

### getSubject {#getSubject--}
```
public String getSubject()
```

Gets the Subject information of PDF document.

**Returns:**
String value

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets the Title information of PDF document.

**Returns:**
String value

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Uses strict validation rules via using {@code IsPdfFile}({@link #isPdfFile}) property.

**Returns:**
boolean value

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it.

**Returns:**
boolean value

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read only if valid password was provided in {@code PdfFileInfo} constructor. In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with {@code InvalidPasswordException}.

**Returns:**
boolean value

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Returns true if password is needed to open password protected pdf document.

**Returns:**
boolean value

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Checks whether the PDF document is encrypted.

**Returns:**
boolean value

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Checks whether the source input is a valid PDF file.

**Returns:**
boolean value

### save {#save-java.io.OutputStream-}
Saves the PDF document to the specified file.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Save updated PDF document into specified stream.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Save updated PDF document into specified file.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Changes the properties specified explicitly by setting file information, other properties remain.

### setAuthor {#setAuthor-java.lang.String-}
Sets the Author information of PDF document.

### setCreationDate {#setCreationDate-java.lang.String-}
Sets the CreationDate information of PDF document.

### setCreator {#setCreator-java.lang.String-}
Sets the Creator information of PDF document.

### setHeader {#setHeader-java.util.Map-}
Sets the customized information of PDF document.

### setInputFile {#setInputFile-java.lang.String-}
Sets the input file.

### setInputStream {#setInputStream-java.io.InputStream-}
Sets the input stream.

### setKeywords {#setKeywords-java.lang.String-}
Sets the Keywords information of PDF document.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Sets customized information of PDF document.

### setModDate {#setModDate-java.lang.String-}
Sets the ModDate date information of PDF document.

### setSubject {#setSubject-java.lang.String-}
Sets the Subject information of PDF document.

### setTitle {#setTitle-java.lang.String-}
Sets the Title information of PDF document.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Uses strict validation rules via using {@code IsPdfFile}({@link #isPdfFile}) property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
