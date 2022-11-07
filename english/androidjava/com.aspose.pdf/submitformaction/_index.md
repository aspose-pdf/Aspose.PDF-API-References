---
title: SubmitFormAction
second_title: Aspose.PDF for Java API Reference
description: Class which describes submit-form action.
type: docs
weight: 278
url: /java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class SubmitFormAction extends PdfAction
```

Class which describes submit-form action.
## Constructors

| Constructor | Description |
| --- | --- |
| [SubmitFormAction()](#SubmitFormAction--) |  |
## Fields

| Field | Description |
| --- | --- |
| [EXCLUDE](#EXCLUDE) | If clear, the Fields array specifies which fields to include in the submission. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE-NO-VALUE-FIELDS) | If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted. |
| [EXPORT_FORMAT](#EXPORT-FORMAT) | If set, field names and values shall be submitted in HTML Form format. |
| [GET_METHOD](#GET-METHOD) | If set, field names and values shall be submitted using an HTTP GET request. |
| [SUBMIT_COORDINATES](#SUBMIT-COORDINATES) | If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data. |
| [XFDF](#XFDF) | If set, field names and values shall be submitted as XFDF. |
| [INCLUDE_APPEND_SAVES](#INCLUDE-APPEND-SAVES) | If set, the submitted FDF file shall include the contents of all incremental updates. |
| [INCLUDE_ANNOTATIONS](#INCLUDE-ANNOTATIONS) | If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document. |
| [SUBMIT_PDF](#SUBMIT-PDF) | If set, the document shall be submitted as PDF, using the MIME content type application/pdf. |
| [CANONICAL_FORMAT](#CANONICAL-FORMAT) | If set, any submitted field values representing dates shall be converted to the standard format. |
| [EXCL_NON_USER_ANNOTS](#EXCL-NON-USER-ANNOTS) | If set, it shall include only those markup annotations whose T entry matches the name of the current user. |
| [EXCL_F_KEY](#EXCL-F-KEY) | If set, the submitted FDF shall exclude the F entry. |
| [EMBED_FORM](#EMBED-FORM) | If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted. |
## Methods

| Method | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Gets or sets flagas of submit action |
| [setFlags(int value)](#setFlags-int-) |  |
| [getUrl()](#getUrl--) |  |
| [setUrl(FileSpecification value)](#setUrl-com.aspose.pdf.FileSpecification-) |  |
### SubmitFormAction() {#SubmitFormAction--}
```
public SubmitFormAction()
```


### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```


If clear, the Fields array specifies which fields to include in the submission.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE-NO-VALUE-FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```


If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted.

### EXPORT_FORMAT {#EXPORT-FORMAT}
```
public static final int EXPORT_FORMAT
```


If set, field names and values shall be submitted in HTML Form format.

### GET_METHOD {#GET-METHOD}
```
public static final int GET_METHOD
```


If set, field names and values shall be submitted using an HTTP GET request.

### SUBMIT_COORDINATES {#SUBMIT-COORDINATES}
```
public static final int SUBMIT_COORDINATES
```


If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data.

### XFDF {#XFDF}
```
public static final int XFDF
```


If set, field names and values shall be submitted as XFDF.

### INCLUDE_APPEND_SAVES {#INCLUDE-APPEND-SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```


If set, the submitted FDF file shall include the contents of all incremental updates.

### INCLUDE_ANNOTATIONS {#INCLUDE-ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```


If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document.

### SUBMIT_PDF {#SUBMIT-PDF}
```
public static final int SUBMIT_PDF
```


If set, the document shall be submitted as PDF, using the MIME content type application/pdf.

### CANONICAL_FORMAT {#CANONICAL-FORMAT}
```
public static final int CANONICAL_FORMAT
```


If set, any submitted field values representing dates shall be converted to the standard format.

### EXCL_NON_USER_ANNOTS {#EXCL-NON-USER-ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```


If set, it shall include only those markup annotations whose T entry matches the name of the current user.

### EXCL_F_KEY {#EXCL-F-KEY}
```
public static final int EXCL_F_KEY
```


If set, the submitted FDF shall exclude the F entry.

### EMBED_FORM {#EMBED-FORM}
```
public static final int EMBED_FORM
```


If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted.

### getFlags() {#getFlags--}
```
public int getFlags()
```


Gets or sets flagas of submit action

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUrl() {#getUrl--}
```
public FileSpecification getUrl()
```




**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification)
### setUrl(FileSpecification value) {#setUrl-com.aspose.pdf.FileSpecification-}
```
public void setUrl(FileSpecification value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) |  |

