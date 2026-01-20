---
title: System::Text::UTF8Encoding class
linktitle: UTF8Encoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::UTF8Encoding class. UTF-8 encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2800
url: /cpp/system.text/utf8encoding/
---
## UTF8Encoding class


UTF-8 encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UTF8Encoding : public System::Text::ICUEncoding
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones encoding object. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares with object. |
| [GetHashCode](./gethashcode/)() const override | Gets encoding hash code. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Get the maximum number of bytes needed to encode a specified number of characters. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Get the maximum number of characters needed to decode a specified number of bytes. |
| [GetPreamble](./getpreamble/)() override | Get codepage preamble. |
| [operator==](./operator==/)(const UTF8Encoding\&) const | Compares encodings parameters. |
| [UTF8Encoding](./utf8encoding/)() | Constructor. |
| [UTF8Encoding](./utf8encoding/)(bool) | Constructor. |
| [UTF8Encoding](./utf8encoding/)(bool, bool) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Default codepage value. |
| static constexpr [UTF8_CODE_PAGE](./utf8_code_page/) | RTTI information. |
## See Also

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
