---
title: Permissions
second_title: Aspose.PDF for Java API Reference
description: Binary Flag This enum represents user's permissions for a pdf.
type: docs
weight: 3830
url: /java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Binary Flag This enum represents user's permissions for a pdf.

## Fields

| Field | Description |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if {@code ModifyContent} is clear. |
| [ExtractContent](#ExtractContent) | (Security handlers of revision 2) Copy or otherwise extract text and graphics from the document, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes). (Security handlers of revision 3 or greater) Copy or otherwise extract text and graphics from the document by operations other than that controlled by {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| [FillForm](#FillForm) | (Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if {@code ModifyTextAnnotations} is clear. |
| [ModifyContent](#ModifyContent) | Modify the contents of the document by operations other than those controlled by {@code ModifyTextAnnotations}, {@code FillForm}, and 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Add or modify text annotations, fill in interactive form fields, and, if {@code ModifyContent} is also set, create or modify interactive form fields (including signature fields). |
| [PrintDocument](#PrintDocument) | (Security handlers of revision 2) Print the document. (Security handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether {@code PrintingQuality} is also set). |
| [PrintingQuality](#PrintingQuality) | (Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if {@code ModifyContent} is clear.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Security handlers of revision 2) Copy or otherwise extract text and graphics from the document, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes). (Security handlers of revision 3 or greater) Copy or otherwise extract text and graphics from the document by operations other than that controlled by {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if {@code ModifyTextAnnotations} is clear.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Modify the contents of the document by operations other than those controlled by {@code ModifyTextAnnotations}, {@code FillForm}, and 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Add or modify text annotations, fill in interactive form fields, and, if {@code ModifyContent} is also set, create or modify interactive form fields (including signature fields).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Security handlers of revision 2) Print the document. (Security handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether {@code PrintingQuality} is also set).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality.
