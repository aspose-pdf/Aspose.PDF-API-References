---
title: System::Net::Http::Headers::MediaTypeHeaderValue class
linktitle: MediaTypeHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::MediaTypeHeaderValue class. Represents a MIME type in a value of the ''Content-Type'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue class


Represents a MIME type in a value of the 'Content-Type' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_CharSet](./get_charset/)() | RTTI information. |
| [get_MediaType](./get_mediatype/)() | Gets a value of the media-type header. |
| [get_Parameters](./get_parameters/)() | Returns the value parameters of the media-type header. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetMediaTypeLength](./getmediatypelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [MediaTypeHeaderValue](./) class. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)() | Constructs a new instance. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)(String) | Constructs a new instance. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [MediaTypeHeaderValue](./) class. |
| [set_CharSet](./set_charset/)(String) | Sets a character set. |
| [set_MediaType](./set_mediatype/)(String) | Sets a value of the media-type header. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Tries to convert a passed string to an instance of the [MediaTypeHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
