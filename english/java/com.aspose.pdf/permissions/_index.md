---
title: Permissions
second_title: Aspose.PDF for Java API Reference
description: This enum represents users permissions for a pdf.
type: docs
weight: 282
url: /java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Permissions extends System.Enum
```

This enum represents user's permissions for a pdf.
## Fields

| Field | Description |
| --- | --- |
| [PrintDocument](#PrintDocument) | (Security handlers of revision 2) Print the document. |
| [ModifyContent](#ModifyContent) | Modify the contents of the document by operations other than those controlled by  ModifyTextAnnotations ,  FillForm , and 11. |
| [ExtractContent](#ExtractContent) | (Security handlers of revision 2) Copy or otherwise extract text and graphics from the document, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Add or modify text annotations, fill in interactive form fields, and, if  ModifyContent  is also set, create or modify interactive form fields (including signature fields). |
| [FillForm](#FillForm) | (Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if  ModifyTextAnnotations  is clear. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| [AssembleDocument](#AssembleDocument) | (Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if  ModifyContent  is clear. |
| [PrintingQuality](#PrintingQuality) | (Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. |
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


(Security handlers of revision 2) Print the document. (Security handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether  PrintingQuality  is also set).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Modify the contents of the document by operations other than those controlled by  ModifyTextAnnotations ,  FillForm , and 11.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


(Security handlers of revision 2) Copy or otherwise extract text and graphics from the document, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes). (Security handlers of revision 3 or greater) Copy or otherwise extract text and graphics from the document by operations other than that controlled by  ExtractContentWithDisabilities .

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Add or modify text annotations, fill in interactive form fields, and, if  ModifyContent  is also set, create or modify interactive form fields (including signature fields).

### FillForm {#FillForm}
```
public static final int FillForm
```


(Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if  ModifyTextAnnotations  is clear.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


(Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes).

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


(Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if  ModifyContent  is clear.

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


(Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality.

