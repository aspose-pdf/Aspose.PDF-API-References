---
title: System::Net::Http::Headers::MediaTypeWithQualityHeaderValue class
linktitle: MediaTypeWithQualityHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::MediaTypeWithQualityHeaderValue class. Represents a MIME type with an additional quality factor in a value of the ''Content-Type'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue class


Represents a MIME type with an additional quality factor in a value of the 'Content-Type' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Methods

| Method | Description |
| --- | --- |
| [get_Quality](./get_quality/)() | RTTI information. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Constructs a new instance. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String) | Constructs a new instance. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String, double) | Constructs a new instance. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [MediaTypeWithQualityHeaderValue](./) class. |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Sets a quality value. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeWithQualityHeaderValue\>\&) | Tries to convert a passed string to an instance of the [MediaTypeWithQualityHeaderValue](./) class. |
## See Also

* Class [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
