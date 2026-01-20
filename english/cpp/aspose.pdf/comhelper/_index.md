---
title: Aspose::Pdf::ComHelper class
linktitle: ComHelper
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ComHelper class. Provides methods for COM clients to load a document into Aspose.Pdf in C++.'
type: docs
weight: 3100
url: /cpp/aspose.pdf/comhelper/
---
## ComHelper class


Provides methods for COM clients to load a document into [Aspose.Pdf](../).

```cpp
class ComHelper : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [OpenFile](./openfile/)(System::String) | Just create and return [Document](../document/) using *filename* . The same as [Document(Stream)](../). |
| [OpenFile](./openfile/)(System::String, System::String) | Initialize and return new instance of the [Document](../document/) class for working with encrypted document. |
| [OpenFile](./openfile/)(System::String, System::String, bool) | Initialize new instance of the [Document](../document/) class for working with encrypted document. |
| [OpenFile](./openfile/)(System::String, System::SharedPtr\<LoadOptions\>) | Open an existing document from a file providing necessary converting oprions to get pdf document. |
| [OpenStream](./openstream/)(System::SharedPtr\<System::IO::Stream\>) | Initialize and return new [Document](../document/) instance from the *input*  stream. |
| [OpenStream](./openstream/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Initialize and return new [Document](../document/) instance from the *input*  stream. |
| [OpenStream](./openstream/)(System::SharedPtr\<System::IO::Stream\>, bool) | Initialize and return new [Document](../document/) instance from the *input*  stream. |
| [OpenStream](./openstream/)(System::SharedPtr\<System::IO::Stream\>, System::String, bool) | Initialize and return new [Document](../document/) instance from the *input*  stream. |
| [OpenStream](./openstream/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>) | Open and return an existing document from a stream providing necessary converting to get pdf document. |
## Remarks


Use the [ComHelper](./) class to load a document from a file or stream into a [Document](../document/) object in a COM application. The [Document](../document/) class provides a default constructor to create a new document and also provides overloaded constructors to load a document from a file or stream. If you are using Aspose.Words from a .NET application, you can use all of the [Document](../document/) constructors directly, but if you are using [Aspose.Pdf](../) from a COM application, only the default [Document](../document/) constructor is available. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
