---
title: System::Text::UTF32Encoding class
linktitle: UTF32Encoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::UTF32Encoding class. UTF-32 encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.text/utf32encoding/
---
## UTF32Encoding class


UTF-32 encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UTF32Encoding : public System::Text::ICUEncoding
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones encoding object. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares with object. |
| [GetHashCode](./gethashcode/)() const override | Gets encoding hash code. |
| [GetPreamble](./getpreamble/)() override | Get codepage preamble. |
| [operator==](./operator==/)(const UTF32Encoding\&) const | Compares encodings' parameters. |
| [UTF32Encoding](./utf32encoding/)() | Constructor. |
| [UTF32Encoding](./utf32encoding/)(bool, bool) | Constructor. |
| [UTF32Encoding](./utf32encoding/)(bool, bool, bool) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [BIG_UTF32_CODE_PAGE](./big_utf32_code_page/) | Magic number used by [Windows](../../system.windows/) for big endian UTF-32 codepage id. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Default codepage value. |
| static constexpr [UTF32_CODE_PAGE](./utf32_code_page/) | Magic number used by [Windows](../../system.windows/) for little endian UTF-32 codepage id. |
## See Also

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
