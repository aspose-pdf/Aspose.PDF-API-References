---
title: Aspose::Pdf::TeXFileSystemOutputDirectory class
linktitle: TeXFileSystemOutputDirectory
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXFileSystemOutputDirectory class. Implements the regular file system''s method for getting a file stream to write to in C++.'
type: docs
weight: 14800
url: /cpp/aspose.pdf/texfilesystemoutputdirectory/
---
## TeXFileSystemOutputDirectory class


Implements the regular file system's method for getting a file stream to write to.

```cpp
class TeXFileSystemOutputDirectory : public Aspose::Pdf::TeXFileSystemInputDirectory,
                                     public Aspose::Pdf::ITeXOutputDirectory
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](../texfilesysteminputdirectory/dispose/)() override | Disposes the instance. |
| [GetFile](../texfilesysteminputdirectory/getfile/)(System::String, System::String\&, bool) override | Returns the stream to read from. |
| [GetOutputFile](./getoutputfile/)(System::String, System::String\&) override | Returns the stream to write to. |
| [TeXFileSystemInputDirectory](../texfilesysteminputdirectory/texfilesysteminputdirectory/)(System::String) | Creates new instance. |
| [TeXFileSystemOutputDirectory](./texfilesystemoutputdirectory/)(System::String) | Creates new instance. |
## See Also

* Class [TeXFileSystemInputDirectory](../texfilesysteminputdirectory/)
* Class [ITeXOutputDirectory](../itexoutputdirectory/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
