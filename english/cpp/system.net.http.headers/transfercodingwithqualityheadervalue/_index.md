---
title: System::Net::Http::Headers::TransferCodingWithQualityHeaderValue class
linktitle: TransferCodingWithQualityHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::TransferCodingWithQualityHeaderValue class. Represents a value with an additional quality of the ''Accept-Encoding'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.net.http.headers/transfercodingwithqualityheadervalue/
---
## TransferCodingWithQualityHeaderValue class


Represents a value with an additional quality of the 'Accept-Encoding' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TransferCodingWithQualityHeaderValue : public System::Net::Http::Headers::TransferCodingHeaderValue
```

## Methods

| Method | Description |
| --- | --- |
| [get_Quality](./get_quality/)() | RTTI information. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [TransferCodingWithQualityHeaderValue](./) class. |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Sets the quality value of the 'Accept-Encoding' header. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)() | Constructs a new instance. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)(String) | Constructs a new instance. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)(String, double) | Constructs a new instance. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingWithQualityHeaderValue\>\&) | Tries to convert a passed string to an instance of the [TransferCodingWithQualityHeaderValue](./) class. |
## See Also

* Class [TransferCodingHeaderValue](../transfercodingheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
