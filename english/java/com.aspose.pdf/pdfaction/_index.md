---
title: PdfAction
second_title: Aspose.PDF for Java API Reference
description: Represents Action in PDF document
type: docs
weight: 276
url: /java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.IAppointment](../../com.aspose.pdf/iappointment)
```
public abstract class PdfAction implements IAppointment
```

Represents Action in PDF document
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfAction()](#PdfAction--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getNext()](#getNext--) | Next actions in sequence. |
| [getECMAScriptString()](#getECMAScriptString--) | Gets string for ECMAScript Action. |
### PdfAction() {#PdfAction--}
```
public PdfAction()
```


### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Next actions in sequence.

**Returns:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - ActionCollection object
### getECMAScriptString() {#getECMAScriptString--}
```
public final String getECMAScriptString()
```


Gets string for ECMAScript Action.

**Returns:**
java.lang.String - Return string for JS entry for ECMAScript Action or null else.
