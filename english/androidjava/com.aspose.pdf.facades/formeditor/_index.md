---
title: FormEditor
second_title: Aspose.PDF for Java API Reference
description: 
type: docs
weight: 25
url: /java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AFormEditor

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IFormEditor](../../com.aspose.pdf.facades/iformeditor)
```
public final class FormEditor extends AFormEditor implements IFormEditor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FormEditor()](#FormEditor--) | Constructor for FormEditor. |
| [FormEditor(IDocument document)](#FormEditor-com.aspose.pdf.IDocument-) | Initializes new  FormEditor  object on base of the  document  . |
| [FormEditor(IDocument document, OutputStream destStream)](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initializes new  FormEditor  object on base of the  document  . |
| [FormEditor(IDocument document, String destFileName)](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  FormEditor  object on base of the  document  . |
| [FormEditor(InputStream srcStream, OutputStream destStream)](#FormEditor-java.io.InputStream-java.io.OutputStream-) | Constructor for FormEditor. |
| [FormEditor(String srcFileName, String destFileName)](#FormEditor-java.lang.String-java.lang.String-) | Constructor for FormEditor |
### FormEditor() {#FormEditor--}
```
public FormEditor()
```


Constructor for FormEditor.

--------------------

> ```
> FormEditor formEditor = new FormEditor();
> ```

### FormEditor(IDocument document) {#FormEditor-com.aspose.pdf.IDocument-}
```
public FormEditor(IDocument document)
```


Initializes new  FormEditor  object on base of the  document  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### FormEditor(IDocument document, OutputStream destStream) {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public FormEditor(IDocument document, OutputStream destStream)
```


Initializes new  FormEditor  object on base of the  document  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destStream | java.io.OutputStream | Destination stream. |

### FormEditor(IDocument document, String destFileName) {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
```
public FormEditor(IDocument document, String destFileName)
```


Initializes new  FormEditor  object on base of the  document  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destFileName | java.lang.String | Path of the destination file. |

### FormEditor(InputStream srcStream, OutputStream destStream) {#FormEditor-java.io.InputStream-java.io.OutputStream-}
```
public FormEditor(InputStream srcStream, OutputStream destStream)
```


Constructor for FormEditor.

--------------------

> ```
> FormEditor formEditor = new FormEditor(
>    new FileInputStream(new FileInputStream("InFile.pdf", FileMode.Open, FileAccess.Read), 
>    new FileInputStream("OutFile.pdf", FileMode.Create, FileAccess.Write));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destStream | java.io.OutputStream | Destination stream. |

### FormEditor(String srcFileName, String destFileName) {#FormEditor-java.lang.String-java.lang.String-}
```
public FormEditor(String srcFileName, String destFileName)
```


Constructor for FormEditor

--------------------

> ```
> FormEditor formEditor = new FormEditor("InFile.pdf", "OutFile.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Name of source file. |
| destFileName | java.lang.String | Name of destination file. |

