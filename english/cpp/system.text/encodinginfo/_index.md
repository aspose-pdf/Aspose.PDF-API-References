---
title: System::Text::EncodingInfo class
linktitle: EncodingInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncodingInfo class. Brief info on encoding. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1900
url: /cpp/system.text/encodinginfo/
---
## EncodingInfo class


Brief info on encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncodingInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [EncodingInfo](./encodinginfo/)(int, const String\&, const String\&) | Constuctor. |
| [get_CodePage](./get_codepage/)() const | Gets codepage ID. |
| [get_DisplayName](./get_displayname/)() const | Gets full localized encoding name. |
| [get_Name](./get_name/)() const | Gets encoding short name. |
| [GetEncoding](./getencoding/)() | Gets encoding described by info. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
