---
title: System::Text::ASCIIEncoding class
linktitle: ASCIIEncoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ASCIIEncoding class. Represents ASCII encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.text/asciiencoding/
---
## ASCIIEncoding class


Represents ASCII encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Methods

| Method | Description |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/)() | Constructor. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Gets max byte count possible to hold a string of known character count. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Get the maximum number of characters needed to decode a specified number of bytes. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Default codepage value. |
## See Also

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
