---
title: Aspose::Pdf::Comparison::OutputGenerator::MarkdownDiffOutputGenerator class
linktitle: MarkdownDiffOutputGenerator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::OutputGenerator::MarkdownDiffOutputGenerator class. Represents a class for generating markdown representation of texts differences. Because of the markdown syntax, it is not possible to show changes to whitespace characters. Selection of changes makes adding whitespace characters around formatting, otherwise markdown viewer will not correctly display the text. Deleted line breaks are indicated by - paragraph mark in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.comparison.outputgenerator/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class


Represents a class for generating markdown representation of texts differences. Because of the markdown syntax, it is not possible to show changes to whitespace characters. Selection of changes makes adding whitespace characters around formatting, otherwise markdown viewer will not correctly display the text. Deleted line breaks are indicated by - paragraph mark.

```cpp
class MarkdownDiffOutputGenerator : public Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator,
                                    public Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator
```

## Methods

| Method | Description |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>, System::String) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\>) override | Generates the output based on the differences between texts and saves it to a file. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\>, System::String) override | Generates the output based on the differences between texts and saves it to a file. |
| [MarkdownDiffOutputGenerator](./markdowndiffoutputgenerator/)() | Creates an instance of [MarkdownDiffOutputGenerator](./) class. |
## See Also

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../)
* Library [Aspose.PDF for C++](../../)
