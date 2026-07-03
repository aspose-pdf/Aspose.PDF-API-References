---
title: PdfAction
linktitle: PdfAction
second_title: Aspose.PDF for Java API Reference
description: Represents Action in PDF document
type: docs
weight: 3670
url: /java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

Represents Action in PDF document

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | Gets string for ECMAScript Action. |
| [getNext](#getNext--) | Next actions in sequence. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

Gets string for ECMAScript Action.

**Returns:**
Return string for JS entry for ECMAScript Action or null else.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Next actions in sequence.

**Returns:**
ActionCollection object
