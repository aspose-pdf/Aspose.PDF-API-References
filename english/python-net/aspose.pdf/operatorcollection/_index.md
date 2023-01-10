---
title: OperatorCollection
second_title: Aspose.PDF for Python via .NET API Reference
description: Class represents collection of operators
type: docs
weight: 1010
url: /python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

Class represents collection of operators

The OperatorCollection type exposes the following members:
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
|insert(index, op)|Inserts operator into collection.|
|insert(at, ops)|Insert operators at the the given position.|
|insert(at, ops)|Inserts operator into collection.|
|delete(index)|Deletes operator from collection.|
|delete(ops)|Deletes operators from collection.|
|delete(list)|None|
|add(ops)|Add operators at the end of the contents operators.|
|add(ops)|Adds new operator into collection.|
|suppress_update()|Suppresses update contents data.<br/>            The contents stream is not updated until ResumeUpdate is called.|
|resume_update()|Resumes document update.<br/>            Updates contents stream in case there are any pending changes.|
|cancel_update()|Cancels last update.<br/>            This method may be called when the change should not raise contents update.|
|accept(visitor)|Accepts IOperatorSelector visitor object to process operators.|
|replace(operators)|Replace operators in collection with other operators.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

