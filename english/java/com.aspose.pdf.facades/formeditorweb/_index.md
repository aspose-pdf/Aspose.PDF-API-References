---
title: FormEditorWeb
second_title: Aspose.PDF for Java API Reference
description: Class for editing forms ading/deleting field etc
type: docs
weight: 27
url: /java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AFormEditor

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IFormEditor](../../com.aspose.pdf.facades/iformeditor)
```
public final class FormEditorWeb extends AFormEditor implements IFormEditor
```

Class for editing forms (ading/deleting field etc)
## Constructors

| Constructor | Description |
| --- | --- |
| [FormEditorWeb()](#FormEditorWeb--) | Constructor for FormEditorWeb. |
| [FormEditorWeb(IDocument document)](#FormEditorWeb-com.aspose.pdf.IDocument-) | Initializes new  FormEditorWeb  object on base of the  document . |
| [FormEditorWeb(IDocument document, OutputStream destStream)](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initializes new  FormEditorWeb  object on base of the  document . |
| [FormEditorWeb(IDocument document, String destFileName)](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  FormEditorWeb  object on base of the  document . |
| [FormEditorWeb(InputStream inputStream, HttpServletResponse response)](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | Creates FormEditorWeb which will save result into HttpResponse object. |
| [FormEditorWeb(InputStream srcStream, OutputStream destStream)](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | Constructor for FormEditorWeb. |
| [FormEditorWeb(String inputFile, HttpServletResponse response)](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | Creates FormEditorWeb which will save result into HttpResponse object. |
| [FormEditorWeb(String srcFileName, String destFileName)](#FormEditorWeb-java.lang.String-java.lang.String-) | Constructor for FormEditorWeb |
## Methods

| Method | Description |
| --- | --- |
| [getResponse()](#getResponse--) | Gets Response object where result of operation will be stored. |
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | Sets Response object where result of operation will be stored. |
| [save()](#save--) | Saves changes into destination file. |
### FormEditorWeb() {#FormEditorWeb--}
```
public FormEditorWeb()
```


Constructor for FormEditorWeb.

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb();
```

### FormEditorWeb(IDocument document) {#FormEditorWeb-com.aspose.pdf.IDocument-}
```
public FormEditorWeb(IDocument document)
```


Initializes new  FormEditorWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### FormEditorWeb(IDocument document, OutputStream destStream) {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public FormEditorWeb(IDocument document, OutputStream destStream)
```


Initializes new  FormEditorWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destStream | java.io.OutputStream | Destination stream. |

### FormEditorWeb(IDocument document, String destFileName) {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
public FormEditorWeb(IDocument document, String destFileName)
```


Initializes new  FormEditorWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destFileName | java.lang.String | Path of the destination file. |

### FormEditorWeb(InputStream inputStream, HttpServletResponse response) {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
public FormEditorWeb(InputStream inputStream, HttpServletResponse response)
```


Creates FormEditorWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source stream. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse object where result will be saved. |

### FormEditorWeb(InputStream srcStream, OutputStream destStream) {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
```
public FormEditorWeb(InputStream srcStream, OutputStream destStream)
```


Constructor for FormEditorWeb.

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destStream | java.io.OutputStream | Destination stream. |

### FormEditorWeb(String inputFile, HttpServletResponse response) {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
public FormEditorWeb(String inputFile, HttpServletResponse response)
```


Creates FormEditorWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file name. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse objects where result be saved. |

### FormEditorWeb(String srcFileName, String destFileName) {#FormEditorWeb-java.lang.String-java.lang.String-}
```
public FormEditorWeb(String srcFileName, String destFileName)
```


Constructor for FormEditorWeb

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb("InFile.pdf", "OutFile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Name of source file. |
| destFileName | java.lang.String | Name of destination file. |

### getResponse() {#getResponse--}
```
public HttpServletResponse getResponse()
```


Gets Response object where result of operation will be stored.

**Returns:**
javax.servlet.http.HttpServletResponse - HttpServletResponse object
### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse value)
```


Sets Response object where result of operation will be stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | HttpServletResponse object |

### save() {#save--}
```
public void save()
```


Saves changes into destination file.

