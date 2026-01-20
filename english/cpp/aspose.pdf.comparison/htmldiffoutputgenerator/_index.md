---
title: Aspose::Pdf::Comparison::HtmlDiffOutputGenerator class
linktitle: HtmlDiffOutputGenerator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::HtmlDiffOutputGenerator class. Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class


Represents a class for generating html representation of texts differences. Deleted line breaks are indicated by paragraph mark.

```cpp
class HtmlDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Methods

| Method | Description |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Generates the output based on the differences between texts and saves it to a file. |
| [get_DeleteStyle](./get_deletestyle/)() const | Gets and sets the CSS-style string for Delete operation. Example: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_EqualStyle](./get_equalstyle/)() const | Gets and sets the CSS-style string for Equal operation. Example: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_InsertStyle](./get_insertstyle/)() const | Gets and sets the CSS-style string for Insert operation. Example: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_StrikethroughDeleted](./get_strikethroughdeleted/)() const | Get or set text-decoration: line-through style for the delete operation. Default value is **False**. |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)() | Creates an instance of [HtmlDiffOutputGenerator](./) class. |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)(System::SharedPtr\<OutputTextStyle\>) | Creates an instance of [HtmlDiffOutputGenerator](./) class. |
| [set_DeleteStyle](./set_deletestyle/)(System::String) | Gets and sets the CSS-style string for Delete operation. Example: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_EqualStyle](./set_equalstyle/)(System::String) | Gets and sets the CSS-style string for Equal operation. Example: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_InsertStyle](./set_insertstyle/)(System::String) | Gets and sets the CSS-style string for Insert operation. Example: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_StrikethroughDeleted](./set_strikethroughdeleted/)(bool) | Get or set text-decoration: line-through style for the delete operation. Default value is **False**. |
## See Also

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
