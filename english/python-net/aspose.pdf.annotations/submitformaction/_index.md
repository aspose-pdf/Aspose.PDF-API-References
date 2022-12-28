---
title: SubmitFormAction
second_title: Aspose.PDF for Python via .NET API Reference
description: Class which describes submit-form action.
type: docs
weight: 810
url: /python-net/aspose.pdf.annotations/submitformaction/
---

## SubmitFormAction class

Class which describes submit-form action.

The SubmitFormAction type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|SubmitFormAction()|Initializes SubmitFormAction object.|
## Properties
| Name | Description |
| :- | :- |
|next|Next actions in sequence.|
|flags|Gets or sets flagas of submit action|
|url|Destination URL.|
|EXCLUDE|If clear, the Fields array specifies which fields to include in the submission.|
|INCLUDE_NO_VALUE_FIELDS|If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted.|
|EXPORT_FORMAT|If set, field names and values shall be submitted in HTML Form format.|
|GET_METHOD|If set, field names and values shall be submitted using an HTTP GET request.|
|SUBMIT_COORDINATES|If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data.|
|XFDF|If set, field names and values shall be submitted as XFDF.|
|INCLUDE_APPEND_SAVES|If set, the submitted FDF file shall include the contents of all incremental updates.|
|INCLUDE_ANNOTATIONS|If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document.|
|SUBMIT_PDF|If set, the document shall be submitted as PDF, using the MIME content type application/pdf.|
|CANONICAL_FORMAT|If set, any submitted field values representing dates shall be converted to the standard format.|
|EXCL_NON_USER_ANNOTS|If set, it shall include only those markup annotations whose T entry matches the name of the current user.|
|EXCL_F_KEY|If set, the submitted FDF shall exclude the F entry.|
|EMBED_FORM|If set, the F entry of the submitted FDF shall be a file specification containing an <br/>            embedded file stream representing the PDF file from which the FDF is being submitted.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

