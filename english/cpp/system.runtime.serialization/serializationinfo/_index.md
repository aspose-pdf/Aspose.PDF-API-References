---
title: System::Runtime::Serialization::SerializationInfo class
linktitle: SerializationInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::Serialization::SerializationInfo class. Holds set of named fields representing serialized object. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.runtime.serialization/serializationinfo/
---
## SerializationInfo class


Holds set of named fields representing serialized object. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SerializationInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddValue](./addvalue/)(const System::String\&, float) | Puts float value. Not implemented. |
| [AddValue](./addvalue/)(const System::String\&, short) | Puts short value. Not implemented. |
| [AddValue](./addvalue/)(const System::String\&, bool) | Puts boolean value. Not implemented. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Puts object value. Not implemented. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Puts object value with specifed type. Not implemented. |
| [GetValue](./getvalue/)(const System::String\&, const System::TypeInfo\&) | Retrieves a value from the [SerializationInfo](./) store. Not implemented. |
| [SerializationInfo](./serializationinfo/)(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) | RTTI information. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
