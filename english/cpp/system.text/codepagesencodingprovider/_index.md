---
title: System::Text::CodePagesEncodingProvider class
linktitle: CodePagesEncodingProvider
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::CodePagesEncodingProvider class. Represents an encoding provider that supplies encodings for specific code pages in C++.'
type: docs
weight: 200
url: /cpp/system.text/codepagesencodingprovider/
---
## CodePagesEncodingProvider class


Represents an encoding provider that supplies encodings for specific code pages.

```cpp
class CodePagesEncodingProvider : public System::Text::EncodingProvider
```

## Methods

| Method | Description |
| --- | --- |
| static [get_Instance](./get_instance/)() | Gets the singleton instance of the [CodePagesEncodingProvider](./). |
| [GetEncoding](./getencoding/)(const String\&) override | Gets the encoding associated with the specified name. |
| [GetEncoding](./getencoding/)(int) override | Gets the encoding associated with the specified code page identifier. |
## Remarks


This class is typically used to register and retrieve encodings for [Windows](../../system.windows/) code pages (e.g., Windows-1252, ISO-8859-1) that are not supported by default in the standard [Encoding](../encoding/) class and otherwise are available only in the desktop .NET Framework. 
## See Also

* Class [EncodingProvider](../encodingprovider/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
