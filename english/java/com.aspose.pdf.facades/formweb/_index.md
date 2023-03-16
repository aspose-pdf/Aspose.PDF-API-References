---
title: FormWeb
second_title: Aspose.PDF for Java API Reference
description: Representing Acro form Interface.
type: docs
weight: 26
url: /java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AForm

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IForm](../../com.aspose.pdf.facades/iform)
```
public final class FormWeb extends AForm implements IForm
```

Representing Acro form Interface.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormWeb()](#FormWeb--) | Construtcor of FormWeb without parameters. |
| [FormWeb(IDocument document)](#FormWeb-com.aspose.pdf.IDocument-) | Initializes new  FormWeb  object on base of the  document . |
| [FormWeb(IDocument document, OutputStream destStream)](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initializes new  FormWeb  object on base of the  document . |
| [FormWeb(IDocument document, String destFileName)](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  FormWeb  object on base of the  document . |
| [FormWeb(InputStream srcStream)](#FormWeb-java.io.InputStream-) | Constructor for FormWeb. |
| [FormWeb(InputStream inputStream, HttpServletResponse response)](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | Creates FormWeb which will save result into HttpResponse object. |
| [FormWeb(InputStream srcStream, OutputStream destStream)](#FormWeb-java.io.InputStream-java.io.OutputStream-) | Constructor of FormWeb with two stream parameters. |
| [FormWeb(InputStream srcStream, String destFileName)](#FormWeb-java.io.InputStream-java.lang.String-) | Constructor of FormWeb |
| [FormWeb(String srcFileName)](#FormWeb-java.lang.String-) | Constructor of FormWeb. |
| [FormWeb(String inputFile, HttpServletResponse response)](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | Creates FormWeb which will save result into HttpResponse object. |
| [FormWeb(String srcFileName, OutputStream destStream)](#FormWeb-java.lang.String-java.io.OutputStream-) | Constructor of FormWeb. |
| [FormWeb(String srcFileName, String destFileName)](#FormWeb-java.lang.String-java.lang.String-) | Constructor of FormWeb class. |
## Methods

| Method | Description |
| --- | --- |
| [getResponse()](#getResponse--) | Gets or sets Response object where result of operation will be stored. |
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | Gets or sets Response object where result of operation will be stored. |
| [save()](#save--) | Saves the value of the filled fields and close the opened Pdf document. |
### FormWeb() {#FormWeb--}
```
public FormWeb()
```


Construtcor of FormWeb without parameters.

--------------------

```
FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb();
 FormWeb.setSrcFileName("file.pdf");
```

### FormWeb(IDocument document) {#FormWeb-com.aspose.pdf.IDocument-}
```
public FormWeb(IDocument document)
```


Initializes new  FormWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### FormWeb(IDocument document, OutputStream destStream) {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public FormWeb(IDocument document, OutputStream destStream)
```


Initializes new  FormWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destStream | java.io.OutputStream | Destination stream. |

### FormWeb(IDocument document, String destFileName) {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
public FormWeb(IDocument document, String destFileName)
```


Initializes new  FormWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destFileName | java.lang.String | Path of the destination file. |

### FormWeb(InputStream srcStream) {#FormWeb-java.io.InputStream-}
```
public FormWeb(InputStream srcStream)
```


Constructor for FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("PdfFormWeb.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | source stream. |

### FormWeb(InputStream inputStream, HttpServletResponse response) {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
public FormWeb(InputStream inputStream, HttpServletResponse response)
```


Creates FormWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream containing source document. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse object where result will be saved. |

### FormWeb(InputStream srcStream, OutputStream destStream) {#FormWeb-java.io.InputStream-java.io.OutputStream-}
```
public FormWeb(InputStream srcStream, OutputStream destStream)
```


Constructor of FormWeb with two stream parameters. Specify same source and destination stream for incremental update.

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destStream | java.io.OutputStream | Destination stream. |

### FormWeb(InputStream srcStream, String destFileName) {#FormWeb-java.io.InputStream-java.lang.String-}
```
public FormWeb(InputStream srcStream, String destFileName)
```


Constructor of FormWeb

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("PdfFormWeb.pdf"), "PdfFormWeb_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destFileName | java.lang.String | Destination file path. |

### FormWeb(String srcFileName) {#FormWeb-java.lang.String-}
```
public FormWeb(String srcFileName)
```


Constructor of FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Source file path. |

### FormWeb(String inputFile, HttpServletResponse response) {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
public FormWeb(String inputFile, HttpServletResponse response)
```


Creates FormWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Name of input file. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse object where result will be stored. |

### FormWeb(String srcFileName, OutputStream destStream) {#FormWeb-java.lang.String-java.io.OutputStream-}
```
public FormWeb(String srcFileName, OutputStream destStream)
```


Constructor of FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf", "PdfFormWeb_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Source file path. |
| destStream | java.io.OutputStream | Destination file path. |

### FormWeb(String srcFileName, String destFileName) {#FormWeb-java.lang.String-java.lang.String-}
```
public FormWeb(String srcFileName, String destFileName)
```


Constructor of FormWeb class. Specify same source file name and destination file name to perFormWeb incremental update.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf", "PdfFormWeb_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Path of the source file. |
| destFileName | java.lang.String | Path of the destination file. |

### getResponse() {#getResponse--}
```
public HttpServletResponse getResponse()
```


Gets or sets Response object where result of operation will be stored.

**Returns:**
javax.servlet.http.HttpServletResponse - HttpServletResponse object
### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse value)
```


Gets or sets Response object where result of operation will be stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | HttpServletResponse object |

### save() {#save--}
```
public void save()
```


Saves the value of the filled fields and close the opened Pdf document.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
 form.fillField("textField", "new value");
 form.save();
```

