---
title: Aspose::Pdf::Annotations::SubmitFormAction class
linktitle: SubmitFormAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::SubmitFormAction class. Class which describes submit-form action in C++.'
type: docs
weight: 11000
url: /cpp/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class


Class which describes submit-form action.

```cpp
class SubmitFormAction : public Aspose::Pdf::Annotations::PdfAction
```

## Methods

| Method | Description |
| --- | --- |
| [get_Flags](./get_flags/)() | Gets flagas of submit action. |
| [get_Url](./get_url/)() | Destination URL. |
| [set_Flags](./set_flags/)(int32_t) | Sets flagas of submit action. |
| [set_Url](./set_url/)(System::SharedPtr\<FileSpecification\>) | Destination URL. |
| [SubmitFormAction](./submitformaction/)() | Initializes [SubmitFormAction](./) object. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [CanonicalFormat](./canonicalformat/) | If set, any submitted field values representing dates shall be converted to the standard format. |
| static constexpr [EmbedForm](./embedform/) | If set, the F entry of the submitted FDF shall be a file specification containing an embedded file stream representing the PDF file from which the FDF is being submitted. |
| static constexpr [ExclFKey](./exclfkey/) | If set, the submitted FDF shall exclude the F entry. |
| static constexpr [ExclNonUserAnnots](./exclnonuserannots/) | If set, it shall include only those markup annotations whose T entry matches the name of the current user. |
| static constexpr [Exclude](./exclude/) | If clear, the Fields array specifies which fields to include in the submission. |
| static constexpr [ExportFormat](./exportformat/) | If set, field names and values shall be submitted in HTML Form format. |
| static constexpr [GetMethod](./getmethod/) | If set, field names and values shall be submitted using an HTTP GET request. |
| static constexpr [IncludeAnnotations](./includeannotations/) | If set, the submitted FDF file shall include includes all markup annotations in the underlying PDF document. |
| static constexpr [IncludeAppendSaves](./includeappendsaves/) | If set, the submitted FDF file shall include the contents of all incremental updates. |
| static constexpr [IncludeNoValueFields](./includenovaluefields/) | If set, all fields designated by the Fields array and the Include/Exclude flag shall be submitted. |
| static constexpr [SubmitCoordinates](./submitcoordinates/) | If set, the coordinates of the mouse click that caused the submit-form action shall be transmitted as part of the form data. |
| static constexpr [SubmitPdf](./submitpdf/) | If set, the document shall be submitted as PDF, using the MIME content type application/pdf. |
| static constexpr [Xfdf](./xfdf/) | If set, field names and values shall be submitted as XFDF. |
## See Also

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
