---
title: System::Runtime::Serialization namespace
linktitle: System::Runtime::Serialization
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Runtime::Serialization namespace in C++.'
type: docs
weight: 6000
url: /cpp/system.runtime.serialization/
---



## Classes

| Class | Description |
| --- | --- |
| [FormatterConverter](./formatterconverter/) | Represents a base implementation of the [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) interface. |
| [IFormatterConverter](./iformatterconverter/) | Provides the connection between an instance of [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) and the formatter-provided class best suited to parse the data inside the [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Interface of object which can be serialized. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SerializationInfo](./serializationinfo/) | Holds set of named fields representing serialized object. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [StreamingContext](./streamingcontext/) | Dummy class to make StreamingContext-using translated classes compile. Do not manage instances of this class by [SmartPtr](../system/smartptr/), they must be allocated on stack only. |
