---
title: SubmitFormAction
second_title: Aspose.PDF for Java API Reference
description: Class which describes submit-form action.
type: docs
weight: 342
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
| [SubmitFormAction()](#SubmitFormAction--) | Initializes SubmitFormAction object. |
## Fields

| Field | Description |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL-FORMAT) | If set, any submitted field values representing dates shall be converted to the standard format. |
| [EMBED_FORM](#EMBED-FORM) | If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted. |
| [EXCLUDE](#EXCLUDE) | If clear, the Fields array specifies which fields to include in the submission. |
| [EXCL_F_KEY](#EXCL-F-KEY) | If set, the submitted FDF shall exclude the F entry. |
| [EXCL_NON_USER_ANNOTS](#EXCL-NON-USER-ANNOTS) | If set, it shall include only those markup annotations whose T entry matches the name of the current user. |
| [EXPORT_FORMAT](#EXPORT-FORMAT) | If set, field names and values shall be submitted in HTML Form format. |
| [GET_METHOD](#GET-METHOD) | If set, field names and values shall be submitted using an HTTP GET request. |
| [INCLUDE_ANNOTATIONS](#INCLUDE-ANNOTATIONS) | If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document. |
| [INCLUDE_APPEND_SAVES](#INCLUDE-APPEND-SAVES) | If set, the submitted FDF file shall include the contents of all incremental updates. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE-NO-VALUE-FIELDS) | If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted. |
| [SUBMIT_COORDINATES](#SUBMIT-COORDINATES) | If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data. |
| [SUBMIT_PDF](#SUBMIT-PDF) | If set, the document shall be submitted as PDF, using the MIME content type application/pdf. |
| [XFDF](#XFDF) | If set, field names and values shall be submitted as XFDF. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | Gets flagas of submit action |
| [getNext()](#getNext--) | Next actions in sequence. |
| [getUrl()](#getUrl--) | Destination URL. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFlags(int value)](#setFlags-int-) | Sets flagas of submit action |
| [setUrl(FileSpecification value)](#setUrl-com.aspose.pdf.FileSpecification-) | Destination URL. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubmitFormAction() {#SubmitFormAction--}
```
public SubmitFormAction()
```


Initializes SubmitFormAction object.

### CANONICAL_FORMAT {#CANONICAL-FORMAT}
```
public static final int CANONICAL_FORMAT
```


If set, any submitted field values representing dates shall be converted to the standard format.

### EMBED_FORM {#EMBED-FORM}
```
public static final int EMBED_FORM
```


If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```


If clear, the Fields array specifies which fields to include in the submission.

### EXCL_F_KEY {#EXCL-F-KEY}
```
public static final int EXCL_F_KEY
```


If set, the submitted FDF shall exclude the F entry.

### EXCL_NON_USER_ANNOTS {#EXCL-NON-USER-ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```


If set, it shall include only those markup annotations whose T entry matches the name of the current user.

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

### INCLUDE_ANNOTATIONS {#INCLUDE-ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```


If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document.

### INCLUDE_APPEND_SAVES {#INCLUDE-APPEND-SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```


If set, the submitted FDF file shall include the contents of all incremental updates.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE-NO-VALUE-FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```


If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted.

### SUBMIT_COORDINATES {#SUBMIT-COORDINATES}
```
public static final int SUBMIT_COORDINATES
```


If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data.

### SUBMIT_PDF {#SUBMIT-PDF}
```
public static final int SUBMIT_PDF
```


If set, the document shall be submitted as PDF, using the MIME content type application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```


If set, field names and values shall be submitted as XFDF.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFlags() {#getFlags--}
```
public int getFlags()
```


Gets flagas of submit action

**Returns:**
int - int value
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Next actions in sequence.

**Returns:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - ActionCollection object
### getUrl() {#getUrl--}
```
public FileSpecification getUrl()
```


Destination URL.

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - FileSpecification value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Sets flagas of submit action

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setUrl(FileSpecification value) {#setUrl-com.aspose.pdf.FileSpecification-}
```
public void setUrl(FileSpecification value)
```


Destination URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

