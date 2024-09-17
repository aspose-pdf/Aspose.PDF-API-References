---
title: Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator class
linktitle: IFileOutputGenerator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator class. Represents an interface for generating output to a file of differences between texts in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.comparison.outputgenerator/ifileoutputgenerator/
---
## IFileOutputGenerator class


Represents an interface for generating output to a file of differences between texts.

```cpp
class IFileOutputGenerator : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>, System::String) | Generates the output based on the differences between texts and saves it to a file. |
| virtual [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\>, System::String) | Generates the output based on the differences between texts and saves it to a file. |
## See Also

* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../)
* Library [Aspose.PDF for C++](../../)
