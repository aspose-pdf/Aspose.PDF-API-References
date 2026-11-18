---
title: System::Text::EncodingProvider class
linktitle: EncodingProvider
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncodingProvider class. Represents a base class for encoding providers that supply character encoding information in C++.'
type: docs
weight: 2100
url: /cpp/system.text/encodingprovider/
---
## EncodingProvider class


Represents a base class for encoding providers that supply character encoding information.

```cpp
class EncodingProvider : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetEncoding](./getencoding/)(const String\&) | Gets the encoding associated with the specified name. |
| virtual [GetEncoding](./getencoding/)(int) | Gets the encoding associated with the specified code page identifier. |
## Remarks


Derived classes override the GetEncoding methods to provide support for specific character encodings or to override the default encoding resolution behavior of the system. 
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
