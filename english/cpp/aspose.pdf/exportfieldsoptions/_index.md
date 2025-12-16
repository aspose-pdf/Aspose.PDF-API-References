---
title: Aspose::Pdf::ExportFieldsOptions class
linktitle: ExportFieldsOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ExportFieldsOptions class. Represents base class of options for exporting form fields in C++.'
type: docs
weight: 5000
url: /cpp/aspose.pdf/exportfieldsoptions/
---
## ExportFieldsOptions class


Represents base class of options for exporting form fields.

```cpp
class ExportFieldsOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [ExportFieldsOptions](./exportfieldsoptions/)() |  |
| [get_ExportPasswordValue](./get_exportpasswordvalue/)() const | Gets a value indicating whether the password value should be exported. |
| [get_FieldSelector](./get_fieldselector/)() const | Gets a delegate that determines whether a particular field should be exported. If the delegate is **null**, all fields are exported (the default behaviour). |
| [set_ExportPasswordValue](./set_exportpasswordvalue/)(bool) | Sets a value indicating whether the password value should be exported. |
| [set_FieldSelector](./set_fieldselector/)(System::Predicate\<System::SharedPtr\<Forms::Field\>\>) | Sets a delegate that determines whether a particular field should be exported. If the delegate is **null**, all fields are exported (the default behaviour). |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
