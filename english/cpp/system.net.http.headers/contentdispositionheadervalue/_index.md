---
title: System::Net::Http::Headers::ContentDispositionHeaderValue class
linktitle: ContentDispositionHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ContentDispositionHeaderValue class. Represents a value of the ''Content-Disposition'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue class


Represents a value of the 'Content-Disposition' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Constructs a new instance. |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)(String) | Constructs a new instance. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_CreationDate](./get_creationdate/)() | Gets the file creation date. |
| [get_DispositionType](./get_dispositiontype/)() | RTTI information. |
| [get_FileName](./get_filename/)() | Gets a value that determines how to construct a filename for storing the message payload. It is used when the entity is detached and stored in a separate file. |
| [get_FileNameStar](./get_filenamestar/)() | Gets a value that determines how to construct filenames for storing the message payload. It is used when the entities are detached and stored in separate files. |
| [get_ModificationDate](./get_modificationdate/)() | Gets the file modification date. |
| [get_Name](./get_name/)() | Gets a name for a part of the content body. |
| [get_Parameters](./get_parameters/)() | Returns a parameters collection of the 'Content-Disposition' header. |
| [get_ReadDate](./get_readdate/)() | Gets the date when the file was read the last time. |
| [get_Size](./get_size/)() | Gets an approximate file size. |
| static [GetDispositionTypeLength](./getdispositiontypelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [ContentDispositionHeaderValue](./) class. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [ContentDispositionHeaderValue](./) class. |
| [set_CreationDate](./set_creationdate/)(Nullable\<DateTimeOffset\>) | Sets the file creation date. |
| [set_DispositionType](./set_dispositiontype/)(String) | Sets a disposition type. |
| [set_FileName](./set_filename/)(String) | Sets a value that determines how to construct a filename for storing the message payload. It is used when the entity is detached and stored in a separate file. |
| [set_FileNameStar](./set_filenamestar/)(String) | Sets a value that determines how to construct filenames for storing the message payload. It is used when the entities are detached and stored in separate files. |
| [set_ModificationDate](./set_modificationdate/)(Nullable\<DateTimeOffset\>) | Sets the file modification date. |
| [set_Name](./set_name/)(String) | Sets a name for a part of the content body. |
| [set_ReadDate](./set_readdate/)(Nullable\<DateTimeOffset\>) | Sets the date when the file read the last time. |
| [set_Size](./set_size/)(Nullable\<int64_t\>) | Sets an approximate file size. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) | Tries to convert a passed string to an instance of the [ContentDispositionHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
