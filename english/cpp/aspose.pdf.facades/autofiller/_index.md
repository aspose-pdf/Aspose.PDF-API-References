---
title: Aspose::Pdf::Facades::AutoFiller class
linktitle: AutoFiller
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::AutoFiller class. Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream. It has two template file input modes:input as a stream or a pdf file. It has four types of output modes:one merged stream, one merged file, many small streams, many small files. It can recieve literal data contained in a System.Data.DataTable in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/autofiller/
---
## AutoFiller class


Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream. It has two template file input modes:input as a stream or a pdf file. It has four types of output modes:one merged stream, one merged file, many small streams, many small files. It can recieve literal data contained in a [System.Data.DataTable](../../system.data/datatable/).

```cpp
class AutoFiller : public Aspose::Pdf::Facades::ISaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [AutoFiller](./autofiller/)() |  |
| [BindPdf](./bindpdf/)(System::String) override | Binds a [Pdf](../../aspose.pdf/) file. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binds a [Pdf](../../aspose.pdf/) file. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Document\>) override | Binds a [Pdf](../../aspose.pdf/) document. |
| [Close](./close/)() override | Closes the object and output streams. |
| [Dispose](./dispose/)() override | Closes the object and output streams. |
| [get_BasicFileName](./get_basicfilename/)() const | Gets the basic file name if many small files will be generated. The generated file will be like "BasicFileName0","BasicFileName1",... It works with another property [GeneratingPath](../)GeneratingPath. |
| [get_GeneratingPath](./get_generatingpath/)() const | Gets the Generating Path of the small pdf files if many small pdf files to be generated. It works with another property [BasicFileName](../)BasicFileName. One of the four output modes. |
| [get_InputFileName](./get_inputfilename/)() const | Gets the input template file. One of two input modes. |
| [get_InputStream](./get_inputstream/)() const | Gets the input template stream. One of two input modes. |
| [get_OutputFileName](./get_outputfilename/)() const | Gets the one big merged output file. One of the four output modes. |
| [get_OutputStream](./get_outputstream/)() const | Gets the OutputStream. One of four output modes. Its classical use case is Response.OutputStream. Please refer to the online demo. |
| [get_OutputStreams](./get_outputstreams/)() const | Gets the many Output Streams. One of four output modes. |
| [Save](./save/)() | Saves all the pdfs. |
| [Save](./save/)(System::String) override | Saves all the pdfs. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves all the pdfs. |
| [set_BasicFileName](./set_basicfilename/)(System::String) | Sets the basic file name if many small files will be generated. The generated file will be like "BasicFileName0","BasicFileName1",... It works with another property [GeneratingPath](../)GeneratingPath. |
| [set_GeneratingPath](./set_generatingpath/)(System::String) | Sets the Generating Path of the small pdf files if many small pdf files to be generated. It works with another property [BasicFileName](../)BasicFileName. One of the four output modes. |
| [set_InputFileName](./set_inputfilename/)(System::String) | Sets the input template file. One of two input modes. |
| [set_InputStream](./set_inputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the input template stream. One of two input modes. |
| [set_OutputFileName](./set_outputfilename/)(System::String) | Sets the one big merged output file. One of the four output modes. |
| [set_OutputStream](./set_outputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the OutputStream. One of four output modes. Its classical use case is Response.OutputStream. Please refer to the online demo. |
| [set_OutputStreams](./set_outputstreams/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>) | Sets the many Output Streams. One of four output modes. |
| [set_UnFlattenFields](./set_unflattenfields/)(System::ArrayPtr\<System::String\>) | Sets the fields which will not be flattened. If this property is not set, all the fields will be flattened. |
## See Also

* Class [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
