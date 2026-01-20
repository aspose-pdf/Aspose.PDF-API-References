---
title: System::Text::UnicodeEncoding class
linktitle: UnicodeEncoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::UnicodeEncoding class. Unicode encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.text/unicodeencoding/
---
## UnicodeEncoding class


Unicode encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones encoding object. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares encodings. |
| [GetHashCode](./gethashcode/)() const override | Hashes encoding. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Get the maximum number of bytes needed to encode a specified number of characters. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Get the maximum number of characters needed to decode a specified number of bytes. |
| [GetPreamble](./getpreamble/)() override | Returns a sequence of bytes that denotes the encoding (e. g. BOM). |
| [operator==](./operator==/)(const UnicodeEncoding\&) const | Compares encodings by codepages and flags. |
| [UnicodeEncoding](./unicodeencoding/)() | Constructor. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool) | Constructor. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool, bool) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Big endian codepage number. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Default codepage value. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Little endian codepage number. |
## See Also

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
