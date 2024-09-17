---
title: Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator class
linktitle: IStringOutputGenerator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator class. Represents an interface for generating output to a string of differences between texts in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.comparison.outputgenerator/istringoutputgenerator/
---
## IStringOutputGenerator class


Represents an interface for generating output to a string of differences between texts.

```cpp
class IStringOutputGenerator : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>) | Generates the output based on the differences between texts and saves it to a file. |
| virtual [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\>) | Generates the output based on the differences between texts and saves it to a file. |
## See Also

* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../)
* Library [Aspose.PDF for C++](../../)
