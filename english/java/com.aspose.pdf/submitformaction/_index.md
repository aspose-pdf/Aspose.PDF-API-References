---
title: SubmitFormAction
linktitle: SubmitFormAction
second_title: Aspose.PDF for Java API Reference
description: Class which describes submit-form action.
type: docs
weight: 4690
url: /java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Class which describes submit-form action.

## Fields

| Field | Description |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | If set, any submitted field values representing dates shall be converted to the standard format. |
| [EMBED_FORM](#EMBED_FORM) | If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted. |
| [EXCL_F_KEY](#EXCL_F_KEY) | If set, the submitted FDF shall exclude the F entry. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | If set, it shall include only those markup annotations whose T entry matches the name of the current user. |
| [EXCLUDE](#EXCLUDE) | If clear, the Fields array specifies which fields to include in the submission. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | If set, field names and values shall be submitted in HTML Form format. |
| [GET_METHOD](#GET_METHOD) | If set, field names and values shall be submitted using an HTTP GET request. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | If set, the submitted FDF file shall include the contents of all incremental updates. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data. |
| [SUBMIT_PDF](#SUBMIT_PDF) | If set, the document shall be submitted as PDF, using the MIME content type application/pdf. |
| [XFDF](#XFDF) | If set, field names and values shall be submitted as XFDF. |

## Constructors

| Constructor | Description |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Initializes SubmitFormAction object. |

## Methods

| Method | Description |
| --- | --- |
| [getFlags](#getFlags--) | Gets flagas of submit action |
| [getUrl](#getUrl--) | Destination URL. |
| [setFlags](#setFlags-int-) | Sets flagas of submit action |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | Destination URL. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

If set, any submitted field values representing dates shall be converted to the standard format.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

If set, the submitted FDF shall exclude the F entry.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

If set, it shall include only those markup annotations whose T entry matches the name of the current user.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

If clear, the Fields array specifies which fields to include in the submission.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

If set, field names and values shall be submitted in HTML Form format.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

If set, field names and values shall be submitted using an HTTP GET request.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

If set, the submitted FDF file shall include the contents of all incremental updates.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

If set, the document shall be submitted as PDF, using the MIME content type application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

If set, field names and values shall be submitted as XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Initializes SubmitFormAction object.

### getFlags {#getFlags--}
```
public int getFlags()
```

Gets flagas of submit action

**Returns:**
int value

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

Destination URL.

**Returns:**
FileSpecification value

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Sets flagas of submit action

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
Destination URL.
