---
title: PdfAction
second_title: Aspose.PDF for Java API Reference
description: Represents Action in PDF document
type: docs
weight: 223
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
| [execute(IDocument document)](#execute-com.aspose.pdf.IDocument-) |  |
| [createAction(IPdfDictionary action)](#createAction-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
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
[ActionCollection](../../com.aspose.pdf/actioncollection)
### execute(IDocument document) {#execute-com.aspose.pdf.IDocument-}
```
public void execute(IDocument document)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |

### createAction(IPdfDictionary action) {#createAction-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public static PdfAction createAction(IPdfDictionary action)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| action | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction)
