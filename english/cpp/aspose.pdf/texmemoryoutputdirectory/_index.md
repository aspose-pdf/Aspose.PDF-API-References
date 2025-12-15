---
title: Aspose::Pdf::TeXMemoryOutputDirectory class
linktitle: TeXMemoryOutputDirectory
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXMemoryOutputDirectory class. Implements fetching an output stream from memory. You can use it, for example, when you don''t want the accompanying output (like a log file) to be written to disk but you''d like to read it afterwards from memory in C++.'
type: docs
weight: 18200
url: /cpp/aspose.pdf/texmemoryoutputdirectory/
---
## TeXMemoryOutputDirectory class


Implements fetching an output stream from memory. You can use it, for example, when you don't want the accompanying output (like a log file) to be written to disk but you'd like to read it afterwards from memory.

```cpp
class TeXMemoryOutputDirectory : public Aspose::Pdf::ITeXOutputDirectory
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Disposes the instance. |
| [GetFile](./getfile/)(System::String, System::String\&, bool) override | Returns the stream to read from. |
| [GetOutputFile](./getoutputfile/)(System::String, System::String\&) override | Returns the stream to write to. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/)() | Creates new instance. |
## See Also

* Class [ITeXOutputDirectory](../itexoutputdirectory/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
