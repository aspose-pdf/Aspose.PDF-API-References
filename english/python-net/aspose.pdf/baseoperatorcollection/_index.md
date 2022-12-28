---
title: BaseOperatorCollection
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents base class for operator collection.
type: docs
weight: 70
url: /python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Represents base class for operator collection.

The BaseOperatorCollection type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_fast_text_extraction_mode|Indicates wheather collection is limited to fast text extraction|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets operator by its index.|
## Methods
| Name | Description |
| :- | :- |
|suppress_update()|Suppresses update contents data.<br/>            The contents stream is not updated until ResumeUpdate is called.|
|resume_update()|Resumes document update.<br/>            Updates contents stream in case there are any pending changes.|
|insert(index, op)|Inserts operator into collection.|
|cancel_update()|Cancels last update.<br/>            This method may be called when the change should not raise contents update.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

